# Requirements 
 ## Introduction
 The primary purpose of Student information system is to simplify teachers and staff work, by automating all student related operations and streamlining their routine tasks.

## Research 
The primary functionality of Student Information system is to manage student information data efficiently. 

The software helps the schools to reward students with a merit system and promote them to the next standard.


## Key Features of Student Information Management
1. Add/Delete the Details of the Students
2. Attendance Monitoring of the students
3. Set/Edit Eligibility criteria for exams
4. Check Eligible Students for Exams
5. Print all the records of the students

## Approach 
The idea is to form an individual function for each operation. All the functions are unified together with switch cases to form software. Below is the illustration of the functions:
1. execute(): This function will shows the available choices for the software and will perform the following functionality using Switch Statements.
They are add Student Details, Show Eligible Students, delete Student Record, Update Eligibility Criteria, Print Details of Students.

2. add(): This function that get the data from the user and update the list of the students. While adding the student into the list, check for the uniqueness of the Roll Number of the student. Details of the students to be added are: Name of Student, Roll Number, Fees Status, Attendance Record of student.

3. eligibleStudents(): This function shows the previous attendance percentage required for exams and get the data from the user and update the eligibility for the exams. It also updates the fee status required for the eligibility of exams by iterating over the List of the student records and for every student check the attendance percentage is above the percentage required and fee status of the student.

4. print_student(): This function iterate over the list of students and print the details of the student.

5. delete(): This function get the student roll number to delete the student record and update the student’s list.

## SWOT ANALYSIS

![23037-swotheadfinal](https://user-images.githubusercontent.com/57322769/132169738-7f7f1251-0042-4d57-87ed-93482f2e809a.jpg)

## 4W's and 1'H
## Who: 
This software can be used in all schools, colleges and universities.
## What:
The system ensures overall student development, along with eliminating the tedious admin tasks. It is easy to maintain and manage an ERP system than a hand written file.
## Where:
This software can be used all across the globe.
## How:
Enhance the efficiency of schools in meeting their requirements and capabilities. Communicate the key information and advice for good ecosystem.

# Detail Requirements
## High level requirements

|ID	  |Description 	                                  |Category  |Status    |
|:----|:----------------------------------------------|:---------|:----------|
|HR01	|User should be able to add a new student record| Technical|Implemented|
|HR02	|User should be able to update a student record	| Technical|Implemented|
|HR03	|User should be able to delete a student record	| Technical|Implemented|
|HR04	|User should be able to read data from a file	  |Technical|Implemented|

## Low level requirements
|ID   |Description                                                                                            |HLR ID    |Status      |
|:----|:------------------------------------------------------------------------------------------------------|:---------|:-----------|
|LR01 |While adding the student into the list, check for the uniqueness of the Roll Number of the student.    |HR01      |Implemented|
|LR02 |User should get the data from the students and update the eligibility for the exams. User should  updates the fee status required for the eligibility of exams.       |HR02      |Implemented|                                        
|LR03 |User should get the student roll number to delete the student record and update the student’s list.    |HR03      |Implemented|
|LR04 |User should be able to read the read the data by searching student's roll number or by printing all the available records.|HR04  |Implemented|
       
