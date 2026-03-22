# ✈️ Airline Data Analysis (SQL)

## 📌 Project Overview  
This project involves analyzing an airline database to extract insights related to bookings, flights, and passenger behavior. The dataset includes multiple relational tables such as bookings, tickets, flights, boarding passes, and airports.

The schema consists of interconnected tables like Bookings, Tickets, Ticket_flights, Flights, and Boarding_passes. This required extensive use of joins, aggregations, and window functions to solve real-world business queries.

---

## 🧠 Approach & Methodology

- Understood table relationships using ER diagram  
- Performed INNER JOIN & LEFT JOIN to combine multiple tables  
- Used aggregation functions (SUM, COUNT) for analysis  
- Applied window functions (RANK, ROW_NUMBER) for ranking problems  
- Used date formatting and filtering for time-based analysis  

---

## 🔍 Problem Statements & Solutions

---

### 🔹 1. Tickets Without Boarding Passes  

**Problem:**  
Find how many tickets do not have boarding passes.

**Approach:**  
Used LEFT JOIN between tickets and boarding_passes and filtered NULL values to identify missing records.

---

### 🔹 2. Format Booking Date  

**Problem:**  
Convert book_date into yyyy-mm-dd format and display total amount.

**Approach:**  
Used date formatting functions to standardize the date output and ensure consistency.

---

### 🔹 3. Most Popular Product per Store  

**Problem:**  
Identify the most popular product in each store based on quantity sold.

**Approach:**  
Used window function (RANK) partitioned by store to identify top-performing products.

---

### 🔹 4. Quarterly Sales Performance  

**Problem:**  
Calculate total sales per store per quarter and rank performance.

**Approach:**  
Extracted year and quarter from date, aggregated total sales, and applied ranking to compare store performance.

---

### 🔹 5. Rank Airports by Flights  

**Problem:**  
Rank airports based on number of departing flights.

**Approach:**  
Grouped flights by departure airport, calculated total flights, and applied ranking to identify busiest airports.

---

## 📊 Key Learnings

- Strong understanding of SQL joins across multiple tables  
- Hands-on experience with window functions for ranking and analysis  
- Ability to convert business problems into SQL queries  
- Experience working with relational datasets  

---

## 🚀 Outcome

Successfully analyzed airline operations data to extract insights on bookings, flights, and performance trends, demonstrating strong SQL and analytical skills.
