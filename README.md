README - Books Database

Overview

This project consists of three CSV files representing a database for a bookstore's operations. The database includes information about books, customers, and orders. The data is structured into three tables: Books, Customers, and Orders.

Database Schema

1. Books Table (Books.csv)

Book_ID (INT, PRIMARY KEY) - Unique identifier for each book.

Title (VARCHAR) - The title of the book.

Author (VARCHAR) - The author of the book.

Genre (VARCHAR) - The genre of the book.

Published_Year (YEAR) - The year the book was published.

Price (DECIMAL) - The price of the book.

Stock (INT) - Number of copies available.

2. Customers Table (Customers_1.csv)

Customer_ID (INT, PRIMARY KEY) - Unique identifier for each customer.

Name (VARCHAR) - Full name of the customer.

Email (VARCHAR) - Email address of the customer.

Phone (VARCHAR) - Contact number of the customer.

City (VARCHAR) - City of residence.

Country (VARCHAR) - Country of residence.

3. Orders Table (Orders_1.csv)

Order_ID (INT, PRIMARY KEY) - Unique identifier for each order.

Customer_ID (INT, FOREIGN KEY) - References Customers.Customer_ID.

Book_ID (INT, FOREIGN KEY) - References Books.Book_ID.

Order_Date (DATE) - Date when the order was placed.

Quantity (INT) - Number of books ordered.

Total_Amount (DECIMAL) - Total amount for the order (Quantity * Price).

Relationships

Orders references Books through Book_ID.

Orders references Customers through Customer_ID.

Usage

Create the database and tables using the SQL script.

Import the CSV data into the respective tables.

Run queries to retrieve book sales, customer orders, stock levels, etc.

SQL Solution File

A separate SQL script (solution.sql) is provided to create tables and insert data.


