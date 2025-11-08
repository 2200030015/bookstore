<!-- PROJECT BANNER -->
<p align="center">
  <img src="https://github.com/2200030015/bookstore/blob/main/src/main/resources/static/images/banner.png" alt="Library Management System Banner" width="800"/>
</p>

<h1 align="center">📚 Library Management System</h1>

<p align="center">
  A full-stack web application built to manage and automate library operations such as book registration, user management, issue/return tracking, and payment handling.<br>
  This project simplifies library workflows and enhances the experience for both administrators and readers.
</p>

---

## 🏷️ Badges

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-orange?logo=openjdk&logoColor=white" alt="Java 17"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-3.0-brightgreen?logo=springboot" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/MySQL-Database-blue?logo=mysql" alt="MySQL"/>
  <img src="https://img.shields.io/badge/Build-Maven-red?logo=apachemaven" alt="Maven"/>
  <img src="https://img.shields.io/badge/Frontend-Thymeleaf%2C%20HTML%2C%20CSS-yellow" alt="Frontend"/>
  <img src="https://img.shields.io/github/license/2200030015/bookstore?color=purple" alt="License"/>
</p>

---

## 🏗️ Project Structure
```bash
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


# ✨ Features
📖 Book Management — Add, edit, delete, and view books.
👥 User Management — Register, login, and manage user profiles.
🛒 Book Issue & Return System — Track borrowed and returned books.
💳 Payment Module — Integrated payment page for late fees or subscriptions.
📷 Image Handling — Store and display book or user images.
🔐 Authentication — Secure login and registration.
🧭 Responsive UI — Built with HTML, CSS, and Thymeleaf templates.
⚙️ Spring Boot Backend — RESTful API with service and repository layers.
🗄️ Database Integration — MySQL database for persistent storage.

# 🧰 Tech Stack
'''bash
| Category            | Technologies Used                 |
| ------------------- | --------------------------------- |
| **Frontend**        | HTML, CSS, Thymeleaf              |
| **Backend**         | Java, Spring Boot                 |
| **Database**        | MySQL                             |
| **Build Tool**      | Maven                             |
| **Version Control** | Git & GitHub                      |
| **IDE**             | Eclipse / VS Code                 |

👩‍💻 Developer

Sowmya Perla
📍 B.Tech, 4rd Year  - CSE - Data Science & Big Data Analytics

🌟 Future Enhancements
📅 Book reservation system
📊 Admin dashboard with analytics
📧 Email notifications for due dates
📱 Mobile-friendly UI
