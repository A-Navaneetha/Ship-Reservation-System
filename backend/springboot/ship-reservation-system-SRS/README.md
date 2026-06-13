# 🚢 Ship Reservation System Backend

A robust backend application for the **Ship Reservation System** built using **Spring Boot**. This RESTful API handles user authentication, ship management, reservation processing, and database operations for the Ship Reservation System.

# 🌟 Features

* 🔐 User Authentication and Authorization
* 🚢 Ship Management
* 📅 Ship Schedule Management
* 🎫 Ticket Reservation and Booking
* 📋 Reservation Details Retrieval
* ❌ Reservation Cancellation
* 🗄️ Database Integration with MySQL
* 🌐 RESTful API Architecture
* ⚡ High Performance with Spring Boot

## 🛠️ Tech Stack

* Java
* Spring Boot
* Spring Data JPA
* Spring Web
* MySQL
* Maven
* Hibernate

## 📂 Project Structure

```text
backend
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── shipreservation
│   │   │           │
│   │   │           ├── controller
│   │   │           ├── service
│   │   │           ├── repository
│   │   │           ├── entity
│   │   │           ├── dto
│   │   │           ├── config
│   │   │           ├── exception
│   │   │           └── ShipReservationApplication.java
│   │   └── resources
│   │       │
│   │       ├── application.properties
│   │       ├── static
│   │       └── templates
│   └── test
│       └── java
├── target
├── .mvn
├── mvnw
├── mvnw.cmd
├── pom.xml
├── .gitignore
└── README.md
```

### Prerequisites

* Java 17 (or your project version)
* Maven
* MySQL Server

## 🔗 API Endpoints

### Authentication

* POST `/api/auth/register`
* POST `/api/auth/login`

### Ship Management

* GET `/api/ships`
* GET `/api/ships/{id}`
* POST `/api/ships`
* PUT `/api/ships/{id}`
* DELETE `/api/ships/{id}`

### Reservation Management

* POST `/api/reservations`
* GET `/api/reservations`
* GET `/api/reservations/{id}`
* DELETE `/api/reservations/{id}`

> Update the endpoints above according to your actual API structure.

## 🔗 Frontend Application

This backend API is consumed by the Ship Reservation System frontend developed using React.js.
Ensure the frontend application is running and configured with the correct backend API URL before using the system.

## 🗄️ Database

The application uses **MySQL** as the primary database for storing:

* User Information
* Ship Details
* Reservation Records
* Schedule Information

## 🎓 Learning Outcomes

Through the development of this Ship Reservation System Backend, the following concepts and skills were learned and applied:

- ☕ Developed RESTful APIs using Spring Boot.
- 🗄️ Implemented database operations using Spring Data JPA and MySQL.
- 🔄 Performed CRUD (Create, Read, Update, Delete) operations efficiently.
- 🏗️ Applied layered architecture using Controller, Service, and Repository patterns.
- 📡 Integrated frontend and backend through REST API communication.
- 🔐 Gained experience in handling user authentication and authorization concepts.
- 🧩 Designed and managed entity relationships and database schemas.
- ⚙️ Configured application properties and environment settings.
- 🐞 Debugged and tested API endpoints using tools like Postman.
- 🚀 Learned backend deployment and version control using Git and GitHub.
- 📚 Improved understanding of enterprise-level Java application development.
  
## 🎯 Future Enhancements

* JWT Authentication
* Role-Based Access Control
* Online Payment Integration
* Email Notifications
* API Documentation with Swagger
* Docker Deployment
