
## EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE:
### AIM:
To create a student database and execute DDL queries using SQL.

### DDL (Data Definition Language)
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
### List of DDL commands:
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.
### Query:
#### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.
### SQL QUERY:
create table students(rollno int primary key, name varchar(20),age int,address varchar(100),phno varchar(10));

### OUTPUT:
![Screenshot 2023-10-05 091802](https://github.com/harini1006/F2_DBMS/assets/113497405/615772e3-019d-466f-bddc-9a35616b3340)


#### 2) Change the above student table by adding another attribute department
### SQL QUERY:
alter table students add dept varchar(10);

### OUTPUT:

![Screenshot 2023-10-05 091958](https://github.com/harini1006/F2_DBMS/assets/113497405/63a9efb5-142b-4847-b352-41ef00542cea)



#### 3) Drop the student table
### SQL QUERY:
drop table students;

### OUTPUT:
![image](https://github.com/harini1006/F2_DBMS/assets/113497405/eafa9619-7b03-48e1-b2fe-f2d87c0cc6c2)


#### 4) Delete the student table using truncate keyword
### SQL QUERY:
truncate table students;

### OUTPUT:
![image](https://github.com/harini1006/F2_DBMS/assets/113497405/5f986da4-b8fe-4099-805c-8d23c3298217)


#### 5) Rename the student table to mystudent
### SQL QUERY:
alter table student rename to mystudent;

### OUTPUT:
![image](https://github.com/harini1006/F2_DBMS/assets/113497405/44c4d2a2-ed1e-49ef-98aa-7bddc4a1b0a8)

