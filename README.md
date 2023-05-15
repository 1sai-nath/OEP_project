# OEP_project
# Online Examination Portal

Welcome to the Online Examination Portal project! This system is designed to provide a convenient and efficient platform for conducting online examinations. It enables users to create, manage, and participate in exams, while ensuring security and integrity of the assessment process.

## Table of Contents

1. [Introduction](#introduction)
2. purpose
3. [Features](#features)
4. UI representation of the app (images)
5. Functional Requirement
6. [Installation](#installation)
7. [Usage](#usage)
8. [Security](#security)



## Introduction

The Online Examination Portal is a web-based application developed to streamline the examination process. It provides an intuitive interface for administrators to create and manage exams, and for participants to take exams remotely. The system ensures fairness, security, and reliability throughout the examination process.

## PURPOSE:-
The purpose of on-line test simulator is to take online test in an efficient manner and no time wasting for checking the paper. The main objective of on-line test simulator is to efficiently evaluate the candidate thoroughly through a fully automated system that not only saves lot of time but also gives fast results.For students they give papers according to their convenience and time and there is no need of using extra thing like paper, pen etc.


## Features

- User authentication: Participants and administrators can create accounts and log in securely.
- Exam creation and management: Administrators can create exams, define question banks, set time limits, and assign appropriate question sets.
- Question types: The system supports various question types, such as multiple choice, true/false, and descriptive questions.
- Exam participation: Participants can view available exams, select and attempt exams within the specified time limits.
- Instant feedback: Participants receive immediate feedback on their performance after completing an exam.
- Result generation: The system automatically calculates and generates results for each participant.
- Analytics and reporting: Administrators can generate reports on exam performance, individual scores, and statistical analysis.
- Time management: The system enforces time limits for exams, ensuring fairness and preventing cheating.
- Security measures: Measures are in place to prevent unauthorized access, protect data integrity, and detect any suspicious activities.

## Functional Requirement
# Admin 
The system will check the validation for admin login
The System will allow the admin to manage set exams,set question papers, results and student list.
The system will allow the admin to update (add ,delete)Exams/Question papers.
The System will allow the admin to fetch Result and Student list who has registered.

# Student
The students will allowed to Register and login for portal. If student already register then system will check the validation for student login.
The student will allowed to see exam details on dashboard.
The student will allowed to start exam by click on button .
After the exam submission result will appear on dashboard

## UI representation of the app (images)
Admin Table:-
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/aed53cbb-fa57-44a9-9083-13dc39ee9a87)
Exam Table:-
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/964038d3-724f-4d70-a475-b79f9fa11446)
Student Table:-
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/3bd06dff-c387-4639-9921-10275b40518b)
Student Table:-
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/d8303438-d133-42dd-bc33-e8c62d877fe7)
HOME PAGE VIEW:
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/e2918308-6912-4e28-9885-c3e273126ce7)
User (Student registered) :-
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/d691fea5-9f95-4131-85b8-30dd959f54b0)
Student Login:-
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/3e2485bc-65ad-40f0-97fd-62551cc74fcd)
Instruction:-
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/1f705b6c-cc91-4e3b-952e-5d1119c93146)
Que:-
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/324adbe1-62b9-4095-a399-69bf6d5c028b)
Result:-
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/1e2d8d47-b3a3-4ca3-9297-2cabcbb120fb)
Admin:-
insert into examsystem.user (userid,age,pwd,role) values ("vithal",25,123,"Admin");
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/bc6552d3-50ce-4239-9d3b-6abe90b79a04)
Admin Login:-
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/7de7479c-711f-469e-901c-99d795da848c)
Click Login:-
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/ba9e6abd-362c-4fda-999f-109af2cb42ea)
Click Subject :- Add Subject
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/733ef374-2174-4ba1-a187-f82e9922ef4a)
Set Question Paper :
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/e8723a68-ee0f-4187-b988-2da2e89a7dab)
Exam Performance :
![image](https://github.com/1sai-nath/OEP_project/assets/121101770/346bceda-12f3-4ce9-815f-bc6717423fcd)



## Installation

To install and set up the Online Examination Portal, follow these steps:

1. Clone the repository: `https://github.com/1sai-nath/OEP_project/new/master'
2. Install the required dependencies using a package manager like npm or yarn.
3. Set up the database by importing the provided SQL file or using the provided database migration scripts.
4. Configure the database connection in the application's configuration file.
5. Start the application server.
6. Access the portal through a web browser.

## Usage

1. As an administrator, log in to the portal using your credentials.
2. Create exams by defining question banks, setting time limits, and assigning question sets.
3. Participants can log in to their accounts and view available exams.
4. Participants select an exam and answer the questions within the given time limit.
5. After submitting the exam, participants receive instant feedback on their performance.
6. Administrators can generate reports and analyze exam results.

## Security

The Online Examination Portal takes security seriously and implements several measures to ensure the integrity of the examination process:

- User authentication: Users must create accounts and log in securely using their credentials.
- Access control: Different user roles (administrator, participant) have different levels of access and permissions.
- Secure connection: The application uses encryption (HTTPS) to protect data transmission.
- Data encryption: Sensitive user data and passwords are encrypted when stored in the database.
- Input validation: The system validates and sanitizes user input to prevent common security vulnerabilities such as SQL injection and cross-site scripting (XSS).
- Session management: User sessions are managed securely to prevent session hijacking or fixation attacks.
- Audit logs: The system logs important events and actions for auditing and troubleshooting purposes.
- Regular updates: The application is regularly updated with security patches to address any potential vulnerabilities.

