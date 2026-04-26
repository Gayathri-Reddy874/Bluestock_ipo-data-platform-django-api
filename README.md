# 🚀 Bluestock IPO Data Platform (Django API)

A full-stack IPO (Initial Public Offering) management platform with a backend API built using Django REST Framework.

---

## 📌 Overview

The **Bluestock IPO Data Platform** is a backend-focused full-stack application inspired by the IPO management system I worked on during my internship at Bluestock Fintech (May 2025 – Batch L73).

This repository represents my **individual implementation and understanding** of backend API development, including CRUD operations, authentication, and database integration.

---

## 🎯 Key Features

* 📊 IPO Listing Management (Create, Read, Update, Delete)
* 🔐 Secure Authentication & Authorization (JWT-based)
* 🗄️ PostgreSQL Database Integration
* 📩 Email Configuration for Password Reset
* ⚡ RESTful API Design
* 🧩 Modular Django Architecture
* 🌐 Full-stack structure (Backend + Frontend)

---

## 🏗️ Project Structure

```
Bluestock_Project/
│
├── backend/           # Django REST API
│   └── API/
│
├── ipo-frontend/      # React Frontend Application
│
├── screens/           # Project screenshots (optional)
│
└── README.md
```

---

## ⚙️ Tech Stack

* **Backend:** Django, Django REST Framework
* **Database:** PostgreSQL (NeonDB)
* **Frontend:** React (Create React App)
* **Tools:** Git, GitHub

---

## 📦 Prerequisites

* Python 3.x
* pip
* PostgreSQL
* Node.js & npm (for frontend)
* Virtual Environment (recommended)

---

## 📥 Clone the Repository

```bash
git clone https://github.com/Gayathri-Reddy874/Bluestock_ipo-data-platform-django-api.git
cd Bluestock_ipo-data-platform-django-api
```

---

## 🧪 Installation & Setup

### 🔹 1. Create Virtual Environment (Backend)

```bash
cd backend
python -m venv backenv
```

---

### 🔹 2. Activate Environment

```bash
# Windows
backenv\Scripts\activate

# Linux/Mac
source backenv/bin/activate
```

---

### 🔹 3. Install Backend Dependencies

```bash
cd API
pip install -r requirements.txt
```

---

### 🔹 4. Configure Environment Variables

Create a `.env` file in the backend directory:

```env
EMAIL_USER=your_email
EMAIL_PASS=your_password
EMAIL_FROM=your_email

PGHOST=your_host
PGDATABASE=your_database
PGUSER=your_user
PGPASSWORD=your_password
```

---

### 🔹 5. Apply Migrations

```bash
python manage.py migrate
```

---

### 🔹 6. Create Superuser

```bash
python manage.py createsuperuser
```

---

### 🔹 7. Run Backend Server

```bash
python manage.py runserver 8001
```

👉 Admin Panel: http://127.0.0.1:8001/admin

---

### 🔹 8. Run Frontend

```bash
cd ../../ipo-frontend
npm install
npm start
```

👉 Frontend runs at: http://localhost:3000

---

## 📡 Sample API Endpoints

| Method | Endpoint        | Description          |
| ------ | --------------- | -------------------- |
| GET    | /api/ipos/      | Get all IPO listings |
| POST   | /api/ipos/      | Create new IPO       |
| GET    | /api/ipos/{id}/ | Get IPO details      |
| PUT    | /api/ipos/{id}/ | Update IPO           |
| DELETE | /api/ipos/{id}/ | Delete IPO           |

---

## 📡 API Documentation

Reference:
https://github.com/bitz-1/bluestock-ipo-rest-api

---

## 🧑‍💻 Internship Experience & Contributions

During my internship at Bluestock Fintech (May 2025 – Batch L73), I worked as part of a team on an IPO management system.

### 🔹 My Contributions

* Developed and tested RESTful APIs using Django REST Framework
* Implemented CRUD operations for IPO data management
* Worked on PostgreSQL database integration
* Assisted in backend logic development and API structuring
* Participated in debugging, testing, and performance improvements

### 🔹 Key Learnings

* Real-world backend development workflows
* API design and data handling
* Team-based software development practices
* Version control and deployment fundamentals

---

## ⚠️ Disclaimer

This repository is an **independent and simplified implementation** based on my internship experience.

It does **not contain any proprietary or confidential code** from the original project and is intended solely for **educational and portfolio purposes**.

---

## 📜 License

This project is intended for educational and demonstration purposes only.
Based on internship experience at Bluestock Fintech.
Original system components may be proprietary to the organization.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📬 Contact

* GitHub: https://github.com/Gayathri-Reddy874
