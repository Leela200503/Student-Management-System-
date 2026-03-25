# Student Management System

A Full Stack Web Application for managing student records.
This project allows users to **Add, View, Update, and Delete student details** using a modern web interface.

The frontend is built using React, the backend is developed using Spring Boot, and the database used is MySQL.

---

## Features

* Add new student
* View all students
* View student details
* Update student information
* Delete student records
* REST API integration
* Responsive UI

---

## Tech Stack

Frontend
React
Axios
Bootstrap / CSS

Backend
Spring Boot
Spring Data JPA
REST API

Database
MySQL

Tools Used
Visual Studio Code (Frontend)
IntelliJ IDEA (Backend)
MySQL Workbench (Database)

---

## Project Structure

student-management-system
│
├── frontend
│     ├── src
│     ├── components
│     ├── pages
│     └── package.json
│
├── backend
│     ├── src/main/java
│     ├── controller
│     ├── model
│     ├── repository
│     └── pom.xml
│
└── README.md

---

## Application Workflow

1. User opens the React application.
2. React sends HTTP requests to the Spring Boot backend.
3. Spring Boot processes the request and communicates with the MySQL database.
4. Data is stored or retrieved from MySQL.
5. The response is returned to the React frontend and displayed to the user.

---

## API Endpoints

GET /students
Fetch all students

GET /student/{id}
Fetch student details by ID

POST /student
Add new student

PUT /student/{id}
Update student information

DELETE /student/{id}
Delete student

---

## How to Run the Project

### Backend (Spring Boot)

1. Open the backend project in IntelliJ IDEA.
2. Configure the MySQL database in `application.properties`.
3. Run the Spring Boot application.

Example configuration:

spring.datasource.url=jdbc:mysql://localhost:3306/studentdb
spring.datasource.username=root
spring.datasource.password=yourpassword

---

### Frontend (React)

1. Open the frontend folder in Visual Studio Code.
2. Install dependencies.

npm install

3. Start the React application.

npm start
4. Start the backend application.
./gradlew bootRun

The application will run on:
http://localhost:3000

---

## Screens

Home Page
Add Student Page
View Students Page
Edit Student Page

---

## Future Improvements

Authentication and Login System
Pagination for student list
Search and filter students
Better UI design
Deployment on cloud

---

## Author

Leela

Final Year Engineering Student
Full Stack Developer (React + Spring Boot)

---
