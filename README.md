# Project Overview

This project analyzes a real-world online retail transactional dataset to uncover insights into sales performance, product demand, customer activity, and geographic trends.

Using Power BI, the raw dataset was cleaned, transformed, and visualized into an interactive dashboard designed to support business decision-making.

# Project Objectives (Stronger version)
Analyze the Online Retail dataset to evaluate sales performance
Identify high-revenue and high-demand products
Understand customer purchasing patterns and behavior
Examine country-level sales distribution
Provide data-driven recommendations to improve revenue and growth

# Dataset
 Source

The dataset used in this project is the Online Retail Dataset from Kaggle:
 https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset

# Dataset Description

The dataset contains transactional data from a UK-based online retail store, capturing purchases made by customers over time.

It includes approximately 500,000+ records and reflects real-world business scenarios such as:

Product purchases
Customer transactions
Returns and cancellations
International sales
# Key Columns Used
Column	Description
InvoiceNo	Unique transaction ID (“C” indicates cancelled orders)
StockCode	Product identifier
Description	Product name
Quantity	Number of items purchased
InvoiceDate	Date and time of transaction
UnitPrice	Price per unit
CustomerID	Unique customer identifier
Country	Customer location
# Data Cleaning & Preparation

The raw dataset required preprocessing before analysis:

Removed cancelled transactions (InvoiceNo starting with “C”)
Filtered out negative quantities (returns)
Removed records with missing CustomerID
Converted columns to correct data types
Created a calculated column:
Revenue = Quantity * UnitPrice

These steps ensured that the analysis reflects actual sales performance.

# Key Metrics (KPIs)

The following metrics were created to summarize the dataset:

Total Revenue
Total Orders (distinct InvoiceNo)
Total Quantity Sold
Unique Customers
Average Order Value
Total Countries
# Dashboard Features

The dashboard transforms the dataset into key business views:

Revenue Trend Over Time — monthly sales performance
Top 10 Products by Revenue — identifies high-value products
Top 10 Products by Quantity — highlights high-demand products
Revenue by Country — shows geographic distribution of sales
Order Trends — tracks transaction activity over time
## Key Insights from the Data
The United Kingdom dominates sales, contributing the majority of total revenue
A small group of products generates most revenue, indicating strong product concentration
Sales show seasonal patterns, with increased activity toward the end of the year
Some products have high sales volume but lower revenue, suggesting pricing differences
## Business Recommendations

Based on the dataset analysis:

Focus on top-performing products to maximize revenue
Expand into high-performing international markets
Plan inventory around seasonal demand peaks
Review pricing strategies for high-volume, low-revenue products
## Project Structure
powerbi-dashboard.pbix
README.md
## How to Use
Open the .pbix file in Power BI Desktop
Use filters to explore different countries and time periods
Interact with visuals to analyze trends and performance
## Project Outcome

This project demonstrates:

Data cleaning and preprocessing using real-world data
Business-focused KPI development
Dashboard design and data visualization in Power BI
Ability to translate raw data into actionable insights
# Author

Koketso Lebelo
