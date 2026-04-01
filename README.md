# 🚀 Authify

Authify is a **full-stack web application** designed for secure user management with **JWT-based authentication** and complete **CRUD operations**. It demonstrates seamless integration between a **React frontend** and a **Spring Boot backend**, following industry-standard architecture and best practices.

The backend is built using **Spring Boot**, **Spring Security**, **Spring Data JPA**, and **Hibernate**, ensuring secure API access, efficient database interaction, and scalable design. The frontend is developed using **React**, providing a dynamic and responsive user interface for managing users.

Authify implements **stateless authentication using JWT (JSON Web Tokens)**, enabling secure communication between client and server without maintaining server-side sessions.

---

# 🔐 Key Features

### 🧑‍💻 User Management

* Create new users
* View all users
* Update user details
* Delete users

### 🔒 Authentication & Security

* JWT-based authentication
* Secure login system
* Password encryption using Spring Security
* Stateless session management
* Protected REST APIs

### 🌐 Frontend (React)

* Dynamic UI using React
* API integration using Axios
* Form handling for user creation & updates
* Component-based architecture

### ⚙️ Backend (Spring Boot)

* RESTful API design
* Layered architecture (Controller → Service → Repository)
* Global exception handling
* Logging support (SLF4J)

### 🗄️ Database

* MySQL integration
* ORM using Hibernate
* Automatic table creation with JPA

---

# 🛠️ Tech Stack

### Frontend

* React
* Axios
* JavaScript (ES6+)

### Backend

* Spring Boot
* Spring Security
* Spring Data JPA
* Hibernate

### Authentication

* JWT (JSON Web Token)

### Database

* MySQL

---

# 📁 Project Structure

## Backend (Spring Boot)

* Controller Layer – Handles HTTP requests
* Service Layer – Business logic
* Repository Layer – Database interaction
* Entity Layer – JPA entities

## Frontend (React)

* Components – UI elements
* Services – API calls
* Pages – Main screens

---

# 🔄 API Flow

```text
React (Frontend) → Axios → Spring Boot (Backend) → JPA/Hibernate → MySQL
```

---

# 🚀 How to Run

### 1️⃣ Backend (Spring Boot)

* Configure `application.properties`
* Run the main class

```bash
mvn spring-boot:run
```

---

### 2️⃣ Frontend (React)

```bash
npm install
npm start
```

---

# 🔐 Authentication Flow

1. User logs in with credentials
2. Server validates and generates JWT token
3. Token is sent to frontend
4. Frontend stores token (localStorage/sessionStorage)
5. Token is sent in Authorization header for protected APIs

---

# 📌 Future Enhancements

* Role-based authorization (Admin/User)
* Refresh token mechanism
* UI improvements (Material UI / Bootstrap)
* Pagination & search optimization
* Docker deployment

---

# 💡 Learning Outcomes

* Full-stack development (React + Spring Boot)
* REST API design
* JWT authentication & security
* Database integration using JPA/Hibernate
* Clean architecture & best practices

---

# 👨‍💻 Author

**Sadguru Thakur**

---

# ⭐ If you like this project

Give it a ⭐ on GitHub!
