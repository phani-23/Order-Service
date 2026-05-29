# 🚀 Order Service

Order Service is a microservice-based backend application developed using Spring Boot.  
It handles customer orders and communicates with the Restaurant Service using OpenFeign.

---

## 📌 Features

- Create and manage customer orders
- Fetch restaurant details from Restaurant Service
- RESTful APIs
- OpenFeign integration
- Exception handling
- MySQL database integration

---

## 🛠️ Tech Stack

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- OpenFeign
- MySQL
- Maven

---

## 📂 Project Structure

src/main/java
│
├── controller
├── service
├── repository
├── entity
├── dto
├── feign
└── exception

---

## 📦 Maven Dependency

```xml
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-openfeign</artifactId>
</dependency>
