# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
 create table student(rollno int,name varchar(20),age int,address varchar(20),phoneno int);
```
### OUTPUT:
![create](https://github.com/Saravana-kumar369/I2_DBMS/assets/117925254/9c95b0bc-ed78-40f7-a3d2-655a460a7511)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department varchar(10);
```
### OUTPUT:
![add](https://github.com/Saravana-kumar369/I2_DBMS/assets/117925254/e063ba12-2dd4-457c-b906-c0084f5cdc08)


### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```
### OUTPUT:
![Drop](https://github.com/Saravana-kumar369/I2_DBMS/assets/117925254/4af4cd38-85f1-4729-87e4-c8c564dc0237)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
 truncate table student;

### OUTPUT:
![trun](https://github.com/Saravana-kumar369/I2_DBMS/assets/117925254/8c868fbf-184b-4846-81c8-cceb0079572d)


### 5) Rename the student table to mystudent

### SQL QUERY: 
```
rename table student to mystudent;
```
### OUTPUT:
![rename](https://github.com/Saravana-kumar369/I2_DBMS/assets/117925254/e0ac4526-8018-45ec-88b1-dce0ff04f15b)

