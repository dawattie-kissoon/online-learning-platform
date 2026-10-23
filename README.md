 Web Application Development

 Group Name: The Dev Duo

Group Members
- Great Opiti: A Computer Programming student interested in web development and new technologies.
- Dawattie Kissoon: A Computer Programming student interested in building useful applications and improving programming skills.
 Project Category
Online Learning Platform

Project Description
Our project is an Online Learning Platform where students can enroll in courses, view assignments, submit their work, and check their grades. Instructors can create courses, post assignments, and grade student work.

We chose this project to help students and instructors. It will also help us learn more about Spring Boot, Thymeleaf, and databases.

Domain Model
1.	Student – stores information about students.
student_id (PK), first_name, last_name, email, password 
2.	Instructor – Stores information about teachers. 
instructor_id (PK), first_name, last_name, email, password 
3.	Course – Stores the courses available on the platform
course_id (PK), title, description, instructor_id (FK)
4.	Enrollment – Records which students join which courses.
enrollment_id (PK), student_id (FK), course_id (FK), enrollment_date
5.	Module – Organizes a course into learning sections
module_id (PK), course_id (FK), title, description 
6.	Assignment – Stores work that students need to complete
assignment_id (PK), module_id (FK), title, due_date, instructions 
7.	Submission – Records the work submitted by each student
submission_id (PK), assignment_id (FK), student_id (FK), submitted_at, file_url
8.	Grade – Stores the result and feedback for submitted work. 
grade_id (PK), submission_id (FK), score, feedback, graded_at


 Technologies
- Java
- Spring Boot
- Thymeleaf
- Database

Design
Our project includes an ER diagram and UI wireframes.
