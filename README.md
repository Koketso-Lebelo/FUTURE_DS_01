# Project Overview

This project analyzes real-world e-commerce transaction data to uncover actionable business insights. An interactive dashboard was developed in Power BI to evaluate sales performance, product demand, customer behavior, and geographic trends.

The goal of this project was to move beyond basic reporting and deliver insights that support data-driven business decisions.

# Business Objective

Businesses generate large volumes of transactional data but often struggle to extract meaningful insights.

This project aims to answer key business questions:

Which products generate the most revenue?
How does sales performance change over time?
Which countries contribute the most sales?
Where should the business focus to drive growth?
 ## Tools & Technologies
Power BI — Dashboard development & visualization
Power Query — Data cleaning & transformation
DAX — Data modeling & calculations
Excel / CSV — Data source
 ## Data Preparation

To ensure accurate analysis, the dataset was cleaned and transformed:

Removed cancelled transactions (InvoiceNo starting with “C”)
Filtered out negative quantities (returns)
Removed records with missing CustomerID
Converted data types for numerical and date fields
Created a calculated column:
Revenue = Quantity × UnitPrice
Key Metrics (KPIs)

The dashboard highlights the following core business metrics:

Total Revenue
Total Orders
Total Quantity Sold
Total Customers

These KPIs provide a quick overview of overall business performance.

# Dashboard Features

The dashboard includes:

Revenue Trend Analysis — monthly sales performance
Top 10 Products by Revenue — high-value product identification
Top 10 Products by Quantity — demand analysis
Revenue by Country — geographic performance
Interactive Filters — dynamic exploration by time and location
## Key Insights
The United Kingdom generates the majority of total revenue, indicating strong domestic dominance.
A small number of products contribute a significant portion of total sales, suggesting product concentration.
Sales show clear seasonal trends, with peaks during year-end periods.
Some products sell in high volumes but generate lower revenue, indicating pricing differences.
## Business Recommendations
Focus marketing efforts on high-performing products to maximize revenue
Expand into high-performing international markets
Prepare inventory for seasonal demand spikes
Review pricing strategies for high-volume, low-revenue products

## Project Structure
online-retail-sales-analysis
powerbi-dashboard.pbix
screenshots
dashboard.png
README.md

## How to Use
Open the .pbix file in Power BI Desktop
Use filters (Country, Date) to explore the data
Interact with visuals to uncover insights
Dataset
## Source

The dataset used in this project is the Online Retail Dataset, available on Kaggle:

https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset

# Description

This dataset contains transactional data from an online retail store, including:

Product purchases
Customer activity
Transaction timestamps
Geographic information

It includes approximately 500,000+ records, making it suitable for real-world analytics and business intelligence projects.

## Key Columns
InvoiceNo — Transaction ID (“C” indicates cancellation)
StockCode — Product ID
Description — Product name
Quantity — Number of items purchased
InvoiceDate — Date of transaction
UnitPrice — Price per item
CustomerID — Unique customer identifier
Country — Customer location

## Data Considerations
Cancelled and return transactions were excluded for accurate analysis
Missing CustomerID values limited customer-level insights
Data is heavily skewed toward the United Kingdom

## Project Outcome

This project demonstrates the ability to:

Clean and prepare real-world data
Perform business-focused data analysis
Build interactive dashboards in Power BI
Communicate insights and recommendations effectively

# Author
Koketso Lebelo 
