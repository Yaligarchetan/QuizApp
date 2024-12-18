# QuizApp

## Overview

QuizApp is a web-based quiz application built using Java, Spring Boot, and connected to a MySQL database. The application allows users to create, take, and manage quizzes, offering a rich and interactive experience.

## Features


- **Quiz Management**: Create, edit, and delete quizzes.
- **Question Management**: Manage questions within quizzes with options for multiple-choice, true/false, and open-ended questions.
- **Data Persistence**: Data stored in a MySQL database for long-term storage and retrieval.


## Technologies Used

- **Backend**:
  - Java 17
  - Spring Boot 2.x
  - Spring Data JPA
 
- **Database**:
  - MySQL 8.x

- **Dependencies**:
  - Spring Web
  - Spring Boot DevTools
  - Spring Security
  - H2 Database (for development and testing)
  - MySQL driver

## Prerequisites

- JDK 11+
- MySQL Server
- IntelliJ IDEA/Eclipse/Any IDE
- Spring Boot CLI (optional)

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/quizapp.git
   cd quizapp
Configure the MySQL database:

Update application.properties with database credentials:
properties
spring.datasource.url=jdbc:mysql://localhost:3306/quizapp
spring.datasource.username=your-username
spring.datasource.password=your-password
spring.jpa.hibernate.ddl-auto=update

Build and run the application:
./mvnw spring-boot:run

Accessing the Application
The application will be available at http://localhost:8080.
Use the registration page for new users or log in using existing credentials.
Contributing
Fork it.
Create your feature branch: git checkout -b feature-name
Commit your changes: git commit -am 'Add some feature'
Push to the branch: git push origin feature-name
Submit a pull request.
