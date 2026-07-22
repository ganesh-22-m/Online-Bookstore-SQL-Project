# 📚 Online Bookstore SQL Project

## 📖 Project Overview

This project demonstrates SQL skills by designing and querying an **Online Bookstore Database**. It is created as a portfolio project for **Business Analyst** and **Technical Business Analyst** roles.

The project includes database creation, data import, and business-focused SQL queries to analyze sales, customers, books, and revenue.

---

## 🎯 Project Objective

The objective of this project is to:

- Design a relational database.
- Practice SQL queries used in real business scenarios.
- Generate business insights from bookstore data.
- Demonstrate SQL skills required for Business Analyst interviews.

---

## 🛠️ Technologies Used

- PostgreSQL
- SQL
- CSV Files
- GitHub

--

## 📂 Database Structure

### Books

Stores information about books.

Columns:
- Book_ID
- Title
- Author
- Genre
- Price
- Stock

---

### Customers

Stores customer information.

Columns:
- Customer_ID
- Customer_Name
- Email
- City

---

### Orders

Stores customer purchase details.

Columns:
- Order_ID
- Customer_ID
- Book_ID
- Quantity
- Order_Date
- Total_Amount

---

## 🔗 Database Relationships

- One Customer can place multiple Orders.
- One Book can appear in multiple Orders.
- Orders connect Customers and Books using Foreign Keys.

---

## 📊 SQL Concepts Covered

- CREATE DATABASE
- CREATE TABLE
- PRIMARY KEY
- FOREIGN KEY
- INSERT
- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- INNER JOIN
- COUNT()
- SUM()
- AVG()
- MAX()
- MIN()
- DISTINCT
- LIMIT
- Subqueries

---

## 📈 Business Questions Solved

- Display all books.
- Find books by genre.
- Sort books by price.
- Count total books.
- Find total revenue.
- Find the highest priced book.
- Find the lowest priced book.
- Find the average book price.
- Identify the most valuable customer.
- Display customers from a specific city.
- Find remaining stock.
- Find books ordered by customers.
- Display total sales by genre.
- Find duplicate records.
- Retrieve top-selling books.

---

## 📁 Project Files

```
Online-Bookstore-SQL-Project
│
├── OnlineBookstoreSQL.sql
├── Books.csv
├── Customers.csv
├── Orders.csv
└── README.md
```

---

## 💼 Skills Demonstrated

- Database Design
- SQL Query Writing
- Data Analysis
- Business Reporting
- Relational Database Management
- Problem Solving
- Business Intelligence Fundamentals

---

## 🎯 Suitable For

This project is suitable for portfolios targeting roles such as:

- Technical Business Analyst
- Business Analyst
- Data Analyst
- SQL Developer
- Database Analyst

---

## 👨‍💻 Author

**Ganesh Mahajan**

- Bachelor of Engineering (Computer Science)
  
- Aspiring Technical Business Analyst

---

## ⭐ Future Improvements

- Add ER Diagram
- Create Power BI Dashboard
- Build Sales Analytics Dashboard
- Add Stored Procedures
- Add Views
- Add Indexes
- Add Business KPI Reports

---

## 📜 License

This project is created for educational and portfolio purposes.
