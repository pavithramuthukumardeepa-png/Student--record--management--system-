Title: Student Record Management System

Problem Statement: 
Many educational institutions still rely on manual processes for managing student records. This leads to data inconsistency, time-consuming retrieval, and difficulty in generating reports. An automated system is needed to streamline student data management.

Objective: 
To develop a Student Record Management System that efficiently stores, manages, and retrieves student information. The system should reduce manual work, minimize errors, and provide quick access to student records.

Modules:
1. Student Management - Add, Update, Delete, View student details
2. Enrollment Management - Handle student course enrollments and subjects
3. Search Management - Search students by ID, Name, Department
4. Report Management - Generate academic reports, attendance, marksheets

Database Design:

1. Student Table
Field Name   | Data Type    | Constraints
-------------|--------------|-------------
Student_ID   | INT          | Primary Key, Auto Increment
Name         | VARCHAR(50)  | Not Null
Gender       | VARCHAR(10)  | Not Null
Department   | VARCHAR(50)  | Not Null
Email        | VARCHAR(100) | Unique
Phone        | VARCHAR(15)  | 
DOB          | DATE         | 

2. Enrollment Table
Field Name    | Data Type    | Constraints
--------------|--------------|
