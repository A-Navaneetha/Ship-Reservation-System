# 🚢 Ship Reservation System Backend

A robust backend application for the **Ship Reservation System** built using **Spring Boot**. This RESTful API handles user authentication, ship management, reservation processing, and database operations for the Ship Reservation System.

## 🌟 Features

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
src/
├── main/
│   ├── java/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── repository/
│   │   ├── model/
│   │   └── ShipReservationApplication.java
│   └── resources/
│       ├── application.properties
│       └── static/
└── test/
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

## 🗄️ Database

The application uses **MySQL** as the primary database for storing:

* User Information
* Ship Details
* Reservation Records
* Schedule Information

## 🎯 Future Enhancements

* JWT Authentication
* Role-Based Access Control
* Online Payment Integration
* Email Notifications
* API Documentation with Swagger
* Docker Deployment

