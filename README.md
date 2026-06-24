# **Face Recognition Attendance System**

A web-based attendance management system that uses facial recognition technology to identify students and record attendance automatically. This project simplifies attendance tracking for classrooms, workplaces, or events.

---

## **📋 Features**

Facial recognition-based attendance tracking
Administrator dashboard
Lecturer dashboard
Student management
Course and venue management
Attendance record generation
Attendance export to Excel
Face API.js integration for facial recognition

## Project Structure

```plaintext

FaceRecognitionAttendanceSystem/
├── database/
│   ├── attendance-db.sql
│   └── database_connection.php
├── models/
├── resources/
│   ├── assets/
│   ├── images/
│   ├── labels/
│   ├── lib/
│   └── pages/
│       ├── administrator/
│       ├── lecture/
│       └── login.php
├── index.php
├── .htaccess
└── README.md
```
# Face Recognition Attendance System

## 🚀 Setup Procedure

1. Install XAMPP.
2. Start Apache and MySQL.
3. Import the database SQL file.
4. Place the project inside the XAMPP `htdocs` folder.
5. Open the project in a browser.

## 👥 User Roles

### Administrator

The administrator can:

* Register and manage students
* Manage courses and units
* Manage venues and lecturers
* Capture student facial images for recognition

### Lecturer

The lecturer can:

* Select course, unit, and venue
* Start facial recognition attendance
* View attendance records
* Export attendance reports to Excel

## 🔐 Credentials

### Administrator

**Email:** `admin@gmail.com`
**Password:** `@admin_`

### Lecturer

**Email:** `mark@gmail.com`
**Password:** `@mark_`

If the default lecturer account does not work, create a new lecturer account through the administrator panel.


````

