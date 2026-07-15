# Student-Management-system
# Student Management System

## 📌 Project Overview

The **Student Management System** is a Python-based application developed to manage student records efficiently. The project uses **Python** for programming logic and **SQLite** as a database to store and manage student information.

This system allows users to perform basic database operations such as adding, viewing, searching, updating, and deleting student records.

The main objective of this project is to learn the fundamentals of **Python programming, database management, and CRUD operations**.

---

## 🎯 Objectives

* To create a digital system for managing student information.
* To understand database connectivity using Python.
* To implement CRUD operations:

  * Create student records
  * Read student details
  * Update student information
  * Delete student records
* To gain practical experience in software development.

---

## 🛠️ Technologies Used

| Technology             | Purpose                     |
| ---------------------- | --------------------------- |
| Python                 | Programming Language        |
| SQLite                 | Database Management         |
| Pandas                 | Displaying database records |
| Google Colab / VS Code | Development Environment     |

---

## ✨ Features

### 1. Add Student

Users can add new student details:

* Student ID
* Name
* Age
* Department
* Email

---

### 2. View Students

Displays all stored student records from the database.

Example:

```
ID    Name          Age    Department

101   Dheekshith   19     CSE AIML
102   Rahul        20     CSE
```

---

### 3. Search Student

Allows users to search student records using the student's name.

---

### 4. Update Student

Users can modify existing student information.

Example:

```
Before:
Age = 19

After:
Age = 20
```

---

### 5. Delete Student

Removes unwanted student records from the database.

---

## 📂 Project Structure

```
Student-Management-System

│
├── student_management.py
│
├── student_database.db
│
└── README.md
```

---

## ⚙️ Installation and Setup

### Step 1: Install Python

Download Python from the official website.

Check installation:

```
python --version
```

---

### Step 2: Install Required Library

Install pandas:

```
pip install pandas
```

(SQLite is already included with Python)

---

### Step 3: Run the Program

Execute:

```
python student_management.py
```

---

## ▶️ How to Use

After running the program, the menu appears:

```
========= Student Management System =========

1. Add Student
2. View Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit

============================================
```

Choose an option and follow the instructions.

---

## 🗄️ Database Design

The project uses an SQLite database with the following table:

### Students Table

| Column     | Data Type             |
| ---------- | --------------------- |
| id         | Integer (Primary Key) |
| name       | Text                  |
| age        | Integer               |
| department | Text                  |
| email      | Text                  |

---

## 📚 Concepts Learned

Through this project, the following concepts are implemented:

* Python Functions
* User Input Handling
* SQLite Database Connection
* SQL Queries
* CRUD Operations
* Data Management
* Project Structure

---

## 🚀 Future Enhancements

Future improvements planned:

* Add user authentication/login system
* Create GUI using Tkinter
* Export student data to Excel/PDF
* Add attendance management
* Add AI-based student performance prediction
* Deploy as a web application using Flask

---

## 👨‍💻 Author

**Dheekshith Immanuel**
B.Tech Computer Science Engineering (AI & ML)

---

## 📄 License

This project is created for educational purposes and learning software development concepts.
