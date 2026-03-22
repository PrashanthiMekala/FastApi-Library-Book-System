# 📚 FastAPI Library Book System

## 🚀 Project Overview

This project is a **Library Book Management System** built using FastAPI.
It allows users to manage books, users, and borrowing activities through REST APIs.

---

## 🎯 Features

* 📌 User Management (Create, View, Update, Delete)
* 📌 Book Management (Add, View, Update, Delete)
* 📌 Borrow & Return Books (Workflow)
* 📌 Search Books
* 📌 Pagination Support
* 📌 API Testing with Swagger UI

---

## 🛠️ Tech Stack

* Python
* FastAPI
* Uvicorn
* Pydantic

---

## 📂 Project Structure

```
FastApi-Library-Book-System/
│── main.py
│── models.py
│── database.py
│── utils.py
│── Screenshots/
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```
git clone https://github.com/your-username/FastApi-Library-Book-System.git
cd FastApi-Library-Book-System
```

### 2. Install Dependencies

```
pip install fastapi uvicorn
```

### 3. Run Server

```
uvicorn main:app --reload
```

---

## 🌐 API Documentation

Open in browser:

```
http://127.0.0.1:8000/docs
```

👉 Use Swagger UI to test all APIs.

---

## 🔁 API Endpoints

### 👤 Users

* POST /users → Create user
* GET /users → Get all users
* PUT /users/{id} → Update user
* DELETE /users/{id} → Delete user

---

### 📚 Books

* POST /books → Add book
* GET /books → Get books (search & pagination)
* PUT /books/{id} → Update book
* DELETE /books/{id} → Delete book

---

### 🔄 Borrow System

* POST /borrow → Borrow book
* GET /borrow → View borrowed books
* DELETE /borrow → Return book

---

## 🔍 Search & Pagination

Example:

```
/books?search=python&page=1&limit=5
```

---

## 📸 Screenshots

Add your screenshots here:

```
Screenshots/swagger-ui.png
Screenshots/create-book.png
Screenshots/borrow-book.png
```

---

## 🎯 Learning Outcomes

* Built REST APIs using FastAPI
* Implemented CRUD operations
* Used Pydantic for validation
* Designed backend workflow (borrow system)
* Practiced API testing using Swagger

---

## 📌 Conclusion

This project demonstrates a complete backend system for managing a library using FastAPI with real-world API features.

---

## 🔗 Author

Your Name

GitHub: https://github.com/your-username





