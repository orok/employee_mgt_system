# employee_mgt_system
Simple employee management full stack app using React, Spring Boot and MySQL

## Prerequisites for running project:

-node 16.15.0 
-npm 8.10.0
-MySQL 8.0.29 (latest version) 
-Java 1.8.0_333
-MySQL Workbench 8.0.29

## Setup MySQL Database
start new MySQL connection on system. 
-I'm on a Mac so you can use preferences or command line
- sudo /usr/local/mysql/support-files/mysql.server start
run create database employee_management_system; 
run create table employees  (
    id int,
    first_name varchar(255),
    last_name varchar(255),
    email_id varchar(255),
);




## Setup Workspace 
1. navigate to somewhere you feel like running for me its /Users/orokukpong/Documents
2. mkdir employee-mgt-app
3. cd /employee-mgt-app
4. git init 
5. git pull git@github.com:orok/employee_mgt_system.git


# Setup Front End 
cd into react-frontend 
run npm install 
run npm start

#Setup Spring Back end 
Open project in STS or intelliJ
open employee-management-system in workspace 
Click project in menu bar-> clean 
right click project -> run as -> Maven install
right click project -> run as -> Spring Boot App

Project should be running on http://localhost:3000/

