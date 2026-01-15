# 🍪 Spring Boot Cookie Store

A Spring Boot MVC web application for managing a fictional cookie store's inventory. The app demonstrates authentication with Spring Security, server-rendered views with Thymeleaf, and basic in-memory CRUD operations.

## ✨ Features

- **User Authentication & Authorization**
  - Secure login using Spring Security
  - Auth required for dashboard, inventory, and all cookie operations
- **Inventory Management**
  - Create, view, and edit cookie products
  - Delete endpoint available (POST /cookie/delete) — add a Delete button in the UI if desired
  - In-memory storage (data resets on app restart)
- **Dashboard & Views**
  - Simple, user-friendly pages built with Thymeleaf

## 🛠️ Technologies

- **Backend**: Java, Spring Boot, Spring Security
- **Frontend**: Thymeleaf, HTML5, CSS
- **IDE**: IntelliJ IDEA or VS Code

## 🚀 Getting Started

### Prerequisites

- Java 11 or higher
- Optional: Maven 3.6+ (if using CLI to run)

### Clone the repository

```bash
git clone https://github.com/ZainabQ26/Spring-Boot-.git
cd Spring-Boot-
```

### Run the application

**Option A: IDE**

Open the project and run the main class: `com.crumbco.cookie_store.CookieStoreApplication`

**Option B: Maven** (requires pom.xml at project root)

```bash
mvn spring-boot:run
```

### Open your browser

Navigate to:
```
http://localhost:8080
```

## 🔐 Security

Default credentials (configured in application.properties):
- **Username**: COOKIE
- **Password**: MONSTER

**Public routes**: /, /about, /contact  
**Authenticated routes**: /dashboard, /inventory, /cookie/**

**CSRF**
- Enabled by default
- Exemptions in config for /cookie/add and /cookie/edit/**
- Delete is handled at POST /cookie/delete — ensure the form includes a CSRF token or update the exemptions

## 🧱 Data Model

```
Cookies {
  id: Long,
  name: String,
  ingredients: String,
  quantityOnHand: Double,
  costPer: Double
}
```

Storage is in-memory via a service layer; no database/ORM is used.

## 💬 Contact

Zainab Qazi – [GitHub](https://github.com/ZainabQ26) – [LinkedIn](https://www.linkedin.com/in/zainab-qazi/)

Project Link: [https://github.com/ZainabQ26/Spring-Boot-](https://github.com/ZainabQ26/Spring-Boot-)
