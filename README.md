# 🎓 Student Management System - Backend API

A robust RESTful API built with **Spring Boot**, **Spring Data JPA**, and **MySQL** to perform complete CRUD operations for managing student records.

---

## 🛠️ Tech Stack
* **Language:** Java 17+
* **Framework:** Spring Boot (Spring Web, Spring Data JPA)
* **Database:** MySQL
* **Build Tool:** Maven
* **Testing Tool:** Thunder Client / Postman

---

## 🚀 Features
* **Create Student:** Register new students with details (Name, Email, Course).
* **Get All Students:** Retrieve a complete list of registered students.
* **Get Student by ID:** Fetch a single student record using their unique ID.
* **Update Student:** Update existing student details.
* **Delete Student:** Remove student records from the database.

---

## 📡 REST API Endpoints

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `POST` | `/api/students` | Create a new student record |
| `GET` | `/api/students` | Fetch all student records |
| `GET` | `/api/students/{id}` | Fetch student details by ID |
| `PUT` | `/api/students/{id}` | Update existing student record |
| `DELETE` | `/api/students/{id}` | Delete student record by ID |

### Sample Request Body (`POST` / `PUT`):
```json
{
  "name": "Chhavi Tyagi",
  "email": "chhavi@example.com",
  "course": "BCA"
}