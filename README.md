# 🚀 Spring Boot Student Management API

A simple **Spring Boot REST API** for managing student data using **MySQL + JPA (Hibernate)**.

---

## 📌 Features

* Add new students
* View all students
* REST API structure
* MySQL database integration
* Layered architecture (Controller → Service → Repository)

---

## 🛠️ Tech Stack

* Java
* Spring Boot
* Spring Data JPA (Hibernate)
* MySQL
* Maven

---

## 📂 Project Structure

```
com.example.demo
│
├── controller        # REST APIs
├── service           # Business logic
├── repository        # Database interaction
├── model             # Entity classes
└── DemoApplication   # Main class
```

---

## ⚙️ Configuration

### application.properties

```
spring.datasource.url=jdbc:mysql://localhost:3306/spring_hibernate_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

server.port=8081
```

---

## 🗄️ Database Setup

1. Start MySQL server
2. Create database:

```
CREATE DATABASE spring_hibernate_db;
```

---

## ▶️ Run the Project

### Using Eclipse / IDE

* Right click → Run As → Spring Boot App

### Using terminal

```
mvn spring-boot:run
```

---

## 🌐 API Endpoints

### ➤ Get All Students

```
GET http://localhost:8081/api/students
```

### ➤ Add Student

```
POST http://localhost:8081/api/students
```

#### Request Body (JSON)

```
{
  "name": "Arya",
  "age": 21
}
```

---

## 🧪 Testing

Use tools like:

* Thunder Client (VS Code)
* Postman

---

## ⚠️ Notes

* Ensure MySQL is running
* Check correct port (8081)
* Database must exist before running

---

## 📈 Future Improvements

* Add JWT Authentication 🔐
* Validation & Exception Handling
* Update/Delete APIs
* Swagger Documentation

---<img width="1919" height="1078" alt="Screenshot 2026-04-06 123630" src="https://github.com/user-attachments/assets/32a71044-4830-42da-bbf8-0f4a007638ae" />

<img width="1919" height="1079" alt="Screenshot 2026-04-06 123545" src="https://github.com/user-attachments/assets/551653fb-3a1d-4c12-8fc1-c925341bd7cd" />

<img width="1919" height="1079" alt="Screenshot 2026-04-06 123539" src="https://github.com/user-attachments/assets/bd514145-a36f-423d-9ea1-74d1b386f01f" />

## 👨‍💻 Author

Arya Bhat

