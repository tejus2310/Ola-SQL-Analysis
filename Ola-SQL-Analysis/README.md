# 🚖 Ola Booking Data Analysis using SQL

A comprehensive SQL project designed to analyze Ola booking data and answer real-world business questions using SQL queries. This project demonstrates proficiency in data retrieval, aggregation, filtering, grouping, and analytical SQL techniques.

> 📂 **Dataset:** 49 bookings × 20 columns · 🛢️ **Engine:** MySQL · ✅ **10 business questions answered**

---

## 📌 Project Overview

This project uses SQL to analyze Ola ride booking data and generate actionable business insights. The queries cover booking performance, customer behavior, payment methods, vehicle analysis, ride cancellations, ratings, and booking value.

The project showcases SQL skills commonly required for **Data Analyst**, **Business Analyst**, and **SQL Developer** roles.

---

## 🎯 Objectives

- Analyze ride booking performance
- Identify customer booking trends
- Measure vehicle performance
- Evaluate cancellation reasons
- Analyze customer and driver ratings
- Calculate revenue-related metrics
- Practice real-world SQL queries

---

## 🛠️ Technologies Used

- MySQL
- SQL
- Relational Database

---

## 📁 Repository Structure

```
Ola-SQL-Analysis/
│
├── Ola project.sql            # All 10 analysis queries
├── Dataset/
│   └── ola_bookings.csv       # Source dataset (49 rows)
├── README.md
└── LICENSE
```

---

## 📊 Database

**Database Name**
```sql
ola
```

**Main Table**
```sql
bookings
```

---

## 📋 SQL Queries & Results

The queries in [`Ola project.sql`](Ola%20project.sql) solve the following business problems. Results shown were produced by running the queries on the sample dataset.

### 1. Retrieve all successful bookings
Returns every completed booking → **33 successful bookings**.

### 2. Average ride distance for each vehicle type
| Vehicle Type | Avg Distance (km) |
|---|---|
| Mini | 24.14 |
| eBike | 21.63 |
| Prime Sedan | 20.00 |
| Prime Plus | 16.80 |
| Bike | 16.71 |
| Prime SUV | 15.57 |
| Auto | 1.67 |

### 3. Count rides cancelled by customers
**3 bookings** were cancelled by customers.

### 4. Identify the Top 5 customers
Retrieves the customers with the highest number of rides (ranked with `ORDER BY … LIMIT 5`).

### 5. Driver cancellations due to personal or vehicle issues
Counts rides cancelled with the reason *"Personal & Car related issue"*.

### 6. Maximum and minimum driver ratings (Prime Sedan)
**Max = 4.3**, **Min = 3.2**

### 7. Retrieve rides paid using UPI
**13 rides** were paid via UPI.

### 8. Average customer rating by vehicle type
| Vehicle Type | Avg Customer Rating |
|---|---|
| Auto | 4.65 |
| Prime SUV | 4.18 |
| eBike | 4.16 |
| Bike | 3.90 |
| Prime Plus | 3.73 |
| Mini | 3.64 |
| Prime Sedan | 3.43 |

### 9. Total booking value of successful rides
**₹18,208** total revenue from successful bookings.

### 10. Retrieve incomplete rides and their reasons
Lists each incomplete ride with its `Incomplete_Rides_Reason`.

---

## 💡 Key Insights

- **67%** of bookings were completed successfully (33 of 49).
- **Mini** covers the longest average trips; **Auto** the shortest.
- **Auto** and **Prime SUV** earn the **highest customer ratings**.
- **UPI** is a widely used digital payment method (13 rides).
- Successful rides generated **₹18,208** in booking value.

---

## 📈 SQL Concepts Used

`SELECT` · `WHERE` · `GROUP BY` · `ORDER BY` · `COUNT()` · `SUM()` · `AVG()` · `MAX()` · `MIN()` · `LIMIT` · Aggregate Functions · Filtering · Sorting · Data Analysis

---

## 📌 Business Questions Answered

- How many bookings were successfully completed?
- What is the average ride distance for each vehicle type?
- How many rides were cancelled by customers?
- Which customers book the most rides?
- Why are drivers cancelling rides?
- Which vehicle type has the highest customer ratings?
- How much revenue was generated from successful bookings?
- Which rides were paid through UPI?
- Which rides remained incomplete, and why?

---

## ▶️ How to Run

1. Create the database and table:
   ```sql
   CREATE DATABASE ola;
   USE ola;
   ```
2. Import `Dataset/ola_bookings.csv` into a table named **`bookings`**
   (MySQL Workbench → Table Data Import Wizard).
3. Open and run [`Ola project.sql`](Ola%20project.sql) — each query is labelled with the business question it answers.

---

## 📚 Learning Outcomes

Through this project, I practiced:

- Writing analytical SQL queries
- Using aggregate functions
- Grouping and summarizing data
- Solving real-world business problems
- Extracting insights from structured datasets
- Working with relational databases

---

## 🚀 Future Improvements

- Advanced SQL using Window Functions
- Common Table Expressions (CTEs)
- Stored Procedures & SQL Views
- Index optimization
- A Power BI dashboard on the same dataset
- Exploratory Data Analysis (EDA)

---

## 👨‍💻 Author

**Tejus Pandey**

- 💼 LinkedIn: https://www.linkedin.com/in/tejuspandey
- 🐙 GitHub: https://github.com/tejus23

---

## ⭐ If you found this project useful, consider giving it a star!
