# 🚀 Full Stack Task Management Application

A complete **Full Stack Web Application** built using **React, Node.js, Express, and MongoDB**.
This project allows users to register, authenticate securely, and manage their tasks with full CRUD functionality.

---

## 📌 Project Overview

The main objective of this project is to build a scalable full stack application where:

* Users can create accounts and log in securely
* Tasks can be created, updated, deleted, and viewed
* Each task is associated with a specific user
* Frontend and backend communicate via REST APIs

---

## ✨ Features

### 🔐 Authentication

* User Registration
* User Login
* JWT-based Authentication
* Protected Routes

### 📋 Task Management

* Create Task
* View Tasks
* Update Task
* Delete Task

### ⚙️ Additional Features

* Pagination & Filtering
* Data Validation
* Error Handling
* Secure API Communication

---

## 🛠️ Tech Stack

### 🔹 Frontend

* React.js
* Context API
* Axios

### 🔹 Backend

* Node.js
* Express.js

### 🔹 Database

* MongoDB
* Mongoose

### 🔹 Authentication

* JSON Web Token (JWT)
* bcrypt

---

## 📂 Project Structure

```
task-manager-api/
│
├── backend/
│   ├── src/
│   │   ├── models/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── config/
│   │
│   ├── server.js
│   └── package.json
│
├── frontend/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── context/
│       ├── services/
│       └── App.js
│
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```
git clone https://github.com/yourusername/task-manager-api.git
cd task-manager-api
```

---

### 2️⃣ Backend Setup

```
cd backend
npm install
```

Create `.env` file:

```
PORT=5000
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret_key
```

Run backend:

```
npm start
```

---

### 3️⃣ Frontend Setup

```
cd frontend
npm install
npm start
```

---

## 📡 API Endpoints

### 🔐 Authentication

* POST /api/auth/register
* POST /api/auth/login

### 📋 Tasks

* GET /api/tasks
* POST /api/tasks
* PUT /api/tasks/:id
* DELETE /api/tasks/:id

---

## 🧪 Testing

* Tested using Postman
* API responses validated
* Authentication tested using JWT tokens

---

## 📊 Database Design

### User

* name
* email
* password

### Task

* title
* description
* completed
* priority
* dueDate
* category
* user (reference)

---

## 🔮 Future Enhancements

* Add Notifications
* Improve UI/UX
* Add Dashboard Analytics
* Deploy Application

---

## 👨‍💻 Author

**Akash**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
