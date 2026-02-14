☕ Coffee Vending Machine Sales Analysis & Forecasting (Power BI)
📌 Project Overview

This project analyzes 149,116 real-world coffee vending machine transactions to uncover purchasing patterns, sales trends, peak demand periods, and store performance.

The dashboard was built in Power BI using DAX measures, time-series analysis, and forecasting to generate actionable business insights.

📊 Dataset Description

The dataset contains transaction-level sales data with the following columns:

Column	Description
transaction_id	Unique transaction number
transaction_date	Date of purchase
transaction_time	Time of purchase
transaction_qty	Quantity purchased
store_id	Store identifier
store_location	Store location
product_id	Product identifier
unit_price	Price per unit
product_category	Product category
product_type	Type of coffee
product_detail	Specific product name

Total Records: 149,116

Data Type: Transaction-level

Time-based dataset (ideal for time-series analysis)

🎯 Business Objectives

Analyze daily, monthly, and weekday sales trends

Identify peak sales hours

Evaluate product performance

Compare store and location performance

Forecast next 7 days of sales

Generate business insights for decision-making

🛠 Tools & Technologies Used

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query (Data Cleaning & Transformation)

Time-Series Analysis

Forecasting (Power BI Analytics Pane)

📈 Dashboard Pages
1️⃣ Sales Overview

Total Sales

Total Orders

Total Quantity

Average Order Value

Daily Sales Trend

Monthly Sales Trend

Weekday Sales Analysis

2️⃣ Product Performance

Sales by Product Category

Quantity by Product Type

Top Selling Products

Sales Contribution %

3️⃣ Store & Location Analysis

Sales by Store Location

Store-wise Order Count

Location Performance Comparison

4️⃣ Time-Based Insights & Forecasting

Sales Forecast (Next 7 Days)

Peak Sales Hours

Weekday Sales Trend

Forecast Confidence Interval: 95%

📊 Key Insights

Sales peak during morning and evening hours

Weekends generate higher revenue

A few product categories dominate total sales

Some store locations significantly outperform others

Sales show consistent time-based patterns suitable for short-term forecasting

🧮 Key DAX Measures

Example measures used:

Total Sales Amount = SUM('Coffee Sales'[Total Sales])

Total Orders = COUNT('Coffee Sales'[transaction_id])

Average Order Value = 
DIVIDE([Total Sales Amount], [Total Orders])


Additional measures include:

Cumulative Sales

Sales Contribution %

Time-based aggregations

Hourly Sales Analysis

🔮 Forecasting Approach

Power BI’s built-in forecasting model was used:

Forecast Length: 7 Days

Confidence Interval: 95%

Based on historical time-series trend

📷 Dashboard Preview

(Add screenshots here)

Example:

/screenshots/sales_overview.png
/screenshots/product_analysis.png
/screenshots/forecast_page.png

🚀 How to Use

Download the .pbix file

Open in Power BI Desktop

Refresh data if needed

Interact using slicers and filters

📌 Project Highlights

✔ Clean data modeling
✔ Custom Date Table
✔ Advanced DAX Measures
✔ Time-Series Visualization
✔ Sales Forecasting
✔ Business-Oriented Insights

🎓 What This Project Demonstrates

Strong understanding of business analytics

Time-series data handling

KPI development

Data storytelling

Dashboard design best practices

Forecasting for decision support
