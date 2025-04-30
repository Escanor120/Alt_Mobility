# Alt Mobility - Data Analyst Intern Assignment

This repository contains the SQL queries and analysis for the Alt Mobility Data Analyst Internship assignment. The goal was to derive insights from customer order and payment data, and create meaningful reports and visualizations for internal decision-making.

---

## 📁 Dataset Overview

**Files Used:**
- `customer_orders.csv` — contains order-level information (order date, amount, status, customer ID).
- `payments.csv` — contains payment-level information (payment date, status, amount).

---

## ✅ Task-wise SQL Approach

### 1. Order and Sales Analysis

- Counted total orders by each order status.
- Calculated revenue from completed orders.
- Created a month-wise revenue trend to highlight seasonality or growth.
- Computed fulfillment rate by comparing completed vs total orders.

### 2. Customer Analysis

- Identified repeat customers (those who placed more than one order).
- Segmented customers into:
  - One-time buyers
  - Repeat buyers (2–5 orders)
  - Loyal customers (>5 orders)
- Compared new vs returning customers over months.
- Tracked active customers each month using distinct customer counts.

### 3. Payment Status Analysis

- Analyzed payment success/failure volumes and amounts.
- Measured failure rate across all transactions.
- Tracked monthly trend of successful vs failed payments.
- Found orders without any successful payments (potential revenue leaks).

### 4. Order Details Report

- Merged customer order data with payment info.
- Produced a detailed report including order and payment statuses, dates, and amounts.
- Summarized key business metrics:
  - Total orders, total revenue
  - Payment success rate
  - Average delay between order and payment

---

## 📊 Visualization

A cohort-based customer retention analysis was done using Python.
- Customers were grouped by the month of their first order.
- The percentage of retained customers was plotted across subsequent months.
- A heatmap was generated to visually represent customer loyalty over time.

_You can find the heatmap image in the repository ('VISUALIZATION.pdf')._

---

## 🛠️ Tools Used

- SQL (MySQL / PostgreSQL-style)
- Python (Pandas, Seaborn, Matplotlib)
- Data cleaning and transformation using Pandas
- Visualization using heatmap for retention tracking

---

## 📌 Notes

- All queries are optimized for readability and logic clarity.
- Edge cases like missing payments or cancelled orders were considered in the analysis.
- No external libraries or dashboards were used for SQL tasks.

---

## 📬 Contact

For any queries or walkthrough of the analysis, feel free to reach out.
