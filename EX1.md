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
create table student (rollno int,name char(20),age int,addr varchar(20),phoneno int);
```

### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/103019882/6b979ed2-047c-4dde-a851-aef53a6d81a0)


### 2) Change the above student table by adding another attribute department

### SQL QUERY:  
```
alter table student add department char(90);
```
### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/103019882/a97a440f-33e3-40da-991c-bdc1281249ef)



### 3) Drop the student table
 
### SQL QUERY:  
```
drop table student;
```


### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/103019882/e4481dbd-22aa-4d72-b768-4e88012c10f8)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```

### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/103019882/ba5fed02-c520-4e5d-8ed4-173328d3b2a4)




### 5) Rename the student table to mystudent

### SQL QUERY:  
```
alter table student rename to mystudent;
```

### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/103019882/040eb6fe-359d-4f6f-9739-1ad36ffd7bab)

