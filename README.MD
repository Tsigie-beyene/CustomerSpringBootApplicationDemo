Spring Boot Test Application 

This is a Spring Boot REST API secured with JWT authentication, using Spring Data JPA and MySQL.

 Features

User & Customer management

JWT-based authentication and authorization

Secure password handling

JPA/Hibernate for database interaction

Entities
Users

id (Auto-generated)

email (Unique, Not Null)

name (Not Null)

Customers

id (Auto-generated)

username (Unique, Not Null)

password (Encrypted)

Security (JWT)

Customers authenticate using username & password

On successful login, a JWT token is generated

Protected endpoints require:

Authorization: Bearer <JWT_TOKEN>

🛠 Tech Stack

Java 21

Spring Boot

Spring Security

JWT

Spring Data JPA

MySQL

Lombok

▶️ Run the Application
mvn spring-boot:run


Application runs on:

http://localhost:8080



Passwords should be stored using BCrypt

JWT filters protect secured endpoints

Entities are auto-created using JPA

If you want, I can also:

Add API endpoints section

Add JWT flow diagram

Make it production-ready README

Just tell me 👍
