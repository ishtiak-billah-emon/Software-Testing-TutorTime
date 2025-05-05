# 📬 Tutor Time API Testing – Postman Collection

This repository contains a fully tested Postman collection for a **TUTOR TIME-ONLINE LANGUAGE & TUTOR BOOKING PLATFORM**, designed to manage users, tutorials and bookings. The API is suitable for platforms that offer language learning services through registered tutors.

---

## 🔍 Project Overview

This Postman collection covers three core functionalities:

### 📁 Folder 1: Users

- `GET /users` – Fetch all users
- `POST /users` – Create a new user
- `PATCH /users` – Update last login

### 📁 Folder 2: Tutorials

- `GET /tutorials` – Retrieve all tutorials
- `GET /tutorials?category=language` – Filter tutorials by language
- `GET /tutorials/:id` – Retrieve a specific tutorial by ID
- `GET /myTutorials/:email` – Get tutorials posted by a specific tutor
- `POST /tutorials` – Add a new tutorial
- `PUT /updateTutorial/:id` – Update tutorial information
- `DELETE /tutorials/:id` – Delete a tutorial

### 📁 Folder 3: Booked Tutorials

- `POST /bookedTutorial` – Book a tutorial
- `GET /bookedTutorial` – Get all bookings
- `GET /bookedTutorial/:email` – Get bookings by user email

---

## 📂 Repository Contents

- ✅ **Postman Collection JSON** – Fully tested and export-ready
- ✅ **Organized folders** – Separated by functionality for clarity
- ✅ **Request examples** – With headers, body, and response verification

---

## 🛠 Technologies Used

- [Postman](https://www.postman.com/) – API testing and management
- RESTful API design pattern
- JSON for request/response structure

---

## 👨‍💻 Author

**Ishtiak Billah Emon**

---
