-------------
Project setup
-------------


---------
JDK setup
---------
Download and install jdk-17.0.2


---------
IDE setup
---------
Download and install Apache NetBeans IDE 13

Create a new project with name 'bank management system'

Create the java files as mentioned in the repository


--------------
Database setup
--------------
Download and install mySQL workbench 8.0 CE and proceed as mentioned below-


-----------------------------
Connecting Database with java
-----------------------------

Add the below files (provided in repository) to the library of the project 'bank management system'

mysql-connector-java-8.0.28.jar

---------------------------------------------------------
Creating the Database for BANK MANAGEMENT SYSTEM Project
---------------------------------------------------------

1 - Create database with name 'bankmanagementsystem' in mysql:

create database bankmanagementsystem;

2 - Select the database you just created:

use 'bankmanagementsystem';

3 - Create our first Table in the selected database with name signup:

create table 'signup' with attributes-

form_number varchar(20), name varchar(30), father_name varchar(20), dob varchar(20), gender varchar(20),email varchar(30),
marital_status varchar(20), address varchar(40), city varchar(25), pincode int, state varchar(25);

4 - Create the second table to store personal information of user:

create table 'signup2' with attributes-

form_number varchar(20), religion varchar(20), category varchar(20), income varchar(20), education varchar(20),
occupation varchar(20), pan varchar(15), aadhar varchar(15), senior_citizen varchar(10), existingaccount varchar(10);

5 - Create the third table to store the account information of user:

create table 'signup3' with attributes-

form_number varchar(20), account_type varchar(40), card_number varchar(25), pin int, facility varchar(300);

6 - Create the Login table to store login information:

create table login with attributes-

form_number varchar(20), card_number varchar(20), pin int;

7 - Now create bank table to store transactions related information:

create table 'bank' with attributes-

pin int, date varchar(50), type varchar(20), amount int;

8 - Now create pin_change table to store pin_change information:
create table 'pinn_change' with attributes-

card_number varchar(20), old_pin int, new_pin int, change_date datetime default current_timestamp;





