# 🏥 Hospital Management System

This project is a simplified Hospital Management System designed to manage essential hospital information, including patient and doctor registration and login functionality. It serves as a foundational platform for securely accessing and maintaining key data in a healthcare environment.

---

## 💡 Features

- Menu tab with navigation and "About Us" section  
- Patient and doctor registration and login system

---

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/hospital-Mangement-System.git
   cd hospital-Mangement-System
2. **Create and activate a virtual environment**
⚠️ This project uses Django 3.0.7, which depends on the cgi module. Python 3.13+ no longer includes it, so use Python 3.11 or Python 3.10.
    ```bash
    py -3.11 -m venv venv
    venv\Scripts\activate
3. **Install dependencies**
💡 If psycopg2 causes issues, you can replace it with psycopg2-binary in requirements.txt for local development.
    ```bash
    pip install -r requirements.txt
4. **Run the development server**
    ```bash
    python manage.py runserver

---

## 📌 Notes

This project uses Django 3.0.7
Database setup is PostgreSQL by default (via psycopg2), but can be adapted for SQLite during local testing.

---

## 📂 Project Structure

hospital-Mangement-System/
├── .idea/ # IDE-specific settings (e.g., for PyCharm or VSCode)
├── account/ # User authentication logic (login, registration)
├── appointment/ # Appointment scheduling features
├── hospital/ # Main Django project settings and configuration
├── static/ # Static files (CSS, JS, images)
├── templates/ # HTML templates used by the views
├── user_profile/ # User profile management (doctors, patients, etc.)
├── venv/ # Python virtual environment
├── db.sqlite3 # SQLite database (used for local development)
├── LICENSE.md # Project license file
├── manage.py # Django’s command-line utility
├── requirements.txt # Python dependencies for the project
├── README.md # Project documentation
└── .gitignore # Files and folders ignored by Git

---

## 📋 License

GPL-3.0 license
