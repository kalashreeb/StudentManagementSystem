# 🎓 Student Management System

### 💻 Java Full Stack Web Application

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk" />
  <img src="https://img.shields.io/badge/Spring%20Boot-3.3.5-brightgreen?style=for-the-badge&logo=springboot" />
  <img src="https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge&logo=mysql" />
  <img src="https://img.shields.io/badge/Maven-Build%20Tool-red?style=for-the-badge&logo=apachemaven" />
</p>

<p align="center">
  A simple and user-friendly Student Management System developed using Java and Spring Boot to manage student information efficiently.
</p>

---

## 🌟 About the Project

The **Student Management System** is a Java Full Stack web application designed to simplify student record management.

It allows administrators to add, view, update and delete student information through a clean and responsive web interface.

The project demonstrates practical implementation of Java programming, Object-Oriented Programming, Spring Boot, database connectivity and CRUD operations.

## 🎯 Project Objectives

- Develop a web-based student management application.
- Understand Java backend development.
- Implement CRUD operations using Spring Boot.
- Connect Java applications with MySQL.
- Understand the MVC architecture.
- Build a user-friendly frontend.

## ✨ Key Features

| Feature | Description |
|---|---|
| ➕ Add Student | Register new student details |
| 📋 View Students | Display all student records |
| ✏️ Update Student | Edit existing student information |
| 🗑️ Delete Student | Remove student records |
| 📧 Email Validation | Validate student email addresses |
| 💾 Database Storage | Store information in MySQL |

## 🛠️ Technologies Used

### Backend Development
- **Java 17:** Core programming language used to implement application logic.
- **Spring Boot:** Simplifies Java application development and configuration.
- **Spring MVC:** Handles HTTP requests and manages application flow.
- **Spring Data JPA:** Simplifies database operations.
- **Hibernate:** ORM framework used to map Java objects to database tables.

### Frontend Development
- **HTML5:** Creates the structure of web pages.
- **CSS3:** Provides styling and responsive layouts.
- **Thymeleaf:** Java template engine used to display dynamic data.

### Database
- **MySQL:** Stores student information.
- **JPA:** Manages database persistence.

### Development Tools
- **Maven:** Manages dependencies and project builds.
- **Git & GitHub:** Version control and source code management.
- **IntelliJ IDEA / Eclipse:** Java development environments.

## ☕ Java Concepts Implemented

This project helps demonstrate important Java concepts:

1. **Object-Oriented Programming (OOP)**
   - Classes and Objects
   - Encapsulation
   - Constructors
   - Methods

2. **Java Classes and Objects**
   - Student class represents student information.
   - Objects represent individual student records.

3. **Dependency Injection**
   - Spring manages application objects (Beans).
   - Constructor injection connects the controller with the repository.

4. **Exception Handling**
   - Handles invalid or missing student records.

5. **Collections**
   - Uses Java collections through repository results to manage student records.

6. **Annotations**
   - `@Entity`
   - `@Id`
   - `@GeneratedValue`
   - `@Controller`
   - `@GetMapping`
   - `@PostMapping`
   - `@Valid`

## 🏗️ Application Architecture

The application follows the **Model-View-Controller (MVC)** architecture.

```text
             USER
               |
               v
        FRONTEND (HTML/CSS)
               |
               v
        CONTROLLER LAYER
        StudentController
               |
               v
        REPOSITORY LAYER
        StudentRepository
               |
               v
          SPRING DATA JPA
               |
               v
          MYSQL DATABASE
```

### Main Components

| Component | Responsibility |
|---|---|
| Model | Represents student data |
| Controller | Handles user requests |
| Repository | Performs database operations |
| View | Displays student information |
| MySQL | Stores student records |

## 📂 Project Structure

```text
StudentManagementSystem/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── com/example/studentmanagement/
│       │       ├── controller/
│       │       │   └── StudentController.java
│       │       │
│       │       ├── model/
│       │       │   └── Student.java
│       │       │
│       │       ├── repository/
│       │       │   └── StudentRepository.java
│       │       │
│       │       └── StudentManagementApplication.java
│       │
│       └── resources/
│           ├── static/
│           │   └── style.css
│           │
│           ├── templates/
│           │   ├── students.html
│           │   └── student-form.html
│           │
│           └── application.properties
│
├── pom.xml
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### Prerequisites

Install the following software:

- Java JDK 17 or higher
- Apache Maven
- MySQL Server
- IntelliJ IDEA or Eclipse

### Step 1: Clone the Repository

```bash
git clone https://github.com/kalashreeb/StudentManagementSystem.git
```

### Step 2: Open the Project

Open the downloaded project in IntelliJ IDEA or Eclipse.

### Step 3: Configure MySQL

Open:

`src/main/resources/application.properties`

Update your MySQL credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/student_management?createDatabaseIfNotExist=true
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD
```

Replace `YOUR_PASSWORD` with your local MySQL password.

### Step 4: Run the Application

From the project directory, execute:

```bash
mvn spring-boot:run
```

### Step 5: Open in Browser

Visit:

http://localhost:8080

🎉 Your Student Management System is ready!

## 🔄 CRUD Operations

CRUD stands for:

- **Create:** Add new student records.
- **Read:** Retrieve and display student details.
- **Update:** Modify existing student information.
- **Delete:** Remove student records from the database.

These operations are implemented using Spring Data JPA.

## 📚 Learning Outcomes

Through this project, I gained practical understanding of:

- Java application development.
- Object-Oriented Programming concepts.
- Spring Boot application structure.
- MVC architecture.
- Database connectivity using MySQL.
- CRUD operations using Spring Data JPA.
- Frontend and backend integration.
- Maven dependency management.
- Git and GitHub version control.

## 🚀 Future Enhancements

- Admin login and authentication.
- Student search functionality.
- Pagination and sorting.
- Student attendance management.
- Role-based access control.
- REST API integration.
- Dashboard with student statistics.

## 👩‍💻 Developer

**Kalashree B.**

🎓 Computer Science and Engineering Student

🏫 Cambridge Institute of Technology, Bengaluru

🔗 GitHub: [@kalashreeb](https://github.com/kalashreeb)

---

<p align="center">
  ⭐ If you find this project useful, consider giving it a star!
</p>

<p align="center">
  <b>Built with ❤️ using Java and Spring Boot</b>
</p>
