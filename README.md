# Student-Result-Management-System


Before doing the project please create the database and table for admin and student



 create database srms;
 
 
 use srms;


 create table student(course varchar(20),branch varchar(50),rollNo varchar(10)primary key,name varchar(100),fatherName varchar(100),gender varchar(10));

 create table result(rollNo varchar(10)primary key,s1 int(3),s2 int(3),s3 int(3),s4 int(3),s5 int(3),s6 int(3),s7 int(3));
