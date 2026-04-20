Sales Dashboard (Power BI)
Overview

This project is an interactive Sales Dashboard built using Power BI. It provides insights into sales, revenue, returns, and customer segments across different countries, categories, and time periods.

The dashboard is designed with a clean user interface and interactive filters to help users analyze business performance efficiently.

Objectives
Analyze total sales and revenue performance
Track product categories and subcategories
Monitor returns and discounts
Compare sales across countries
Provide interactive filtering for better insights
Dataset Details

The dataset follows a star schema model.

Fact Tables

Sales_Fact: Contains sales transactions
Returns_Fact: Contains return data

Dimension Tables

Customer_Dim
Product_Dim
Region_Dim
Date_Dim
Tools and Technologies
Power BI Desktop
Power Query for data cleaning
Data Modeling (Star Schema)
DAX (Data Analysis Expressions)
Project Workflow
Data Import
Loaded multiple datasets into Power BI using the Get Data option
Data Cleaning
Removed null values, corrected data types, and structured the dataset
Data Modeling
Created relationships between fact and dimension tables and implemented a star schema
DAX Measures
Created measures such as Total Sales, Total Quantity, Total Returns, and Average Discount
Dashboard Features

KPI Metrics

Total Sales: 125K
Total Quantity: 3K
Total Returns: 100
Average Discount: 9.36

Visualizations

Total Returns by Brand and Category (Bar Chart)
Revenue by Subcategory and Category (Stacked Column Chart)
Sales by Country (Bar Chart)
Category-wise Sales Table
Segment-wise Revenue Table

Filters

Category
State
Month
Dashboard Preview
<img width="1107" height="737" alt="Screenshot 2026-04-20 120709" src="https://github.com/user-attachments/assets/4e2b670b-bd86-4802-9028-c32162e903ed" />


Key Insights
USA has the highest sales (approximately 52K)
India and Germany show moderate performance
Clothing and Electronics categories perform strongly
Some brands have higher return rates
Discounts influence revenue trends
How to Use
Download the PBIX file
Open it in Power BI Desktop
Use slicers such as Category, State, and Month
Explore the dashboard interactively
Project Files
PROJECT NO 2.pbix: Main dashboard file
README.md: Project documentation

Author
Dev Patel
