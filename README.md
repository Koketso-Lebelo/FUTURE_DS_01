# Online Retail Sales Dashboard - Power BI



An interactive **Power BI dashboard** built to analyze a real-world Online Retail transactional dataset. This project uncovers key insights into sales performance, top-performing products, customer behavior, and geographic trends to support data-driven business decisions.

##  Project Objectives

- Evaluate overall sales performance and trends
- Identify high-revenue and high-demand products
- Understand customer purchasing patterns and behavior
- Analyze country-level sales distribution
- Provide actionable recommendations to drive revenue and growth

##  Dataset

**Source:** [Online Retail Dataset on Kaggle](https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset)

The dataset contains over **500,000 transactional records** from a UK-based online retail company (similar to real e-commerce platforms like those selling gifts and household items).

### Key Columns
- **InvoiceNo** — Transaction ID (C = Cancelled)
- **StockCode** — Product identifier
- **Description** — Product name
- **Quantity** — Number of units purchased
- **InvoiceDate** — Date and time of transaction
- **UnitPrice** — Price per unit
- **CustomerID** — Unique customer identifier
- **Country** — Customer’s country

##  Data Cleaning & Preparation

Raw data was cleaned and transformed in Power BI:
- Removed cancelled transactions (InvoiceNo starting with "C")
- Filtered out negative quantities (returns)
- Removed records with missing `CustomerID`
- Converted data types where necessary
- Created a new **Revenue** measure: `Revenue = Quantity × UnitPrice`

These steps ensured the analysis reflects only **completed, valid sales**.

##  Key Metrics (KPIs)

- **Total Revenue**
- **Total Orders** (distinct InvoiceNo)
- **Total Quantity Sold**
- **Unique Customers**
- **Average Order Value (AOV)**
- **Total Countries**

##  Dashboard Features

The interactive dashboard includes:

- **Revenue Trend Over Time** — Monthly sales performance
- **Top 10 Products by Revenue** — High-value products
- **Top 10 Products by Quantity** — High-demand (volume) products
- **Revenue by Country** — Geographic sales distribution (with UK dominance highlighted)
- **Order Trends** — Transaction activity over time
- Slicers for Country, Time Period, and Product filtering

##  Key Insights

- The **United Kingdom** accounts for the vast majority of total revenue
- A small number of products drive most of the revenue (strong product concentration)
- Clear **seasonal patterns** — higher activity toward the end of the year (holiday season)
- Some products have high sales volume but relatively lower revenue, indicating pricing or margin differences

##  Business Recommendations

- Prioritize stocking and marketing of **top revenue-generating products**
- Focus expansion efforts on high-performing international markets
- Optimize inventory planning around **year-end seasonal peaks**
- Review pricing strategy for high-volume, low-revenue products to improve margins


##  How to Use

1. Download or clone this repository
2. Open `powerbi-dashboard.pbix` in **Power BI Desktop**
3. Interact with the visuals and use the slicers to explore different countries, time periods, or products

No additional setup or data sources required — everything is embedded.

##  Technologies Used

- **Power BI Desktop** — Data modeling, DAX measures, and visualization
- **Power Query** — Data cleaning and transformation

##  Project Outcome

This project showcases:
- Real-world data cleaning and preprocessing
- Business-oriented KPI and measure development
- Professional dashboard design and storytelling with data
- Ability to derive actionable insights from raw transactional data

---

**Author:** Koketso Lebelo  




