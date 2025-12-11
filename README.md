📊 Amazon Sales Data Analysis 

📁 Project Overview

This project analyzes Amazon Sales Data using Power BI to uncover key business insights such as revenue trends, product performance, regional distribution of sales, and order fulfillment patterns.
The dataset used includes 10,000+ sales records, containing information about products, prices, orders, shipping details, and customer segments.

The goal of this project is to build a clear, interactive dashboard that helps stakeholders:

Monitor sales performance

Identify top-selling products and categories

Track order and shipping trends

Understand customer buying behavior

📂 Files Included
File Name	Description
Amazon Sales Data.pbix	Power BI dashboard containing data cleaning, modeling, and visualizations
amazon_sales_dataset_10000.csv	Raw dataset used for analysis
🧽 Data Cleaning & Preprocessing

Performed inside Power BI Power Query:

Removed null or inconsistent records

Standardized date formats

Cleaned categorical fields (state names, product names, shipping status, etc.)

Converted data types (dates, currency, integer fields)

Added calculated columns such as:

Total Sales = Unit Price × Quantity

Profit

Delivery Time (Days between Order Date and Shipment Date)

🏗️ Data Model

The data model is a single-table design from the provided CSV.
Additional measures were created using DAX:

Total Sales

Total Profit

Average Delivery Days

Orders Count

Profit Margin

📈 Dashboard Features
1️⃣ Sales Overview

Total Sales

Total Profit

Total Orders

Profit Margin

2️⃣ Time Series Analysis

Sales by Month

Profit by Month

Seasonal trends

3️⃣ Product Insights

Top 10 best-selling products

Category performance

Profitability by product

4️⃣ Geographical Analysis

Sales distribution by state

Region-wise performance

5️⃣ Order & Shipping Insights

Delivery time analysis

Order status breakdown

Fulfillment trends

🛠 Tools & Technologies

Power BI Desktop

Power Query

DAX (Data Analysis Expressions)

CSV dataset

📊 Key Insights (Example)

These insights may vary depending on your dashboard:

Certain product categories contribute to the highest revenue.

Some states show stronger sales demand patterns.

Delivery delays impact customer satisfaction and overall sales.

Seasonal peaks show increased orders during specific months.

🚀 How to Use This Project

Download the .pbix file

Open it using Power BI Desktop

Explore the pre-built dashboard

Connect your own dataset (optional)

Modify visuals as required

🔮 Future Improvements

Add forecasting using Power BI Analytics

Build separate dimension tables for a star schema model

Create R/Python visuals inside Power BI

Add real-time dashboards using DirectQuery
