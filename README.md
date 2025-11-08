# 📚 Library Management System

A full-stack web application built to manage and automate library operations such as book registration, user management, issue/return tracking, and payment handling. This project aims to simplify library workflows and enhance the experience for both administrators and readers.

# 🏗️ Project Structure
--bash
library-management-system/
├── src/
│   ├── main/
│   │   ├── java/com/bookStore/
│   │   │   ├── controller/         # Handles web requests
│   │   │   ├── model/              # Contains entity classes
│   │   │   ├── repository/         # JPA repositories for DB interaction
│   │   │   ├── service/            # Business logic layer
│   │   │   └── LibraryApplication.java  # Main Spring Boot class
│   │   ├── resources/
│   │   │   ├── static/             # Static assets (CSS, JS, Images)
│   │   │   │   ├── images/
│   │   │   │   └── payment.html
│   │   │   ├── templates/          # Thymeleaf HTML templates
│   │   │   │   ├── aboutus.html
│   │   │   │   ├── bookEdit.html
│   │   │   │   ├── bookList.html
│   │   │   │   ├── bookRegister.html
│   │   │   │   ├── home.html
│   │   │   │   ├── login.html
│   │   │   │   ├── myBooks.html
│   │   │   │   ├── register.html
│   │   │   │   └── settings.html
│   │   │   └── application.properties
│   └── test/java/com/bookStore/    # Test cases
├── target/                         # Compiled files
├── pom.xml                         # Maven dependencies
└── README.md
