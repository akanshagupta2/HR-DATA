# HR Dataset (SQL)

This project contains a full HR (Human Resources) database schema along with sample SQL queries to explore employee, department, and job-related data. 
It is suitable for learners and practitioners who want to improve their SQL skills with real-world structures and queries.

## 📦 Contents

- `HR Dataset.SQL`: SQL file containing:
  - Database and table creation scripts
  - Foreign key relationships between tables
  - Sample SQL queries for data analysis

## 🗂️ Database Tables

The dataset includes the following tables:
- `countries`
- `regions` 
- `locations`
- `departments`
- `employees`
- `jobs`
- `job_history`

> Note: Make sure to create the `regions` table before importing, as it's referenced via foreign key in `countries`.

## 📊 Sample Queries Included

The SQL file includes several practical business queries such as:

1. Number of employees per department  
2. Total number of departments  
3. List of departments with active employees  
4. Employees in the Marketing department  
5. Departments with and without employees  
6. Employees without departments and vice versa  
7. Employees earning above the average salary  
8. Senior-most employee per department  
9. Job progression for each employee  

These examples help understand real-life HR data scenarios and SQL operations like joins, aggregation, subqueries, and window functions.

## 🛠️ How to Use

1. Import the SQL file into any SQL-compatible RDBMS (like MySQL, MariaDB, or PostgreSQL with syntax adjustments).
2. Run the included queries to explore the data.

