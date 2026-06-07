# SMS-student-management-system-
# Student Management System

## Developed by Yanet Yeshiwas

### Project Overview

The Student Management System is a desktop-based application developed using Python and MySQL to streamline student information management within educational institutions. The system provides a centralized platform for managing student records, attendance, fees, faculty information, and administrative activities through role-based access control.

The application features an intuitive graphical user interface (GUI) built with Tkinter, making it easy for users to interact with the system efficiently.

---

## Features

### Super Administrator

* Create and manage administrator accounts
* Update administrator information
* Reset and change passwords
* Monitor system administration

### Administrator

* Add and manage student records
* Add and manage faculty records
* Update student fee information
* Maintain institutional data

### Faculty

* Mark student attendance
* View student records
* Manage class information
* Monitor attendance history

### Student

* View personal profile
* Check attendance records
* View fee payment history
* Access academic information

---

## Technologies Used

### Programming Language

* Python 3

### Graphical User Interface

* Tkinter

### Database

* MySQL

### Python Libraries

* mysql-connector-python
* tkcalendar
* tktooltip
* Pillow (PIL)

---

## Database Design

The database is designed using MySQL and includes advanced database concepts such as:

* Stored Procedures
* Functions
* Triggers

These components automate tasks such as user ID generation, attendance management, and data validation, improving system efficiency and reliability.

---

## Project Structure

```text
Student-Management-System/
│
├── app.py
├── config.ini
├── database/
│   └── sql_file.sql
├── modules/
├── reports/
├── assets/
└── README.md
```

---

## Installation Guide

### Prerequisites

Before running the project, ensure the following are installed:

* Python 3.x
* MySQL Server
* MySQL Workbench (Optional)

### Install Required Packages

```bash
pip install pillow
pip install tkcalendar
pip install tktooltip
pip install mysql-connector-python
```

---

## Database Setup

1. Create a new MySQL database.
2. Import the SQL script provided in the project.
3. Execute all database queries included in the SQL file.
4. Configure database credentials in the `config.ini` file.

Example:

```ini
host=localhost
user=root
password=your_password
database=student_management
```

---

## Running the Application

Run the application using:

```bash
python app.py
```

---

## System Benefits

* Reduces manual paperwork
* Improves data accuracy
* Simplifies attendance tracking
* Provides secure role-based access
* Enhances administrative efficiency
* Centralizes academic information

---

## Future Enhancements

* Online student portal
* Email notifications
* Report generation in PDF format
* Mobile application integration
* Advanced analytics dashboard
* Cloud database support

---

## Learning Outcomes

This project demonstrates practical knowledge in:

* Python Programming
* GUI Development using Tkinter
* MySQL Database Design
* CRUD Operations
* Role-Based Authentication
* Database Triggers and Procedures
* Software Development Practices

---

## License

This project is intended for educational and learning purposes.

---

## Author

**Yanet Yeshiwas**

Passionate about software development, database systems, and technology-driven solutions.
