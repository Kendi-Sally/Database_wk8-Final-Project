# Library Management Database (Week 8 Final Project)

## Project Overview
This project implements a **relational database management system** for a library.  
It manages:
- **Authors** (who wrote books)
- **Books** (with details like title, genre, and published year)
- **Members** (library users with membership details)
- **Borrowings** (records of which member borrowed which book)

The project demonstrates:
- Primary keys
- Foreign keys
- One-to-Many and Many-to-Many relationships

---

 Technologies Used
- **MySQL**

---
 Database Schema
- **Authors** → Stores author details  
- **Books** → Linked to authors (One-to-Many)  
- **Members** → Stores library member details  
- **Borrowings** → Links members and books (Many-to-Many)  

---

##  How to Run
1. Open MySQL Workbench (or your preferred MySQL client).
2. Create a new query and paste the contents of `library_management.sql`.
3. Run the script to create the databas
