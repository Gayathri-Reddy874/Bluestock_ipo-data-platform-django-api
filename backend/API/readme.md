# 🚀 IPO REST API (Django Backend)

This is a backend REST API for managing IPO (Initial Public Offering) data, built using Django and Django REST Framework.

This project is an individual implementation inspired by my internship experience at Bluestock Fintech.

---

## 📌 Overview

The API enables administrators to manage IPO listings and allows users to securely access IPO data through authenticated endpoints.

---

## 🎯 Features

### 🔹 Admin CRUD Operations

* **POST /administrator/api/v1/ipo-list/** → Create a new IPO
* **GET /administrator/api/v1/ipo-list/** → Retrieve IPO list
* **PUT /administrator/api/v1/ipo-list/{id}/** → Update IPO
* **DELETE /administrator/api/v1/ipo-list/{id}/** → Delete IPO

---

### 🔹 User Operations

* **POST /api/user/register/** → Register user
* **POST /api/user/login/** → Login user (JWT Authentication)
* **POST /api/user/changepassword/** → Change password
* **GET /api/user/ipo/** → View IPO list
* **GET /api/user/profile/** → Get user profile
* **POST /api/user/send-reset-password-email/** → Send reset email
* **POST /api/user/reset-password/{uid}/{token}/** → Reset password

---

## ⚙️ Tech Stack

* Django
* Django REST Framework
* PostgreSQL (Neon DB)
* JWT Authentication

---

## 🧪 Getting Started

### 🔹 Prerequisites

* Python 3.x
* PostgreSQL
* pip
* Postman (for API testing)

---

## ▶️ Run the Server

```bash id="uxz1zz"
python manage.py runserver
```

---

## 🔐 Authentication

JWT-based authentication is used.
Include the token in request headers:

```text id="nyh7d9"
Authorization: Bearer <your_token>
```

---

## ⚠️ Disclaimer

This project is a simplified and independent implementation based on a team project completed during my internship.

It does not include any proprietary or confidential components from the original system.

---

## 📜 License

This project is for educational and portfolio purposes only.
Based on internship experience at Bluestock Fintech.

---

## 📬 Contact

* GitHub: https://github.com/Gayathri-Reddy874
