# F2_DBMS
## EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
### AIM:
To create a student database and execute DDL queries using SQL.

### DDL (Data Definition Language)
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
### List of DDL commands:
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.
### Query:
#### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.
### SQL QUERY:
create table student(rollno int primary key, name varchar(20),age int,address varchar(100),phno varchar(10));

### OUTPUT:

![image](https://github.com/harini1006/F2_DBMS/assets/113497405/bdfc4d19-1f32-4cb7-96e4-170284e94baf)

#### 2) Change the above student table by adding another attribute department
### SQL QUERY:
alter table student add dept varchar(10);

### OUTPUT:
![image](https://github.com/harini1006/F2_DBMS/assets/113497405/5e417937-dbe4-4b05-90a5-36e2e0cd48bc)



#### 3) Drop the student table
### SQL QUERY:
drop table student;

### OUTPUT:

![image](https://github.com/harini1006/F2_DBMS/assets/113497405/1571a243-99c0-4e69-8133-b02bed5d2dad)

#### 4) Delete the student table using truncate keyword
SQL QUERY:
truncate table student;

### OUTPUT:
![image](https://github.com/harini1006/F2_DBMS/assets/113497405/5f986da4-b8fe-4099-805c-8d23c3298217)


#### 5) Rename the student table to mystudent
### SQL QUERY:
alter table student rename to mystudent;

### OUTPUT:
![image](https://github.com/harini1006/F2_DBMS/assets/113497405/44c4d2a2-ed1e-49ef-98aa-7bddc4a1b0a8)

