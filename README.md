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
 create table students(rollno int,name varchar(20),age int,address varchar(20),phoneno int);

### OUTPUT:
![image](https://github.com/22009011/I2_DBMS/assets/118343461/c7666b70-aa14-44e5-949e-28c031c41e58)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
 insert into students values(112,'jk',20,'no40 cuddalore',2543256556);
 insert into students values(110,'thanjiyappan',19,'no 36 vellore',25432564764);
### OUTPUT:

![image](https://github.com/22009011/I2_DBMS/assets/118343461/e6dbd76b-7ae4-4553-97f1-36586c833fde)

### 3) Drop the student table
 
### SQL QUERY: 
DROP TABLE students;

### OUTPUT:
![image](https://github.com/22009011/I2_DBMS/assets/118343461/756bcab5-5743-4031-975f-ccf266567bd2)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
 TRUNCATE TABLE mystudents;

### OUTPUT:
![image](https://github.com/22009011/I2_DBMS/assets/118343461/885a7f9e-4a54-468f-87fa-8b20d04c2fa9)



### 5) Rename the student table to mystudent

### SQL QUERY: 
 ALTER TABLE student RENAME to mystudents;

### OUTPUT:
![image](https://github.com/22009011/I2_DBMS/assets/118343461/320983c9-106d-479d-8d51-4095cc47945a)
