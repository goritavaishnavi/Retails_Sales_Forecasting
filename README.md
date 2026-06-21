# Retails_Sales_Forecasting
Retail Sales Forecasting and Business Insights Dashboard
Project Overview
This project analyzes Walmart retail sales data to identify sales trends, evaluate business performance, and forecast future sales using Power BI. The dashboard provides interactive visualizations, business insights, and predictive analytics to support data-driven decision-making.

Problem Statement
Businesses need to understand historical sales performance and forecast future trends to improve planning and decision-making. This project aims to:
Analyze historical sales data
Identify key sales drivers
Compare holiday and non-holiday sales performance
Evaluate the impact of economic factors
Forecast future sales trends

Dataset Information
The dataset contains historical Walmart sales data with the following attributes:
Column
Description
Store
Store ID
Date
Weekly sales date
Weekly_Sales
Weekly sales revenue
Holiday_Flag
Indicates holiday week (0 = No, 1 = Yes)
Temperature
Weekly average temperature
Fuel_Price
Fuel price
CPI
Consumer Price Index
Unemployment
Unemployment rate

Tools and Technologies
Power BI Desktop
Power Query
DAX (Data Analysis Expressions)
Microsoft Excel / CSV Dataset

Data Preparation
The following preprocessing steps were performed:
Converted Date column to Date format
Removed invalid and duplicate records
Created Year, Month, Quarter, and Month Number columns
Organized data for analysis and forecasting

Key Performance Indicators (KPIs)
The dashboard includes:
Total Sales
Average Weekly Sales
Total Number of Stores

Dashboard Visualizations
Sales Trend Analysis
Monthly Sales Trend
Sales Forecast using historical sales data
Store Performance Analysis
Total Sales by Store
Identification of top-performing stores
Holiday Impact Analysis
Average Weekly Sales during Holiday vs Non-Holiday periods
Economic Factors Analysis
CPI vs Weekly Sales
Temperature vs Weekly Sales
Interactive Filters
Year Filter
Store Filter
Holiday Filter

Key Insights
Total sales reached approximately 6.74 Billion.
The dataset covers 45 Walmart stores.
Holiday weeks generated higher average sales compared to non-holiday weeks.
Certain stores consistently outperformed others in total sales.
Temperature shows a weak relationship with sales performance.
CPI has limited impact on weekly sales.
Forecasting indicates relatively stable future sales trends.

Forecasting
Power BI’s built-in forecasting feature was applied to historical weekly sales data to predict future sales trends.
Forecast Configuration:
Historical Weekly Sales Data
Time Series Forecasting
Confidence Interval: 95%
Forecast Horizon: Future Weeks

Dashboard Screenshot
Add your dashboard screenshot here after uploading it to GitHub.
Example:
screenshots/dashboard.png

Project Structure
Retail-Sales-Forecasting
│
├── Walmart.csv
├── Retail_Sales_Dashboard.pbix
├── screenshots/
│   ├── dashboard.png
│   └── forecast.png
│
|
│
└── README.md

Business Value
This dashboard helps businesses:
Monitor sales performance
Identify sales trends
Understand holiday sales behavior
Analyze economic factors affecting sales
Forecast future sales for better planning

Future Improvements
Advanced forecasting models
Regional sales analysis
Product category analysis
Customer segmentation
Integration with live data sources

Author
Vaishnavi Reddy
Data Analytics Project | Power BI | Retail Sales Forecasting
