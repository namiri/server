# server
1) **Nodejs Installation:**  : ```sudo apt-get install -y nodejs ```
2) **MySql Installation:**   : ```sudo apt install mysql-server ```
3) **git Clone https://github.com/Lhardin491/bookstore-db**
4) **restart sql:** ```sudo service mysql restart ```
5) **change mysql port to 8889** : ```vi /etc/mysql/mysql.conf.d/mysqld.cnf ```
6) **create DATABASE** : ``` mysql -u root => CREATE DATABASE BOOKSTORE ```
7) **import from bookstore.sql** : ``` mysql -u root -p BOOKSTORE < sql/bookstore.sql ```
8) **run server:** : ```node ./server.js```
