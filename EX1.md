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
create table student(rollno numeric(4), name varchar(50), age numeric(2),
address varchar(10), phoneno numeric(10));



### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/119393540/d1e4e3ee-b173-4418-8e4f-41df65fb2433)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student add department varchar(4);
### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/119393540/6e4d1ed7-9418-438a-9570-3876187ff7c6)


### 3) Drop the student table
 
### SQL QUERY: 
drop table studentz;

### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/119393540/ae828397-5a92-41d2-a7b2-1f6a90c71eaf)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:

![image](https://github.com/dineshgl/G2_DBMS/assets/119393540/06e4d752-457d-4f78-914f-b4f680b6f68b)


### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student rename to my_student;

### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/119393540/3bb3087a-e20a-4f36-abbe-726ac9da4502)
