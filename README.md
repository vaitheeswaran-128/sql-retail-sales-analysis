# Sales Data Analysis using SQL

## Project Overview
This project analyzes retail sales data using SQL. The dataset contains order and transaction details, which are used to generate insights about sales performance, customer behavior, and profitability.

The analysis includes data cleaning, joins, aggregations, and window functions to answer business questions.

## Database Structure

Two tables were used:

### Orderss Table
- OrderID
- Order Date
- CustomerName
- City
- State

### Details Table
- OrderID
- Category
- Sub-Category
- Amount
- Profit
- Quantity
- PaymentMode

## Data Cleaning
- Renamed inconsistent column names
- Converted date format
- Updated negative profit values
- Standardized column naming

## Key SQL Concepts Used
- JOIN operations
- Aggregate functions (SUM, COUNT, AVG)
- GROUP BY
- Window functions (RANK)
- Subqueries
- Date functions

## Business Analysis Performed

### 1. Total Sales per City
Identifies cities generating the highest revenue.

### 2. Total Profit per Customer
Finds the most profitable customers.

### 3. Order Count and Revenue per State
Analyzes order volume and revenue by state.

### 4. Category-wise Revenue per Payment Mode
Shows payment behavior across product categories.

### 5. Customers with Profit Above Average
Identifies high-value customers.

### 6. Top City by Revenue in Each State
Uses window functions to find the best-performing city in each state.

### 7. Orders with Maximum Quantity
Finds orders with the highest purchase quantity.

### 8. Most Common Sub-Category per Category
Analyzes popular sub-categories.

### 9. Weekly Order Trends
Tracks how order volume changes weekly.

### 10. Weekend vs Weekday Orders
Analyzes customer purchase patterns.

### 11. Quarterly Sales Analysis
Identifies orders placed in the last quarter.

### 12. Yearly Sales per City
Analyzes sales trends across years.

## Tools Used
- MySQL
- MySQL Workbench
- SQL

## Skills Demonstrated
- SQL Query Writing
- Data Cleaning
- Data Aggregation
- Window Functions


