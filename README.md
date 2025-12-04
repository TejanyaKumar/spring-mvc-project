# Spring MVC Project (Spring Boot + Thymeleaf)

This is a beginner-friendly **Spring Boot MVC** application built to understand how controllers, views, forms, and data flow work in Spring MVC using **Thymeleaf**.

---

## 🚀 Technologies Used
- Java 17
- Spring Boot
- Spring MVC
- Thymeleaf
- Maven
- Git & GitHub

---

## ✅ Features
- Basic controller to view mapping
- Dynamic data rendering using Thymeleaf
- Form handling using:
  - `@RequestParam`
  - `@ModelAttribute`
- Passing data using `Model`
- Displaying a list of users in a table
- Multiple endpoints demonstration

---

## 📂 Project Structure

SpringMVCProject
├── src/main/java
│ └── com/flm
│ ├── controller
│ │ ├── UserController.java
│ │ └── WelcomeController.java
│ ├── model
│ │ └── User.java
│ └── SpringMvcProjectApplication.java
│
├── src/main/resources
│ ├── templates
│ │ ├── hi.html
│ │ ├── home.html
│ │ ├── success.html
│ │ └── users.html
│ └── application.properties
│
└── pom.xml

---

## 🌐 Available Endpoints
| URL | Method | Description |
|----|--------|------------|
| `/hi` | GET | Simple welcome page |
| `/home` | GET | Home page with form |
| `/submit` | POST | Form submission using `@RequestParam` |
| `/submitObject` | POST | Form submission using `@ModelAttribute` |
| `/users` | GET | Displays list of users |

---

## 🧪 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/TejanyaKumar/spring-mvc-project.git
Open the project in STS / Eclipse

Run:

Copy code
SpringMvcProjectApplication.java
Open browser and visit:

bash
Copy code
http://localhost:8080/home
📘 What I Learned from This Project
Spring MVC request flow

Difference between @Controller and @RestController

Using Model, @RequestParam, and @ModelAttribute

Thymeleaf syntax (th:text, th:each, th:field)

Basic Git & GitHub workflow

⚠️ Note
This project is created for learning and practice purposes.
Passwords are displayed only for demonstration and should never be handled this way in real applications.

👤 Author
Tejanya Kumar

GitHub: https://github.com/TejanyaKumar
