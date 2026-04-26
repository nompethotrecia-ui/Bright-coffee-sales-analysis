

# ☕ Bright Coffee Shop Sales Analytics

## 📌 Introduction

This project analyzes transactional data from the *Bright Coffee Shop* to support the new CEO’s mission of increasing revenue and improving product performance. As a Junior Data Analyst, the goal was to transform raw sales data into meaningful insights that inform strategic decision-making.


## Problem Statement

Bright Coffee Shop lacks clear visibility into which products drive revenue, when peak sales occur, and how product performance varies over time. Without these insights, it is difficult to optimize sales strategies and maximize profitability.


## Aim of the Project

To analyze historical sales data and generate actionable insights on product performance, revenue trends, and customer purchasing behavior.


## Objectives

* Identify top revenue-generating products
* Analyze sales performance across different times of the day
* Evaluate trends in product categories and transaction volumes
* Provide data-driven recommendations to improve sales performance


## Data Architecture & Flow

* **Data Source:** Excel dataset (daily transactions)
* **Processing (ETL):**

  * Converted Excel data to CSV
  * Loaded data into Databricks
  * Cleaned and transformed data using SQL
* **Storage:** Databricks environment
* **Analysis & Visualization:** Excel dashboards and charts


## Key Insights

* A small number of products generate the majority of total revenue
* Coffee products dominate sales, followed by tea and bakery items
* Sales peak during specific time intervals, indicating strong time-based demand
* Certain store locations outperform others in revenue generation
* Some products consistently underperform, presenting opportunities for improvement


##  Key Calculations

* **Total Revenue:** `unit_price × transaction_qty`
* Grouping transactions into **time intervals (e.g., 30-minute or hourly buckets)**
* Total units sold by **product category and product type**


## Data Processing Steps

* Converted dataset from Excel to CSV format
* Loaded data into Databricks for processing
* Cleaned data (e.g., corrected unit price formatting)
* Created new fields such as:

  * `transaction_time_bucket`
  * `total_amount`
* Used SQL queries to aggregate and analyze sales by product and time intervals


## Visualization & Reporting

* Exported processed data to Excel
* Built dashboards and pivot tables showing:

  * Revenue per product category
  * Peak sales time intervals
  * Quantity sold per product
  * Best-selling items
* Used charts and visuals to communicate insights effectively


## Summary of Results

* Revenue is highly concentrated in a few best-selling products
* Peak sales occur during specific times of the day
* Coffee is the leading category in both revenue and quantity sold
* Underperforming products and slow periods highlight opportunities for targeted interventions


## Recommendations

* Run marketing campaigns during slow time periods (e.g., discounts, promotions)
* Increase stock levels for high-demand products
* Bundle or promote underperforming items
* Improve in-store visibility of less popular products


## Next Steps

* Automate daily sales reporting using dashboards
* Expand analysis across multiple store locations
* Implement customer loyalty programs based on peak buying times
* Integrate real-time analytics for better decision-making


## Tools Used

* **SQL (Databricks)** – Data transformation and analysis
* **Excel** – Data cleaning, pivot tables, and dashboards
* **Miro** – Data architecture and planning



