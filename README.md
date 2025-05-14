
# 📚 Smart Library Management System

## 📝 Project Description

The **Smart Library Management System** is a full-featured relational database built using MySQL. It is designed to handle everyday operations in a library such as user registration, book management, borrow/return tracking, fine calculation, and reservation handling.

This system supports:
- Tracking users (students/staff)
- Managing books, authors, and categories
- Borrowing and returning of books
- Handling fines for overdue returns
- Reserving books
- Many-to-many relationships between books and authors

---

## 🚀 How to Run / Set Up the Project

1. Ensure you have **MySQL Server** installed on your machine.
2. Open your preferred MySQL client (e.g., MySQL Workbench, phpMyAdmin, or CLI).
3. Import the provided SQL file:

### Option 1: Using MySQL CLI
```bash
mysql -u your_username -p < smart_library_schema.sql
```

### Option 2: Using MySQL Workbench
- Open Workbench and connect to your MySQL server.
- Open the `smart_library_schema.sql` file.
- Execute the script to create the database and all required tables.

---

## 📷 ERD Screenshot or Link

You can view the Entity-Relationship Diagram (ERD) for the system at the ERD.png file.

---

## 📁 Repository Structure

```
SmartLibrary/
│
├── smart_library_schema.sql    # Contains all CREATE TABLE statements
├── README.md                   # This file
└── ERD.png                     # (Optional) ERD image file
```

---

## 👨‍💻 Author

Created by Tech-swift, A passionate developer with a strong focus on building high-quality software.  
Feel free to contribute or fork this project.
