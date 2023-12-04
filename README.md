
# Path To SQL 

## Create a database
- create database [database name]

## Use a database
- use [database Name]

## Selecting a database
- select database()
call this function to select a database from your local directory

## create table 
- create table pakhi (
never forgetti to use white space spaghetti after table
- student_id INT,
- name VARCHAR(20),
- major VARCHAR(20),
- major VARCHAR(20),
- primary key (pakhi_id)
- );

## show table
- show tables;

## describe table
- describe [table name];

## Add a new column
- alter table [table name] gpa decimal(3.2);
 
 where gpa is the name of the new column that has been adedd while the function decimal(a,b) , where a→ significant figures of the integers , and b→ decimal points

 ## Delete table:
- drop table [table name]
 
 this deletes the table name , called after the drop table syntax

  ## Insert new data into table 
 - insert into [Table Name] value [{object}]

   ## Full table view
   - select *
   -  fromt [Table Name];
  
   ## insert an object into the table
   - insert into [Table Name] values (69,'Jorina','Pharmacy',3.69);
 

