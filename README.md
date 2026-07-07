# Notification Service 

A production-style Notification Service built using **Node.js**, **TypeScript**, and **NestJS**.

This project is being built to learn backend development by implementing real-world concepts such as authentication, asynchronous processing, caching, rate limiting, retries, scheduling, and clean architecture.

> **Project Status:** 🚧 Under Development

---

## Tech Stack

* Node.js
* TypeScript
* NestJS
* PostgreSQL
* Prisma ORM
* Redis
* JWT Authentication
* Docker
* Docker Compose
* Swagger (OpenAPI)
* Jest

---

## Project Goals

The goal of this project is to build a backend service that follows production-level development practices.

Some of the concepts I want to learn and implement are:

* REST APIs
* Authentication & Authorization
* Clean Architecture
* Database Design
* Redis Caching
* Rate Limiting
* Background Workers
* Notification Queue
* Retry Mechanism
* Scheduling
* Docker
* Unit Testing
* Integration Testing

---

## Features

### Authentication

* User Registration
* User Login
* JWT Authentication
* Refresh Tokens
* Role-Based Access Control

### Notification Templates

* Create Template
* Update Template
* Delete Template
* View Templates
* Dynamic Variables

Example:

```text
Hello {{name}}

Your order {{orderId}} has been confirmed.
```

### Notification Service

* Send Email
* Send SMS (Mock Provider)
* Multiple Notification Channels
* Priority Support

### Background Processing

* Internal Queue
* Worker Threads
* Scheduled Notifications
* Retry Failed Notifications
* Exponential Backoff

### Performance

* Redis Cache
* Rate Limiting
* Idempotency Support

### Analytics

* Notifications Sent Today
* Failed Notifications
* Delivery Rate
* Channel Statistics
* Priority Statistics

### Documentation

* Swagger API Documentation

---

## Project Structure

```text
src/
│
├── auth/
├── users/
├── notifications/
├── templates/
├── analytics/
├── audit/
├── common/
├── config/
├── cache/
├── queue/
└── main.ts
```

---

## Project Progress

* [x] Repository Created
* [ ] Project Setup
* [ ] Docker Setup
* [ ] PostgreSQL Configuration
* [ ] Prisma Setup
* [ ] Authentication
* [ ] User Module
* [ ] Notification Templates
* [ ] Notification Service
* [ ] Queue System
* [ ] Retry Mechanism
* [ ] Redis Cache
* [ ] Rate Limiting
* [ ] Scheduling
* [ ] Analytics
* [ ] Swagger Documentation
* [ ] Unit Tests
* [ ] Integration Tests
* [ ] Deployment

---

## Learning Objectives

This project is mainly focused on improving my backend development skills by learning:

* TypeScript
* NestJS
* PostgreSQL
* Prisma
* Redis
* Docker
* System Design Basics
* API Development
* Backend Best Practices

---

## Running the Project

Instructions will be added once the initial setup is completed.

---

## Future Improvements

* Push Notifications
* Real SMS Provider
* Real Email Provider
* Message Queue (Kafka/RabbitMQ)
* Prometheus Metrics
* Grafana Dashboard
* CI/CD Pipeline
* Kubernetes Deployment

---

## License

This project is created for learning and educational purposes.

---

**Thanks for visiting this repository!**

The project is currently under development, and new features will be added step by step.
