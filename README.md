# 💬 DatingApp - Social Matching Backend

> API backend per applicazione social matching (stile Tinder) sviluppata in team Agile. 

[![Java](https://img.shields.io/badge/Java-24-007396?logo=java)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2.0-6DB33F? logo=spring)](https://spring.io/projects/spring-boot)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?logo=mysql)](https://www.mysql.com/)

## 🎯 Overview

Progetto sviluppato in **team Agile (5 developer)** con delivery **MVP in 2 settimane**.  Focus su API RESTful per matching utenti e messaggistica real-time.

## ✨ Key Features

- 🔑 **JWT Authentication** con Spring Security
- 💬 **Matching & Messaging API** con Spring Data JPA
- 🔔 **Push Notifications** via Firebase Admin SDK
- 📚 **Swagger Documentation** per API
- 👥 **Team collaboration** (Trello, GitHub, code reviews)

## 🛠️ Tech Stack

- **Java 24** + **Spring Boot 3.2.0**
- **MySQL 8.0** (database)
- **Firebase Admin SDK** (push notifications)
- **JWT** (authentication)
- **Maven** (build tool)

## 🚀 Getting Started

```bash
# Clone repository
git clone https://github.com/Byrontec2018/DatingApp.git
cd DatingApp

# Configure database (MySQL)
# Edit application.properties con le tue credenziali

# Build & Run
./mvnw clean install
./mvnw spring-boot:run
```

Backend disponibile su: `http://localhost:8080`

## 📚 API Endpoints

```http
POST   /api/auth/register          # User registration
POST   /api/auth/login             # User login
GET    /api/users/matches          # Get potential matches
POST   /api/matches/like           # Like user
POST   /api/matches/dislike        # Dislike user
GET    /api/messages/{matchId}     # Get conversation
POST   /api/messages               # Send message
```

## 🏗️ Architecture

```
Controllers (REST API)
    ↓
Services (Business Logic)
    ↓
Repositories (Spring Data JPA)
    ↓
MySQL Database
```

## 👨‍💻 Author

**Stefano D'Incà** - [GitHub](https://github.com/Byrontec2018) | [LinkedIn](https://www.linkedin.com/in/stefanodinca/)

---

⭐ Part of my portfolio - [View all projects](https://github.com/Byrontec2018)
