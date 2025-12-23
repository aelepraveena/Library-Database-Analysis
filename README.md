# Library Database Analysis (SQL Project)

## Overview

This project demonstrates **practical SQL-based database design and analysis** using a library management scenario. It focuses on building a normalized relational database, enforcing data integrity, and extracting meaningful insights through structured queries. The goal is not just CRUD operations, but **decision-oriented analysis** using real-world relationships between books, borrowers, branches, and loans.



## Objectives

* Design a **normalized relational schema** for a library system
* Implement **primary keys, foreign keys, and constraints**
* Populate tables with realistic sample data
* Write **non-trivial SQL queries** to answer operational questions
* Analyze borrowing patterns, inventory distribution, and branch performance


## Database Schema

The database consists of the following tables:

* **tbl_publisher** – Publisher details
* **tbl_book** – Book metadata (linked to publisher)
* **tbl_library_branch** – Library branch information
* **tbl_book_copies** – Number of copies per book per branch
* **tbl_borrower** – Borrower details
* **tbl_book_loans** – Loan transactions (book, borrower, branch, dates)

Relationships are enforced using **foreign keys**, ensuring referential integrity across all transactions.


## Key SQL Concepts Used

* Table creation with constraints
* Primary and foreign key relationships
* INNER JOINs across multiple tables
* Aggregate functions (`COUNT`, `SUM`)
* Grouping and filtering (`GROUP BY`, `HAVING`, `WHERE`)
* Realistic problem-solving queries instead of toy examples
  


## Insights Gained

* Structured data enables **clear visibility into usage patterns**
* SQL joins are critical for extracting value from normalized schemas
* Branch-level and borrower-level trends can guide inventory decisions
* Clean schema design reduces errors during data import and querying



## Tools & Technologies

* MySQL / SQL
* Relational Database Design
* SQL Query Optimization (basic level)


## How to Use

1. Import the SQL schema into a MySQL database
2. Insert the provided sample data
3. Execute analysis queries from the queries file
4. Modify queries to explore additional insights


Developed as part of hands-on SQL practice to strengthen database design and analysis skills.
