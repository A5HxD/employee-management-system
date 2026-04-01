# 🧑‍💼 Employee Management System

## 📌 Overview
A Python and MySQL-based employee management system that allows users to manage employee records, perform CRUD operations, and generate salary slips.

## 🔧 Technologies Used
- Python
- MySQL

## 🗄️ Database Schema

Table: emp

- empno (INT, PRIMARY KEY)
- name (VARCHAR)
- dept (VARCHAR)
- salary (INT)

## ⚙️ Features
- Add, search, update, and delete employee records
- Display employee list in tabular format
- Generate salary slips with calculated deductions and earnings
- Role-based interaction (Admin and Employee)

## 📂 Project Structure
```
employee-management-system/
│
├── src/
│ └── employee_system.py
│
├── screenshots/
│ └── output.png
│
└── README.md
```

## ▶️ How to Run

1. Install MySQL  
2. Create database:
   CREATE DATABASE company;

3. Create table:
   CREATE TABLE emp (
     empno INT PRIMARY KEY,
     name VARCHAR(50),
     dept VARCHAR(50),
     salary INT
   );

4. Update credentials in code  
5. Run:
   python employee_system.py


## 🖼️ Output Preview
![Output](screenshots/output(1).png)
![Output](screenshots/output(2).png)

## 🚀 Conclusion
This project demonstrates database integration, CRUD operations, and basic payroll logic using Python and MySQL.
