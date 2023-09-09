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
create table student(rollno int(8),name varchar(20),age int(2),address varchar(50),phoneno int(10));
```

### OUTPUT:
![create](https://github.com/dineshgl/I2_DBMS/assets/117925254/cdad9989-972a-408d-a00a-0975532799ae)


### 2) Change the above student table by adding another attribute department

### SQL QUERY:
```
 alter table student add department varchar(10);
```

### OUTPUT:
![add](https://github.com/dineshgl/I2_DBMS/assets/117925254/ab10031b-5673-40c1-b61d-dac133cd9dfe)


### 3) Drop the student table
 
### SQL QUERY: 
```
 drop table student;
```

### OUTPUT:
![Drop](https://github.com/dineshgl/I2_DBMS/assets/117925254/2bbe346b-b5f5-463b-8488-686ac8c867b3)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```

### OUTPUT:
![trun](https://github.com/dineshgl/I2_DBMS/assets/117925254/f269c38c-be6b-410e-9e56-a6a06c9e9f06)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```
rename table student to mystudent;
```

### OUTPUT:
![rename](https://github.com/dineshgl/I2_DBMS/assets/117925254/2083c564-bca9-4d34-a660-7b33f05b3ff6)
