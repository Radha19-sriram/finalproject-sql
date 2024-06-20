# SQL Project

This project contains a series of SQL queries and operations designed to perform various tasks on a database. The tasks include removing duplicates, selecting distinct values, and other common database operations.

## Project Overview

The purpose of this project is to demonstrate proficiency in SQL by performing a variety of operations on sample datasets. The operations include:
- Removing duplicate entries
- Selecting distinct values
- Filtering data based on conditions
- Aggregating data using functions like `COUNT`, `SUM`, `AVG`, etc.
- Joining multiple tables

## File Structure

- `Radha_SQL_PROJECT.xlsx`: This file contains the SQL queries and their explanations. Each sheet in the Excel file represents a different task or set of tasks.

## SQL Queries and Operations

### 1. Removing Duplicates
- **Query:**
  ```sql
  SELECT DISTINCT city, state FROM store2;
Explanation: This query removes duplicate entries from the `city` and `state` columns in the store2 table.

2. Selecting Distinct Values
   SELECT DISTINCT column_name FROM table_name;
   Explanation: This query selects unique values from the specified column in the table.

3. Filtering Data
   SELECT * FROM table_name WHERE condition;
   Explanation: This query filters the data based on the given condition.

4. Aggregating Data
   SELECT COUNT(column_name) FROM table_name;
   Explanation: This query counts the number of entries in the specified column.

5. Joining Tables
   SELECT a.column_name, b.column_name 
   FROM table1 a
   JOIN table2 b ON a.common_column = b.common_column;
   Explanation: This query joins two tables on a common column and selects specified columns from both tables.

Acknowledgment
Special thanks to the instructors and mentors who guided the creation of this project.



