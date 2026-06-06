# Online Banking System - Microservices Architecture

## Overview

Online Banking System is a scalable banking platform built using Spring Boot Microservices. The application enables customers to securely manage bank accounts, perform transactions, and access banking services through a modern web interface.

The project follows a microservices architecture where each service owns its business logic and database, making the system highly scalable, maintainable, and production-ready.

---

## Features

### Customer Module

* Customer Registration
* Secure Login & Authentication
* View Account Details
* Check Account Balance
* Fund Transfer
* View Transaction History
* Profile Management

### Bank Employee Module

* Customer Verification
* Account Creation
* View Customer Information
* Account Management

### Admin Module

* User Management
* Employee Management
* Freeze/Unfreeze Accounts
* System Monitoring
* Reports & Analytics

---

## Microservices

### Auth Service

Responsible for:

* User Registration
* Authentication
* Authorization
* JWT Token Generation
* Role Management

### Account Service

Responsible for:

* Account Creation
* Account Information
* Balance Management

### Transaction Service

Responsible for:

* Deposits
* Withdrawals
* Fund Transfers
* Transaction History

### API Gateway

Responsible for:

* Request Routing
* Centralized Entry Point
* Security Enforcement

### Service Registry

Responsible for:

* Service Discovery
* Dynamic Registration
* Health Monitoring

---

## Technology Stack

### Backend

* Java 21
* Spring Boot
* Spring Security
* Spring Data JPA
* Hibernate
* JWT Authentication
* Maven

### Database

* MySQL

### Microservices

* Eureka Server
* Spring Cloud Gateway
* OpenFeign

### DevOps

* Docker
* Docker Compose

### Frontend

* React JS

---

## Project Structure

online-banking-system-microservices

├── auth-service

├── account-service

├── transaction-service

├── api-gateway

├── service-registry

├── frontend

└── docs

---

## Security Features

* JWT Authentication
* Password Encryption using BCrypt
* Role-Based Access Control (RBAC)
* Secure API Access
* Authentication & Authorization Filters

---

## Future Enhancements

* Loan Management System
* Credit Card Services
* Notification Service
* Email & SMS Integration
* Audit Logging
* Kafka Event Streaming
* Kubernetes Deployment
* CI/CD Pipeline Integration

---

## Learning Objectives

This project demonstrates:

* Microservices Architecture
* RESTful API Development
* Spring Security & JWT
* Database Design
* Service Discovery
* API Gateway Pattern
* Docker Containerization
* Production-Oriented Backend Development

---

## Author

Sandip Ugile

Final Year B.Tech (Information Technology)

Java | Spring Boot | React | Microservices | MySQL
