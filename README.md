


markdown

# SQL Learning Project

This repository contains several SQL scripts I created while learning SQL for the first time. These scripts cover various fundamental concepts of SQL, such as database creation, inserting and querying data, joins, and aggregate functions.

## Files

### 1. **LEFT+RIGHT+CROSS+JOINS.sql**
   - Demonstrates the use of different types of joins:
     - LEFT JOIN
     - RIGHT JOIN
     - CROSS JOIN

### 2. **avg_sql.sql**
   - Contains SQL queries that demonstrate the use of the `AVG()` function to calculate the average values from specific columns in a table.

### 3. **create_school_db.sql**
   - A script to create a database named `school_db` and its associated tables, such as `students`, `teachers`, and `courses`.

### 4. **delete_records.sql**
   - Demonstrates how to delete specific records from a table using the `DELETE` statement.

### 5. **drop_school_db1.sql**
   - Drops the `school_db` database if it exists, demonstrating how to safely remove a database.

### 6. **group+by.sql**
   - Shows how to use the `GROUP BY` clause in SQL to group rows sharing a property and apply aggregate functions like `COUNT()`, `SUM()`, `AVG()`, etc.

### 7. **insert_more_courses.sql**
   - Adds additional records to the `courses` table.

### 8. **insert_more_teachers.sql**
   - Inserts more entries into the `teachers` table.

### 9. **insert_records.sql**
   - Contains `INSERT INTO` statements to add initial records to the tables within the `school_db` database.

### 10. **min_max.sql**
   - Demonstrates how to use the `MIN()` and `MAX()` functions to find the minimum and maximum values in a dataset.

### 11. **querying+related+data.sql**
   - Provides SQL queries to retrieve related data from multiple tables using JOINs and foreign keys.

### 12. **school_db2.sql**
   - An alternate or additional script related to the structure and data of the `school_db` database.

### 13. **select_records.sql**
   - Demonstrates the use of the `SELECT` statement to retrieve specific data from tables.

### 14. **sum_sql.sql**
   - Contains SQL queries utilizing the `SUM()` function to calculate the total sum of values from a specific column.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Chakridhar2555/sql-learning-project.git

Execute the SQL scripts in your preferred SQL environment (MySQL, PostgreSQL, etc.) using a command-line tool or database management system (e.g., MySQL Workbench).

For example, to execute create_school_db.sql, use:

sql
Copy code
source create_school_db.sql;
