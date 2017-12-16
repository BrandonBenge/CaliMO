# Managing mysql

## Starting mysql on mac
### This will show you where the server commands are
which mysql.server  

### This will start your mysql instance
mysql.server start  

## Setup the database the first time
mysql -uroot 

SET PASSWORD FOR 'root'@'localhost' = 'mylockerpass';

create database mylocker;

use mylocker;

CREATE USER 'mylocker_app'@'localhost' IDENTIFIED BY 'mylockerpass_app';
