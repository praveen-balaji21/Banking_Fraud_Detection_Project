**# 🏦 Banking Fraud Detection SQL Project**

## 📌 Project Overview

This project is a **Banking Fraud Detection Database System** built using **MySQL**.

It simulates real-world banking operations including:

* Customer Management
* Account Management
* Transaction Processing
* Fraud Detection & Risk Analysis

The database is fully relational with proper foreign key constraints and normalized schema design.

---

## 🗂 Database Structure

### Total Tables: 4

1. Customers
2. Accounts
3. Transactions
4. Fraud_Alert

### Relationships Implemented

✔ One-to-Many Relationship between Customer and Accounts

✔ One-to-Many Relationship between Account and Transactions

✔ One-to-Many Relationship between Transactions and Fraud Alerts

✔ Referential Integrity maintained using Foreign Keys

✔ Normalized Database Design (up to 3NF)

---

## 🔥 Implemented SQL Business Scenarios

This project includes real-time banking and fraud analysis queries from basic to advanced level.

### ✅ Basic Level Queries

* Total number of customers
* Active vs Inactive accounts
* Total transaction amount
* Maximum and minimum transaction amount
* Top 5 transactions by amount
* Top 5 customers by account balance
* Customers with inactive savings accounts

### ✅ Intermediate Level Queries

* Customer-wise transaction history
* Fraud transactions with customer details
* Normal transactions report
* Average transaction amount by city
* High-value transaction detection
* Location-wise transaction analysis
* Top customers based on transaction amount

### ✅ Advanced Level Queries

* Customer Risk Score Classification
* Fraud-Prone Location Identification
* Banking Master Table Creation using JOINs
* Top Customers using Window Functions
* Top Customers using CTEs
* Fraud Pattern Analysis
* Risk Categorization using CASE Statements

---

## 🧠 SQL Concepts Demonstrated

✔ Database Design

✔ Primary Keys & Foreign Keys

✔ CRUD Operations

✔ INNER JOIN

✔ LEFT JOIN

✔ Aggregate Functions (COUNT, SUM, AVG, MAX, MIN)

✔ GROUP BY & HAVING

✔ CASE Statements

✔ Common Table Expressions (CTE)

✔ Window Functions (ROW_NUMBER)

✔ Subqueries

✔ Data Analysis Queries

✔ Fraud Detection Logic

---

## 📊 Key Business Insights Generated

* Customers involved in suspicious transactions
* High-risk customers based on fraud history
* Locations generating maximum fraud alerts
* High-value transaction monitoring
* Average spending behavior by city
* Active vs inactive account analysis
* Fraud trend identification

---

## 📁 Project Files

* `banking_database.sql` → Database Schema & Table Creation
* `sample_data.sql` → Sample Banking Data
* `queries.sql` → SQL Analysis Queries
* `er_diagram.png` → Database ER Diagram

---

## 🖼 ER Diagram

(Add ER Diagram Screenshot Here)

---

## ⚙ Technologies Used

* MySQL
* MySQL Workbench
* Git & GitHub

---

## 🎯 What This Project Demonstrates

* Strong understanding of Relational Database Design
* Banking Domain Knowledge
* Fraud Detection using SQL
* Advanced Query Writing Skills
* Data Analysis using SQL
* Real-world Business Problem Solving
* Hands-on Experience with Joins, CTEs, Window Functions, and Aggregations

---

## 🚀 How to Run

### Create Database

```sql
CREATE DATABASE Proj;
USE Proj;
```

### Run Table Creation Script

```sql
SOURCE banking_database.sql;
```

### Insert Sample Data

```sql
SOURCE sample_data.sql;
```

### Execute Analysis Queries

```sql
SOURCE queries.sql;
```

---

## ⭐ Project Highlights

* 30 Customers
* 30 Accounts
* 30 Transactions
* Fraud Detection Scenarios
* Risk Scoring System
* Banking Analytics Dashboard Ready Dataset
* Advanced SQL Concepts Implemented
