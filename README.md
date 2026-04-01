# FastAPI Todo App 🚀

A **RESTful Todo Management API** built with **FastAPI**, **JWT Authentication**, **SQLite**, and **SQLAlchemy ORM**.

This project supports secure user authentication and complete CRUD operations for managing todos.

---

## ✨ Features

* User signup & login with JWT authentication
* Protected routes using bearer token
* Create, read, update, and delete todos
* SQLAlchemy ORM integration
* SQLite database support
* Modular router-based project structure
* Interactive API docs with Swagger UI

---

## 🛠️ Tech Stack

* **Python**
* **FastAPI**
* **SQLAlchemy**
* **SQLite**
* **JWT / OAuth2**
* **Uvicorn**

---

## 📂 Project Structure

```text
fastapi-todo-app/
│── routers/
│   ├── auth.py
│   ├── todos.py
│   └── admin.py
│── database.py
│── models.py
│── main.py
│── requirements.txt
│── .gitignore
│── README.md
```

---

## ▶️ Run Locally

```bash
uvicorn main:app --reload
```

Open in browser:

```text
http://127.0.0.1:8000/docs
```

---

## 🔐 Authentication

This project uses **JWT token-based authentication**.

1. Login using `/auth/token`
2. Copy the access token
3. Click **Authorize** in Swagger UI
4. Use: `Bearer <your_token>`

---

## 📌 Future Improvements

* Role-based admin access
* PostgreSQL integration
* Docker deployment
* Unit testing with Pytest
* CI/CD pipeline

---

## 👩‍💻 Author

**Labanya Roy**

Built as part of backend learning and portfolio development with FastAPI.

