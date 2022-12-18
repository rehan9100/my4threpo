# Install & configure PHP 73 on Linux

# Install httpd24 on linux
```
   sudo yum install httpd24
```
# Start the service httpd
```
   service httpd start
```
# install php version 73 and mysql
```
   sudo yum install php73 php73-mysql php-mbstring
```
# After installing go html directory

```
cd /var/www/html
```
# create file give name phpinfo.php
```
   sudo vi phpinfo.php
```
# <?php
# phpinfo();
   
# Install Mysql database
# First Add Root Password

```
  passwd root
  service sshd reload
  yum install mysql57-server
  service mysqld start
  service mysqld reload
  chkconfig mysqld on
  mysql_secure_installation
```
# login to mysql server

```
  mysql -uroot -p
```
# Test database

```
  show databases;
  create database [databasename];
  show tables;
  describe [table name];
````
