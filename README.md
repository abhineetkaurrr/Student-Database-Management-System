[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Python](https://img.shields.io/badge/Python-3.x-red.svg)


## Student Database Management System (SDBMS)

A desktop-based Student Database Management System built using Python, PyQt5, and SQLite.
This application allows users to add, search, view, and delete student records through a graphical user interface.

---

## 📌 Features

🔐 Simple login system

➕ Add student details (roll number, name, department, year, courses)

🔍 Search student records by roll number

🗑️ Delete student records

🪟 GUI-based application using PyQt5

💾 Persistent storage using SQLite database

---

##  🛠️ Technologies Used

Python 3

PyQt5 – for GUI

SQLite3 – for database management

---

## 📂 Project Structure

```bash
Student-database-management-System/
│
├── sdbms.py        # Main application file
├── sdms.db         # SQLite database file
├── README.md       # Project documentation
├── LICENSE         # MIT License
```
---

## 🧠 How the System Works

### Database Tables

The application uses SQLite and creates the following tables automatically:

student – stores student details and enrolled courses

faculty – stores faculty information

course – stores course details

### Functional Modules

Login Module – basic authentication (empty username/password)

Add Student – insert new student records

View Student – fetch and display student details in tabular form

Delete Student – remove student records using roll number

---

## ▶️ How to Run the Project

### Prerequisites

Make sure you have Python 3 installed.

### Install required dependency:

```
pip install PyQt5
```

### Run the Application

```
python sdbms.py
```
---

## 🔑 Login Details

Username: (leave empty)

Password: (leave empty)

(This is a basic demo login and can be enhanced in future versions.)

---

## 🖥️ User Interface Overview

### Main window with options:

Enter Student Details

Show Student Details

Delete Record

### Separate dialogs for:

Adding a student

Searching by roll number

Viewing student details in a table

---

## 🚀 Future Improvements

Add proper authentication (username/password storage)

Input validation and error handling

Update/edit student records

Export data to CSV or Excel

Improve UI styling

Role-based access (admin/faculty)

---

##  📜 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute this software.

---

## 👤 Author

Abhineet Kaur

AI & ML learner | Python & Data Analysis Enthusiast
