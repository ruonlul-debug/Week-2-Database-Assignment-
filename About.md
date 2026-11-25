Week 2 Assignment: Introduction to SQL
Description
Assignment Overview

This week, we covered the fundamentals of SQL and learned how to retrieve and manipulate data from a database using basic SQL queries.

For this assignment, you will work with the sales database and apply the concepts covered during the week, including:

Selecting specific columns from a table
Filtering records using WHERE
Sorting results using ORDER BY
Limiting query results using LIMIT
Retrieving data from different tables
Database Setup

Before starting the assignment, you must have the sales database, including its data, available on your computer.

If You Already Have the sales Database

You can proceed directly with the assignment.

To confirm that the database exists, run:

SHOW DATABASES;


Then select the database:

USE sales;
If You Do Not Have the sales Database

You must import the database before starting the assignment.

Database and Import Resources:
CLICK HERE: Week 2 Database Assignment 

Please watch the provided video on how to import the database before proceeding. The database and its data are required to complete this assignment.
Assignment Questions

Write an SQL query for each of the following questions.

Question 1: Retrieve Payment Information

Write an SQL query to retrieve the following columns from the payments table:

checkNumber
paymentDate
amount
Question 2: Find Orders in Process

Write an SQL query to retrieve the following columns from the orders table:

orderDate
requiredDate
status

Only retrieve orders whose status is In Process.

Sort the results by orderDate in descending order.

Question 3: Find Sales Representatives

Write an SQL query to retrieve the following columns from the employees table:

firstName
lastName
email

Only retrieve employees whose job title is Sales Rep.

Sort the results by employeeNumber in descending order.

Question 4: Retrieve Office Information

Write an SQL query to retrieve all columns and all records from the offices table.

Question 5: Retrieve the Five Cheapest Products

Write an SQL query to retrieve the following columns from the products table:

productName
quantityInStock

Sort the results by buyPrice in ascending order and limit the output to 5 records.