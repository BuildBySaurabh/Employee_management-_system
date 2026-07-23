# Employee Management System

A simple and efficient **Employee Management System** built with **Python** and **Django** for managing employee records in an organized and user-friendly way. The application allows administrators to add, update, search, and manage employee information through a clean and responsive interface.

To make the application more visually appealing, a continuous **JavaScript snowfall animation** has been added, giving the system a unique and modern look.

---

## ✨ Features

### 👨‍💼 Employee Management

- Add new employees
- View all employee records
- Update employee information
- Delete employee records
- Manage employee details through the Django Admin Panel

---

### 📋 Employee Information

Each employee record includes:

- Auto-generated Employee ID
- Full Name
- Designation
- Mobile Number
- Email Address
- Gender
- Address
- Salary
- Employment Status (Working / Not Working)

---

### 🆔 Automatic Employee ID

Every employee is assigned a unique Employee ID automatically, making employee management easier and preventing duplicate IDs.

---

### 📊 Employee Dashboard

View all employee records in a clean and responsive table displaying:

- Employee ID
- Employee Name
- Designation
- Employment Status
- Salary

---

### 🔍 Search & Filter

Quickly search and filter employees to find records without scrolling through the entire list.

---

### ❄️ Snowfall Animation

The application includes a continuous JavaScript snowfall effect that enhances the overall user experience while maintaining a clean and professional interface.

---

# 🚀 Application Workflow

```text
Administrator
      │
      ▼
Add Employee
      │
      ▼
Generate Employee ID
      │
      ▼
Save Employee Details
      │
      ▼
Employee Dashboard
      │
      ▼
Search / Update / Delete Employee
```

---

# 🛠️ Tech Stack

## Backend

- Python
- Django

## Frontend

- HTML5
- CSS3
- JavaScript

## Styling

- Bootstrap
- Custom CSS

## Database

- SQLite

## Django Components

- Django ORM
- Django Forms
- Django Admin

---

# 📂 Project Structure

```text
employee_management_system/
│
├── employee_management_system/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── employees/
│   ├── migrations/
│   ├── templates/
│   ├── static/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   └── admin.py
│
├── media/
├── db.sqlite3
├── requirements.txt
├── manage.py
└── README.md
```

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone https://github.com/BuildBySaurabh/employee-management-system.git
cd employee-management-system
```

---

## 2. Create a Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4. Apply Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

## 5. Create an Admin User (Optional)

```bash
python manage.py createsuperuser
```

---

## 6. Start the Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/
```

---

# 💡 Purpose of the Project

This project was built to simplify employee record management by providing a centralized platform where administrators can:

- Store employee information securely
- Update employee records easily
- Track active and inactive employees
- Reduce manual paperwork
- Improve overall HR management efficiency

---

# ⭐ Technical Highlights

- Full CRUD (Create, Read, Update, Delete) functionality
- Automatic Employee ID generation
- Employee status tracking
- Search and filtering support
- Responsive Bootstrap UI
- Django ModelForms
- SQLite database integration
- Django Admin support
- JavaScript snowfall animation
- Clean and maintainable project structure

---

# 🔮 Future Enhancements

Planned improvements include:

- Employee authentication
- Role-based access control
- Attendance management
- Leave management
- Payroll management
- Department management
- Employee profile pages
- PDF report generation
- Email notifications
- PostgreSQL support
- REST API integration
- Docker deployment

---



---

## If you found this project useful, consider giving it a ⭐ on GitHub!
