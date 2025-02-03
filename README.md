# 📚 SQL Bookstore Project

![GitHub repo size](https://img.shields.io/github/repo-size/your-username/SQL-Bookstore-Project)
![GitHub contributors](https://img.shields.io/github/contributors/your-username/SQL-Bookstore-Project)
![GitHub stars](https://img.shields.io/github/stars/your-username/SQL-Bookstore-Project?style=social)

## 📌 Project Overview
This project is a **SQL-based Bookstore Database** where I solve **10 SQL queries** related to book management. It includes:
✅ A structured **dataset**
✅ **Query solutions**
✅ Interactive SQL operations

## 📂 Table of Contents
- [Dataset Description](#dataset-description)
- [Queries Solved](#queries-solved)
- [Installation & Setup](#installation--setup)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

---

## 📊 Dataset Description
The dataset contains information about books, authors, sales, and customers in a bookstore.

### Sample Schema:
```sql
CREATE TABLE Books (
    Book_ID INT PRIMARY KEY,
    Title VARCHAR(255),
    Author VARCHAR(255),
    Genre VARCHAR(100),
    Price DECIMAL(10,2),
    Published_Date DATE
);
```

---

## 🔍 Queries Solved
1. Find the **total number of books sold**.
2. Retrieve the **top-selling book**.
3. Calculate the **average price of books per genre**.
4. List the **authors with the most books**.
5. Find **customers who purchased the most books**.
6. Identify the **most popular book genre**.
7. Calculate the **total revenue per author**.
8. Find the **oldest published book**.
9. Count the **total number of books available**.
10. Group books by **year and count publications**.

🔹 **Full query solutions are included in the [Solution PDF](./SQL_Queries_Solved.pdf)**

---

## ⚡ Installation & Setup
1️⃣ Clone this repository:
```bash
git clone https://github.com/your-username/SQL-Bookstore-Project.git
```
2️⃣ Open the SQL file and load the dataset:
```sql
SOURCE bookstore_dataset.sql;
```
3️⃣ Run the queries from the **solution PDF**.

---

## 🚀 How to Use
- Use **MySQL**, **PostgreSQL**, or **SQLite** to run the queries.
- Open the **dataset file** and load it into your SQL environment.
- Run the queries and analyze the results.

---

## 🤝 Contributing
Want to contribute? Feel free to **fork** this repo and submit **pull requests**!

---

## 📜 License
This project is licensed under the **MIT License**.

---

💡 *If you find this project helpful, don't forget to leave a ⭐ on GitHub!*
