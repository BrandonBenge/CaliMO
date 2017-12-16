# Managing mysql

## Starting mysql on mac
which mysql.server  #This will show you where the server commands are
mysql.server start  #This will start your mysql instance

## Setup the database the first time
mysql -uroot 

SET PASSWORD FOR 'root'@'localhost' = 'mylockerpass'

create database mylocker;

use mylocker;

CREATE USER 'mylocker_app'@'localhost' IDENTIFIED BY 'mylockerpass_app';
