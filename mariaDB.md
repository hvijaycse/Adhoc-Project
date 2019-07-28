# MariaDB
### Create Database
```
create database project1;
```
### Use Database
```
use project1
```
### Create Tables
```
create table userInfo(
    -> user_id INT NOT NULL AUTO_INCREMENT,
    -> user_first_name varchar(100) NOT NULL,
    -> user_last_name varchar(100) NOT NULL,
    -> user_email varchar(200) NOT NULL,
    -> user_phone INT NOT NULL,
    -> user_password varchar(50) NOT NULL,
    -> PRIMARY KEY (user_id));

 create table testInfo(
    -> test_id INT NOT NULL AUTO_INCREMENT,
    -> test_name VARCHAR(100) NOT NULL,
    -> PRIMARY KEY (test_id));
```