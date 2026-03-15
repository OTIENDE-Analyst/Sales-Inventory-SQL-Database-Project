## Sales-Inventory SQL Database Project
This project demonstrates the design and querying of a relational Sales-Inventory Management Database using SQL. The database simulates a retail environment where customer information, product details, Inventory records and sales transactions are stored and analyzed.

# Database Structure
The database contains four main tables:
1. Customers table - stores customer information.
2. Products table - stores products details
3. Inventory table - tracks stock quantities for each product.
4. Sales table - has records of sales and transactions between customers and products.

All tables are created within the __assignment__ schema and are connected using __primary keys and foreign keys__ to maintain relational integrity.

# Table Relationships
Customers - Sales:One to many

Products - Sales: One to Many

Products - Inventory : One to One

# Project Tasks
The SQL script performs the following tasks:
1. Creates a database schema named __assignment__
2. Creating the tables; Customers, Products, Inventory and Sales table.
3. Inserting values into all the tables.
4. Querying the database to retrieve and analyse the data.

# SQL Concepts Demonstrated
This project incorporates several SQL concepts including:
1. Aggregate function like COUNT(), SUM(), MAX(), MIN(), AVG()
2. SQL Operators;
3. SQL Joins
4. Subqueries 
5. SQL Window functions
6. Common Table Expresions in SQL (CTEs)
7. Advanced Analytical and Window functions analysis.

# Tools used
1. PostgreSQL
2. DBeaver

