# EXP NO 2: DATA DEFINITION LANGUGE COMMANDS 
### DATE
## AIM:
To create a student database and execute DDL queries using SQL.


## THEORY
### DDL (Data Definition Language)

* DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema.
* It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database.
* DDL is a set of SQL commands used to create, modify, and delete database structures but not data.
* These commands are normally not used by a general user, who should be accessing the database via an application.

 
### List of DDL commands: 
1. CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
2. DROP: This command is used to delete objects from the database.
3. ALTER: This is used to alter the structure of the database.
4. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
5. RENAME: This is used to rename an object existing in the database.

## Query:
### 1) Create a database studentdb

### SQL QUERY:
create database student_db;
### OUTPUT:
![w1](https://github.com/LATHIKESHWARAN/DBMS/assets/119393556/dd3faa1b-cfa8-4257-8257-b75819d2de59)

### 2) Create a table student  and insert any two rows with the following fieds RegisterNumber,Name,Age,Address,Phone number

### SQL QUERY: 
create table student(Regno int, Name varchar(20),Age int,Address varchar(50),Phonenumber varchar(10));

### OUTPUT:
![w2](https://github.com/LATHIKESHWARAN/DBMS/assets/119393556/3faa1e7f-1e70-4ca9-b4ba-37bc4df347f3)

### 3) Alter the above student table by adding another attribute department

### SQL QUERY: 
alter table student add dept varchar(20);
### OUTPUT:
![w3](https://github.com/LATHIKESHWARAN/DBMS/assets/119393556/354130dd-1309-4a92-b19c-c34fabd92b6e)

### 4) Rename the student table to mystudent

### SQL QUERY: 
rename table student to mystudent;


### OUTPUT:
![w4](https://github.com/LATHIKESHWARAN/DBMS/assets/119393556/693bf5ae-c4c1-4877-86ec-55c21e002cc4)

### 5) Delete the mystudent rows using truncate keyword

### SQL QUERY: 
truncate table mystudent;

### OUTPUT:
![w5](https://github.com/LATHIKESHWARAN/DBMS/assets/119393556/2bcb1924-0b23-44f4-976f-c415d626dc38)

### 6) Drop the mystudent table
 
### SQL QUERY: 
drop table mystudent;

### OUTPUT:
![w6](https://github.com/LATHIKESHWARAN/DBMS/assets/119393556/60296d91-a76c-481c-8f84-c6dfecf48df0)








## Result:
         Thus the basic DDL commands in SQL are executed. 


