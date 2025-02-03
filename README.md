README - Books Database

Table of Contents

Overview

Database Schema

Books Table

Customers Table

Orders Table

Relationships

Usage Instructions

SQL Solution File

Overview

This project consists of three CSV files representing a database for a bookstore's operations. The database includes information about books, customers, and orders. The data is structured into three tables: Books, Customers, and Orders.

Database Schema

1. Books Table (Books.csv)

This table stores information about books available in the bookstore.

Column Name

Data Type

Description

Book_ID

INT (PK)

Unique identifier for each book.

Title

VARCHAR

The title of the book.

Author

VARCHAR

The author of the book.

Genre

VARCHAR

The genre of the book.

Published_Year

YEAR

The year the book was published.

Price

DECIMAL

The price of the book.

Stock

INT

Number of copies available.

2. Customers Table (Customers_1.csv)

This table contains customer details.

Column Name

Data Type

Description

Customer_ID

INT (PK)

Unique identifier for each customer.

Name

VARCHAR

Full name of the customer.

Email

VARCHAR

Email address of the customer.

Phone

VARCHAR

Contact number of the customer.

City

VARCHAR

City of residence.

Country

VARCHAR

Country of residence.

3. Orders Table (Orders_1.csv)

This table tracks customer orders and references books and customers.

Column Name

Data Type

Description

Order_ID

INT (PK)

Unique identifier for each order.

Customer_ID

INT (FK)

References Customers.Customer_ID.

Book_ID

INT (FK)

References Books.Book_ID.

Order_Date

DATE

Date when the order was placed.

Quantity

INT

Number of books ordered.

Total_Amount

DECIMAL

Total amount for the order (Quantity * Price).

Relationships

The database maintains the following relationships:

The Orders table references the Books table through the Book_ID column.

The Orders table references the Customers table through the Customer_ID column.

Usage Instructions

Create the Database and Tables: Execute the SQL script to create the tables.

Import Data: Load the provided CSV files into their respective tables.

Run Queries: Perform various queries to analyze book sales, customer orders, and stock levels.

SQL Solution File

A separate SQL script (solution.sql) is provided, which includes:

Table creation statements

Insert statements for loading sample data

Queries to analyze and retrieve data

