#  Music Store Data Analysis using SQL

##  Project Overview

This project analyzes a digital music store database using SQL to answer real-world business questions. The analysis focuses on customer purchasing behavior, sales performance, artist popularity, music genres, and geographical trends. By writing optimized SQL queries, the project demonstrates how relational databases can be used to extract actionable business insights.

The project covers fundamental and advanced SQL concepts including joins, aggregate functions, Common Table Expressions (CTEs), window functions, ranking, grouping, and subqueries.

---

##  Database

**Database Name:** MusicDB

The database contains multiple related tables, including:

* Employee
* Customer
* Invoice
* Invoice_Line
* Track
* Album
* Album2
* Artist
* Genre

These tables represent a digital music store where customers purchase music tracks from various artists and genres.

---

##  Project Objectives

The primary objectives of this project are to:

* Analyze customer purchasing behavior.
* Identify top-performing artists and genres.
* Measure sales across countries and cities.
* Discover high-value customers.
* Practice advanced SQL querying techniques.
* Generate business insights from relational data.

---

##  Technologies Used

* Microsoft SQL Server
* SQL
* Relational Database Management System (RDBMS)

---

##  Business Questions Solved

### Employee Analysis

* Find the most senior employee based on job title.

---

### Sales Analysis

* Determine which countries generate the highest number of invoices.
* Identify the top three highest invoice values.
* Find the city with the highest total sales for promotional opportunities.

---

### Customer Analysis

* Identify the customer who has spent the most money.
* Calculate total spending by each customer on every artist.
* Identify the top-spending customer in every country.

---

### Music Preference Analysis

* Find customers who purchase Rock music.
* Identify the Top 10 Rock artists based on purchase count.
* Determine the most popular music genre for each country.

---

### Track Analysis

* Find tracks that are longer than the average song duration.

---

##  SQL Concepts Demonstrated

* SELECT Statements
* Filtering with WHERE
* ORDER BY
* GROUP BY
* Aggregate Functions

  * COUNT()
  * SUM()
  * AVG()
* INNER JOIN
* DISTINCT
* Common Table Expressions (CTEs)
* UNION ALL
* Window Functions

  * ROW_NUMBER()
  * RANK()
* Subqueries
* Aliasing
* String Concatenation

---

##  Key Business Insights

The SQL queries help answer important business questions such as:

* Which countries contribute the highest sales?
* Which customers generate the most revenue?
* Which artists are the most popular?
* Which music genres dominate different countries?
* Which city would be the best location for marketing campaigns?
* How customer spending varies across artists and countries.

---

##  How to Run

1. Create a new SQL database.

```sql id="k0t2ju"
CREATE DATABASE MusicDB;
```

2. Import the Music Store dataset into the database.

3. Open the SQL script.

4. Execute the queries individually or run the entire script.

---

##  Learning Outcomes

Through this project, I gained practical experience in:

* Writing complex SQL queries
* Working with relational databases
* Joining multiple tables
* Performing business-oriented data analysis
* Using Common Table Expressions (CTEs)
* Applying Window Functions
* Solving analytical business problems using SQL
* Generating actionable insights from transactional data

---

##  Future Improvements

* Build an interactive Power BI dashboard using this database.
* Create SQL stored procedures for reusable analysis.
* Develop views for reporting.
* Optimize query performance with indexing.
* Perform time-series sales analysis.

---

##  Author

**Salvin Thomas**

MBA Business Analytics Student

Learning Data Analytics | SQL | Python | R | Power BI | Tableau

---

## ⭐ If you found this project useful, feel free to star the repository!
