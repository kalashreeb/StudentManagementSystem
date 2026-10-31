# Student Management System

A beginner-friendly Java full-stack CRUD project using **Java 17, Spring Boot, Spring Data JPA, Thymeleaf, HTML/CSS, and MySQL**.

## Features
- View all student records
- Add a student
- Edit student details
- Delete a student
- Server-side validation for name, email, and department
- MySQL persistence

## Requirements
- JDK 17+
- Maven 3.6+
- MySQL Server
- IntelliJ IDEA / Eclipse / VS Code

## Run locally
1. Create a MySQL user/database, or use the default local MySQL root account.
2. Open `src/main/resources/application.properties`.
3. Change `spring.datasource.password=CHANGE_ME` to your local MySQL password.
4. From the project folder, run:

   ```bash
   mvn spring-boot:run
   ```

5. Open http://localhost:8080

The database `student_management` is created automatically if the MySQL user has permission. Hibernate creates/updates the `students` table.

## Project structure
```text
src/main/java/com/example/studentmanagement/
  controller/StudentController.java
  model/Student.java
  repository/StudentRepository.java
  StudentManagementApplication.java
src/main/resources/
  static/style.css
  templates/students.html
  templates/student-form.html
  application.properties
```

## Push to GitHub
1. Create a new empty repository on GitHub, for example `student-management-system`.
2. Extract this ZIP and open a terminal in the extracted project folder.
3. Run:

   ```bash
   git init
   git add .
   git commit -m "Initial commit: Student Management System"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/student-management-system.git
   git push -u origin main
   ```

Replace `YOUR-USERNAME` with your GitHub username.

## Important
- Do not upload your real database password. Keep it local.
- This is a starter academic project. Add authentication/roles, search, pagination, and tests before presenting it as a production-ready application.
