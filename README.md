# 🔐 Spring Boot JWT Authentication API

This is a secure REST API built with **Spring Boot**, featuring **JWT-based authentication**, **role-based authorization**, and **user registration/login** functionalities. This project follows best practices for stateless authentication using JSON Web Tokens (JWT) and Spring Security.

## 📚 Based on a Tutorial

This project was created by following the [JWT Authentication & Authorization Tutorial (2023)](https://www.youtube.com/watch?v=KxqlJblhzfI) by [Amigoscode](https://www.youtube.com/@amigoscode).  
All core logic and flow are based on the concepts explained in that tutorial. This repo is for educational purposes and personal experimentation.

## 🧰 Features

- ✅ User Registration (`/api/v1/auth/register`)
- ✅ User Authentication (`/api/v1/auth/authentication`)
- ✅ JWT generation & validation
- ✅ Spring Security integration
- ✅ Password hashing with `BCryptPasswordEncoder`
- ✅ Role-based access control (e.g., USER, ADMIN)

## 🛠 Tech Stack

- Java 17+
- Spring Boot 3.x
- Spring Security
- Spring Data JPA
- H2 / PostgreSQL / MySQL (your choice)
- JWT (JSON Web Tokens)

## 🚀 Getting Started

### Prerequisites

- Java 17+
- Maven
- IDE (IntelliJ, VS Code, etc.)
