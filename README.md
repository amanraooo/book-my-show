# 🎬 BookMyShow - Movie Ticket Booking Backend

A backend system inspired by BookMyShow, built using Spring Boot.  
This project allows users to browse movies, view shows, select seats, and book tickets with simulated payment functionality.

---

## 🚀 Features

- 🔐 User Authentication (JWT Based)
- 🎥 Add / View Movies
- 🕒 Show Management
- 💺 Seat Selection with Availability Check
- 💳 Simulated Payment Workflow
- 📄 Booking History
- 👨‍💼 Admin Role Management
- 📊 RESTful APIs

---

## 🛠 Tech Stack

- Java
- Spring Boot
- Spring Security
- JWT Authentication
- JPA / Hibernate
- MySQL
- Maven

---

## 📌 API Endpoints

### 🔐 Authentication
- `POST /auth/register`
- `POST /auth/login`

### 🎥 Movies
- `GET /movies`
- `POST /admin/movies`

### 🎟 Booking
- `POST /book`
- `GET /my-bookings`

---

## 🏗 Project Structure

```
src
 ├── controller
 ├── service
 ├── repository
 ├── model
 └── config
```

---

## 💡 How to Run

1. Clone the repository  
2. Configure MySQL in `application.properties`
3. Run using:
```
mvn spring-boot:run
```

---

## 📈 Future Improvements

- Real Payment Gateway Integration
- Frontend Integration (React)
- Docker Deployment
- Email Confirmation Service

---

## 👨‍💻 Author

Aman Kumar  
Backend Developer | Spring Boot Enthusiast
