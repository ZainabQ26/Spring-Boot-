# 🍪 Cookie Store Web Application

A full-stack e-commerce web application for managing a fictional cookie store inventory. Built with Spring Boot and Java, this project demonstrates modern web development practices including user authentication, CRUD operations, and responsive UI design.

## 🎓 Course Project
Developed as part of my Computer Science coursework at Penn State University-Harrisburg to demonstrate proficiency in:
- Backend web development
- Database management
- Security implementation
- MVC architecture

## ✨ Features

- **User Authentication & Authorization**
  - Secure login system using Spring Security
  - Password encryption
  - Session management

- **Inventory Management**
  - Create, Read, Update, Delete (CRUD) operations for cookie products
  - Real-time inventory tracking
  - Product categorization

- **Interactive Dashboard**
  - User-friendly interface for managing cookie inventory
  - Analytics and statistics display
  - Responsive design for mobile and desktop

- **Database Integration**
  - Persistent data storage
  - Efficient query optimization
  - Data validation

## 🛠️ Technologies Used

- **Backend:** Java, Spring Boot, Spring Security
- **Frontend:** Thymeleaf, HTML5, CSS3
- **Database:** [Specify your database - e.g., H2, MySQL, PostgreSQL]
- **Build Tool:** Maven
- **IDE:** IntelliJ IDEA / VS Code

## 🚀 Getting Started

### Prerequisites
- Java 11 or higher
- Maven 3.6+
- [Your database if applicable]

### Installation

1. Clone the repository
```bash
git clone https://github.com/zozo080212/Spring-Boot-.git
cd Spring-Boot-
```

2. Build the project
```bash
mvn clean install
```

3. Run the application
```bash
mvn spring-boot:run
```

4. Open your browser and navigate to:
```
http://localhost:8080
```

## 📚 Project Structure

```
Spring-Boot-/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/crumbco/cookiestore/
│   │   │       ├── config/          # Security configuration
│   │   │       ├── controller/      # Request handlers
│   │   │       ├── model/           # Data models
│   │   │       └── service/         # Business logic
│   │   └── resources/
│   │       ├── templates/       # Thymeleaf HTML templates
│   │       └── application.properties
└── pom.xml                  # Maven dependencies
```

## 💻 Key Learning Outcomes

- Implemented **MVC (Model-View-Controller)** architecture
- Developed **RESTful** API endpoints
- Applied **Spring Security** for authentication and authorization
- Practiced **database design** and ORM with Spring Data
- Created **responsive web interfaces** with Thymeleaf
- Utilized **dependency injection** and IoC principles

## 🔐 Security Features

- Password hashing with BCrypt
- CSRF protection
- SQL injection prevention
- Session timeout management

## 📸 Screenshots

*Add screenshots of your application here to showcase the UI*

## 🚀 Future Enhancements

- [ ] Add shopping cart functionality
- [ ] Implement payment gateway integration
- [ ] Add product image uploads
- [ ] Create admin dashboard
- [ ] Add email notifications
- [ ] Implement search and filtering

## 📝 License

This project was created for educational purposes as part of coursework at Penn State University.

## 💬 Contact

**Zainab Qazi**
- GitHub: [@zozo080212](https://github.com/zozo080212)
- LinkedIn: [linkedin.com/in/zainab--qazi](https://www.linkedin.com/in/zainab--qazi/)
- Email: zainabqazi1712@gmail.com

---

*Built with ❤️ as part of my journey in full-stack web development*
