# JWT Authentication System

A Spring Boot application for secure user authentication using JWT (JSON Web Token).

---

##  Features

- User Registration
- User Login
- JWT Token Generation
- Secure API Access
- Role-based Authorization (User / Admin)
- Password Encryption using BCrypt

---

##  Tech Stack

- Java
- Spring Boot
- Spring Security
- JWT
- postgreSQL

---

##  Authentication Flow

1. User registers
2. User logs in using OTP
3. JWT token is generated
4. Token is used to access secured APIs

---
##  Run Project

mvn spring-boot:run

---
##  Public APIs

| API | Method | Description |
|-----|--------|------------|
| /userReg/createUser | POST | Register new user |
| /userlogin/send?email=email@gmail.com | POST | Send OTP  |
| /userlogin/verify-otp?email=email@gmail.com&otp=995412 | POST | OTP verification and get JWT token |

---
