# RevWorkForce – Human Resource Management System (HRM)

RevWorkForce is a full-stack Human Resource Management (HRM) web application designed to automate and streamline HR operations within an organization. The system provides a centralized platform for managing employee records, leave applications, and performance reviews while ensuring secure role-based access for employees, managers, and administrators.

---

## 🚀 Project Overview

Many organizations still manage HR processes manually or across multiple systems. RevWorkForce solves this problem by providing a unified platform that improves efficiency, transparency, and data management.

The application enables HR teams to manage workforce operations while allowing employees to access their information, request leaves, and track performance through a simple and intuitive interface.

---

## 🛠️ Technology Stack

**Backend**

* Java 21
* Spring Boot
* Spring Data JPA
* Spring Security
* REST APIs

**Frontend**

* HTML
* CSS
* JavaScript
* Thymeleaf

**Database**

* Oracle Database

**Build Tool**

* Maven (Maven Wrapper included)

**Testing Tools**

* Postman (for API testing)

---

## 📂 Project Structure

```
src/main/java/com/rev/app
│
├── controller        → Web controllers (Thymeleaf views)
├── rest              → REST API controllers
├── service           → Business logic layer
├── repository        → Data access layer
├── entity            → JPA entity classes
│
src/main/resources
│
├── templates         → HTML views
├── static            → CSS, JavaScript, images
├── application.properties
└── schema.sql
```

---

## ⚙️ Prerequisites

Before running the project, ensure the following software is installed:

* **Java JDK 21**
* **Oracle Database**
* **Git**
* **Postman** (optional for API testing)

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Priya03333/RevWorkForce.git
cd RevWorkForce
```

---

### 2. Configure Database

Open:

```
src/main/resources/application.properties
```

Update the Oracle database credentials:

```
spring.datasource.url=jdbc:oracle:thin:@localhost:1521:XEPDB1
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
```

---

### 3. Initialize Database Schema

Run the SQL script:

```
src/main/resources/schema.sql
```

This will create the required tables for employees, leaves, and performance management.

---

### 4. Run the Application

From the project root directory run:

```bash
./mvnw spring-boot:run
```

---

## 🌐 Access the Application

After starting the server:

**Application URL**

```
http://localhost:8081
```

**REST API Base URL**

```
http://localhost:8081/api
```

You can test API endpoints using **Postman**.

---

## 🔑 Key Features

* Employee Management
* Leave Request and Approval Workflow
* Performance Review System
* Role-Based Access (Admin / Manager / Employee)
* REST API Support
* Responsive User Interface
* Secure Authentication and Authorization

---

## 👨‍💻 My Role in the Project

* Developed backend services using **Java and Spring Boot**
* Designed and implemented **REST APIs for HR operations**
* Integrated **Oracle Database using Spring Data JPA**
* Built dynamic frontend pages using **Thymeleaf, HTML, CSS, and JavaScript**
* Implemented **authentication and role-based authorization using Spring Security**
* Structured the project using **MVC architecture**
* Managed **database schema design and data relationships**
* Used **Git for version control and collaboration**

---

## 🎯 Future Enhancements

* Email notification system for leave approvals
* Employee attendance tracking
* Payroll management module
* Mobile-friendly UI improvements
* Advanced analytics dashboard

---

## 📌 Author

**Poodur Shanthi Priya**

Junior Architect / Database Administrator
Skilled in **Java, SQL, Spring Boot, and Full-Stack Development**
