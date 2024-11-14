🍕 Pizza Sales Power BI Dashboard
📊 Project Overview
This project involves creating an interactive Power BI Dashboard to analyze pizza sales data spanning from January 1, 2015, to December 1, 2015. The dataset contains over 35,000 entries with various measures to help visualize key sales trends and business insights.

The dashboard aims to provide a comprehensive view of sales performance, helping stakeholders make data-driven decisions by exploring sales patterns, top-performing items, revenue breakdowns, and customer trends.

🚀 Features
Interactive Visualizations: Slice and dice data using Power BI's rich interactive capabilities.
Date Range Analysis: Filter sales data by specific dates to analyze time-based trends.
Top 5 Key Measures:
Total Sales: Sum of all sales revenue.
Total Quantity Sold: Count of pizzas sold.
Average Order Value: Average revenue per order.
Customer Count: Number of unique customers.
Sales by Pizza Type: Revenue split by different types of pizzas.
Dynamic Filters: Use slicers for filtering by date, pizza type, customer segment, etc.
Custom DAX Measures: Leveraged DAX functions for creating calculated columns and measures to enhance data insights.
📁 Dataset
Source
File Type: CSV
Date Range: January 1, 2015 - December 1, 2015
Number of Records: 35,000+
Attributes:
Date: Date of sale (e.g., 01-01-2015)
Pizza Type: Name of the pizza sold (e.g., Margherita, Pepperoni, Veggie)
Quantity: Number of pizzas sold per transaction
Price: Price per unit of pizza
Total Sales: Revenue generated per transaction
Customer ID: Unique identifier for customers
Sample Data
Date	Pizza Type	Quantity	Price	Total Sales	Customer ID
01-01-2015	Margherita	3	10.99	32.97	1001
05-03-2015	Pepperoni	2	12.49	24.98	1002
15-07-2015	Veggie	1	11.50	11.50	1003
📊 Power BI Dashboard Insights
Sales Performance Overview:

Monthly and daily sales trends.
Top-selling pizzas and best-performing months.
Customer Insights:

Customer frequency and loyalty metrics.
Average order value by customer segment.
Revenue Breakdown:

Revenue by pizza type, category, and size.
Revenue contribution by top 10 customers.
Order Trends:

Analysis of peak sales times (days of the week, time of day).
Seasonal sales patterns.
🛠️ Tools & Technologies
Power BI: For creating interactive visualizations and dashboards.
Excel/CSV: Source data files.
DAX: For creating custom measures and calculated fields.
📦 Repository Structure
plaintext
Copy code
pizza-sales-dashboard/
├── data/
│   └── pizza_sales_2015.csv
├── dashboard/
│   └── Pizza_Sales_Dashboard.pbix
├── images/
│   ├── dashboard_screenshot_1.png
│   ├── dashboard_screenshot_2.png
├── README.md
└── LICENSE

