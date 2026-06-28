# 💳 Family Cash Card API

A RESTful API built with **Spring Boot** as part of the **Spring Academy - Spring Boot Beginner Course**. This project simulates a Family Cash Card system that allows parents to securely manage digital allowance cards for their children.

The project follows modern backend development practices, including **Test-Driven Development (TDD)**, RESTful API design, database integration, and application security.

---

## 📖 About

The Family Cash Card API is a cloud-based application that enables parents to create, manage, and track virtual cash cards instead of handing out physical cash.

Throughout this project, the application evolves from a simple API into a fully functional backend that supports CRUD operations, persistent storage, authentication, authorization, and automated testing.

---

## 🎯 Objectives

This project is designed to build a strong foundation in Spring Boot by learning how to:

- Build RESTful APIs
- Develop applications using Spring Boot
- Connect applications to relational databases
- Apply Test-Driven Development (TDD)
- Secure APIs using Spring Security
- Follow real-world software development practices

---

## ✨ Features

- ✅ Create Cash Cards
- ✅ View Individual Cash Cards
- ✅ View Multiple Cash Cards
- ✅ Update Cash Cards
- ✅ Delete Cash Cards
- ✅ Database Persistence
- ✅ RESTful API
- ✅ Pagination
- ✅ Authentication & Authorization
- ✅ Unit Testing
- ✅ Integration Testing

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Java | Programming Language |
| Spring Boot | Application Framework |
| Spring Web | REST API Development |
| Spring Data JDBC | Database Access |
| Spring Security | Authentication & Authorization |
| H2 Database | Development Database |
| Maven | Dependency Management |
| JUnit 5 | Unit Testing |
| MockMvc | Integration Testing |

---

## 📚 Concepts Learned

- Spring Boot Fundamentals
- Dependency Injection (IoC)
- REST API Design
- CRUD Operations
- Repository Pattern
- Spring Data JDBC
- HTTP Methods & Status Codes
- Validation
- Pagination
- Test-Driven Development
- Spring Security
- Authentication
- Authorization
- Clean Code Principles

---

## 🧪 Development Approach

### Test-Driven Development (TDD)

This project follows the Red → Green → Refactor cycle:

1. Write a failing test
2. Implement the functionality
3. Refactor while keeping all tests passing

---

### Steel Thread Development

The application is built using the **Steel Thread** approach by integrating the three core components early:

- REST API
- Database
- Security

This enables incremental development while reducing integration risks.

---

## 📁 Project Structure

```

src
├── main
│   ├── java
│   │   └── example
│   │       ├── controller
│   │       ├── model
│   │       ├── repository
│   │       ├── service
│   │       ├── security
│   │       └── CashCardApplication.java
│   │
│   └── resources
│       ├── application.properties
│       └── schema.sql
│
└── test
└── java

````

---

## 📡 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/cashcards/{id}` | Retrieve a cash card |
| GET | `/cashcards` | Retrieve all cash cards |
| POST | `/cashcards` | Create a new cash card |
| PUT | `/cashcards/{id}` | Update a cash card |
| DELETE | `/cashcards/{id}` | Delete a cash card |

> More endpoints and features are added throughout the course.

---

## 🚀 Getting Started

### Prerequisites

- Java 21+
- Maven
- Git

### Clone the Repository

```bash
git clone https://github.com/your-username/family-cash-card-api.git
````

### Navigate to the Project

```bash
cd family-cash-card-api
```

### Run the Application

Using Maven Wrapper:

```bash
./mvnw spring-boot:run
```

Or using Maven:

```bash
mvn spring-boot:run
```

---

## 🧪 Running Tests

```bash
./mvnw test
```

or

```bash
mvn test
```

---

## 🎓 What This Project Demonstrates

* Backend Development with Spring Boot
* REST API Design
* Spring Data JDBC
* Spring Security
* Test-Driven Development
* Dependency Injection
* Software Testing
* Database Integration
* Clean Architecture

---

## 📈 Learning Journey

This repository documents my journey learning **Spring Boot** through hands-on, project-based development. Rather than focusing only on theory, each lesson introduces a practical feature commonly encountered in real-world backend development.

As I progress through the course, this project will continue to grow with new features, improved architecture, and more advanced Spring concepts.

---

## 📌 Project Status

🚧 **In Progress**

The project is actively being developed as I progress through the Spring Academy course.

---

## 🤝 Acknowledgements

This project is based on the **Spring Academy - Spring Boot Beginner Course**, which teaches Spring Boot by guiding learners through building a production-style RESTful API using modern Java development practices.

---

## 📄 License

This project is intended for educational purposes.

```
```
