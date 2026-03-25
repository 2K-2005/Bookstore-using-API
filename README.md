# 📚 RESTful Bookstore Management System

A backend-focused REST API application developed using Spring Boot that manages bookstore operations such as creating, retrieving, updating, and deleting book records. This project demonstrates core backend development concepts including API design, database integration, and application structuring.

---

## 🚀 Tech Stack

- ☕ Java – Core programming and business logic  
- 🌱 Spring Boot – Framework for building RESTful APIs  
- 🛢️ MySQL – Relational database for persistent storage  
- 🧪 Postman – API testing and validation  

---

## 📌 Features

- 📖 Add new books to the system  
- 🔍 Retrieve book details  
- ✏️ Update existing book information  
- ❌ Delete book records  
- 🔄 Full CRUD operations via REST APIs  
- 🗄️ MySQL database integration  

---

## 🏗️ Architecture

The application follows the **MVC (Model-View-Controller)** architecture:

- **Controller** – Handles incoming HTTP requests  
- **Service** – Contains business logic  
- **Repository** – Manages database interactions  

---

## 📡 API Endpoints (Sample)

| Method | Endpoint       | Description           |
|--------|----------------|-----------------------|
| GET    | /home          | Get all books         |
| GET    | /sel/{id}      | Get book by ID        |
| POST   | /abc           | Add a new book        |
| PUT    | /edit/{id}     | Update book details   |
| DELETE | /del/{id}      | Delete a book         |

---

## ⚙️ How to Run the Project

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
