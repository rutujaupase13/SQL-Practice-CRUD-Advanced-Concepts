This repository contains a complete SQL practice project that covers almost all concepts commonly asked in company assessments and interviews.
I created this mini project to revise SQL fundamentals, understand relational database design, and practice real-world queries.
The project includes:
Database schema
Sample data
CRUD operations
Joins
Aggregations
Group By & Having
Subqueries
Functions
Views
Stored Procedures
Triggers
Indexes
Case statements
Everything is organized into separate files so anyone can learn and practice step-by-step.

📌 1. Project Overview
The project uses a small database named company_db, which contains three simple tables:
employees – stores employee details
departments – stores department information
projects – stores project assignments of employees
This structure is enough to practice basic as well as advanced SQL concepts.

📌 2. Database Schema
The schema includes:
Primary keys
Foreign keys
Unique constraints
Data types
Relationships between tables

With this schema, you can practice joins, subqueries, and relational operations easily.

📌 3. Sample Data

Each table includes real-looking sample data.
The data is kept simple so that it is easy to understand patterns and write queries quickly.
Example data includes:

Employee names

Email IDs

Department assignments

Salary values

Join dates

Projects assigned to employees

This helps in writing meaningful queries instead of random numbers.

📌 4. CRUD Operations
CRUD stands for:

Create → insert new records

Read → fetch existing records

Update → modify records

Delete → remove records

These operations form the base of SQL and are used in every database application.
The file 03_crud.sql includes clear examples for all four operations.

📌 5. Joins

The project contains different joins:

Inner Join

Left Join

Multi-table Join

Joins help combine data from multiple tables based on relationships.
This is one of the most asked topics in SQL interviews.

📌 6. Aggregations

Here I practiced functions like:

COUNT()

SUM()

AVG()

MAX()

MIN()

These are helpful when calculating totals, averages, or summary reports.

📌 7. Group By & Having

GROUP BY is used for grouping data, and
HAVING is used to filter groups.

This is especially useful for analytical queries like:

Department-wise average salary

Employee count per department

📌 8. Subqueries
Subqueries allow writing queries inside other queries.
They are widely used in:

Filtering

Comparing values

Reporting

This project includes both simple and nested subquery examples.

📌 9. SQL Functions

The project includes examples of:

String functions (UPPER, LOWER)

Date functions (YEAR, MONTH)

Mathematical functions

These functions help transform or calculate data.

📌 10. Views
A view is a virtual table created using a query.
It is very helpful for:

Simplifying complex joins

Providing secure access

Reusing frequently used queries

The repo includes a sample view combining employee, department, and salary information.

📌 11. Stored Procedure
Stored procedures allow storing a query as a reusable block.
They help improve:

Performance

Reusability

Security

This project contains a simple stored procedure to fetch employee details by ID.

📌 12. Trigger
A trigger automatically runs when a specific action happens (INSERT, UPDATE, DELETE).
Triggers are used for:

Logging

Validations

Automatic updates

This project includes a trigger that logs salary changes.

📌 13. Indexes
Indexes make searching faster.
An index on the email column demonstrates how indexing can improve query performance.

📌 14. Case Expression
CASE helps apply conditional logic inside SQL queries.
Example: Categorizing employees as High, Medium, or Low salary group.

📌 15. Repository Structure
sql-practice-crud-and-advanced-concepts/
│
├── 01_schema.sql
├── 02_insert_data.sql
├── 03_crud.sql
├── 04_joins.sql
├── 05_groupby_having.sql
├── 06_subqueries.sql
├── 07_functions.sql
├── 08_views.sql
├── 09_stored_procedure.sql
├── 10_triggers.sql
├── 11_indexes.sql
├── README.md

📌 16. Purpose of This Project
This mini project is designed to help in:

Technical interviews

SQL assessments

Database understanding

Revision before placements

Practical hands-on SQL skill building

Companies often ask real-world SQL scenarios during hiring, and this repo covers nearly all of them.

📌 17. How to Use This Repository
Create the database

Run the schema file

Insert sample data

Execute each SQL file one by one

Modify queries to practice more

You can also add your own data to deepen your understanding.
