# 📊 Retail Sales Analysis (SQL Project)

## 📌 Project Overview

This project analyzes retail transaction data using SQL to uncover key patterns in revenue, customer behavior, product performance, and returns.

The goal is to transform raw transactional data into meaningful business insights.

---

## 🗂️ Dataset Information

The dataset contains the following fields:

* InvoiceNo → Unique invoice number
* StockCode → Product code
* Description → Product name
* Quantity → Number of items purchased
* InvoiceDate → Date of transaction
* UnitPrice → Price per item
* CustomerID → Unique customer ID
* Country → Customer location

---

## 🧹 Data Cleaning

* Removed cancelled transactions (`InvoiceNo LIKE 'C%'`)
* Filtered only valid sales (`Quantity > 0`)
* Excluded missing customer IDs where necessary

---

## 📊 Analysis Performed

### 1. Revenue Analysis

* Total revenue calculation
* Revenue by country
* Monthly revenue trends

### 2. Customer Analysis

* Top customers by revenue
* Repeat vs one-time customers

### 3. Product Analysis

* Best-selling products
* Product performance over time

### 4. Returns Analysis

* Total number of returns
* Most returned products

### 5. Order Analysis

* Order-level revenue
* Average order value

---

## 🧠 Key Insights

* Revenue is highly concentrated in a few countries → potential market dependency
* A small group of customers contributes a large share of revenue → customer concentration risk
* Sales show monthly fluctuations → presence of seasonality
* Certain products have high return rates → possible quality or expectation mismatch
* Repeat customers exist but can be further leveraged for retention strategies

---

## 💡 Recommendations

* Diversify revenue across multiple countries to reduce risk
* Focus on retaining high-value customers
* Investigate products with high return rates
* Use seasonal trends for better inventory and marketing planning
* Promote top-performing products to maximize revenue

---

## 🛠️ Tools Used

* SQL (PostgreSQL) for data analysis

---

## 📁 Project Files

* `retail.sql` → All SQL queries used for analysis
* `README.md` → Project documentation

---

## 🚀 Conclusion

This project demonstrates how SQL can be used to analyze transactional data and generate actionable business insights.
