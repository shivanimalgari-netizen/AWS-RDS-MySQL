# AWS RDS MySQL Assignment

## 📌 Title
Creating and Connecting to an AWS RDS MySQL Database Using MySQL Workbench

---

## 🎯 Objective
To create a MySQL database using AWS RDS and connect it using MySQL Workbench, and perform basic SQL operations.

---

## 🛠️ Tools Used
- AWS RDS
- MySQL Workbench
- SQL

---

## 📚 Steps Performed

1. Opened AWS RDS service  
2. Created a MySQL database instance  
3. Configured credentials and connectivity settings  
4. Enabled public access and security group rules  
5. Connected to the database using MySQL Workbench  
6. Created a database (`myproject`)  
7. Created a table (`students`)  
8. Inserted data into the table  
9. Retrieved data using SELECT query  

---

## 💻 SQL Queries Used

`sql
SHOW DATABASES;

CREATE DATABASE myproject;

USE myproject;

CREATE TABLE students (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    age INT
);

INSERT INTO students VALUES (1, 'Sindhu', 20);

SELECT * FROM students;
##
[click here to see video](https://www.youtube.com/watch?v=NC5zmQvaqvQ)
