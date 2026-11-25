# Student Management System

A web-based Student Management System developed using Python, Flask, SQLite, HTML, CSS, and JavaScript.

## 1. Project Overview

The Student Management System is designed to manage student information and academic activities through separate Admin, Teacher, and Student dashboards.

## 2. User Roles

- **Admin:** Manages students, teachers, attendance, marks, results, and notifications.
- **Teacher:** Views student information and manages permitted academic activities.
- **Student:** Views personal academic information, attendance, and marks.

## 3. Main Features

- Admin, Teacher, and Student Login
- Role-Based Access Control
- Student Management
- Teacher Management
- Attendance Management
- Marks and Result Management
- Notifications
- Recycle Bin
- Session-Based Authentication
- SQLite Database

## 4. Technologies Used

### Backend

- Python
- Flask
- Flask-CORS
- SQLite
- Werkzeug

### Frontend

- HTML
- CSS
- JavaScript

## 5. Project Structure

```text
Student-Management-Project/
├── Backend/
│   ├── app.py
│   ├── database.py
│   └── students.db
├── Frontend/
│   ├── login.html
│   ├── admin-dashboard.html
│   ├── teacher-dashboard.html
│   └── student-dashboard.html
└── README.md
```

## 6. Installation

### Requirements

- Python 3
- Visual Studio Code
- Live Server Extension

Install the required Python packages:

```bash
python3 -m pip install Flask Flask-CORS
```

## 7. How to Run the Project

### Step 1: Start Backend

Open Terminal and run:

```bash
cd ~/Desktop/Student-Management-Project/Backend
python3 app.py
```

Backend URL:

[http://127.0.0.1:5001](http://127.0.0.1:5001)

### Step 2: Start Frontend

1. Open the project folder in Visual Studio Code.
2. Open the Frontend folder.
3. Launch `login.html` using the Live Server extension.

Frontend URL:

[http://127.0.0.1:5500/Frontend/login.html](http://127.0.0.1:5500/Frontend/login.html)

## 8. Database

The project uses SQLite for storing student and academic information.

Database file: `Backend/students.db`

Create a separate database backup before making major changes.

## 9. Security

- Password hashing
- Role-based API permissions
- Session-based authentication
- Student data access restrictions

Production deployment requires additional security configuration, HTTPS, and a protected secret key.

## 10. Testing Status

The following modules have been tested locally:

- Admin Login
- Teacher Login
- Student Login
- Student Management
- Attendance Management
- Marks and Results
- Notifications
- Recycle Bin
- Teacher Management
- Logout and Session Protection
- Database Backup and Integrity Check

## 11. Conclusion

The Student Management System provides a centralized platform for managing student information and academic activities. It simplifies administrative work and provides separate access for Admin, Teachers, and Students.

## 12. Future Scope

- Online deployment
- Automated report generation
- Additional analytics
- Improved mobile responsiveness
