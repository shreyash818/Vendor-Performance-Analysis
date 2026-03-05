# Vendor Performance Analysis

## Project Overview

The **Vendor Performance Analysis** project focuses on analyzing vendor sales and purchase data to evaluate vendor efficiency, profitability, and inventory performance.

The project uses **Python-based data analysis** in Jupyter Notebook and an **interactive Power BI dashboard** to identify business insights such as sales performance, profit margins, and stock turnover.

The goal is to help businesses understand which vendors perform best and where improvements can be made.

---

## Project Objectives

- Analyze vendor sales performance
- Identify the most profitable vendors
- Compare purchase vs sales trends
- Detect unsold inventory
- Evaluate vendor efficiency using stock turnover and profit margin

---

## Dataset Description

The dataset contains vendor-level product sales and purchase information.

### Key Columns

| Column Name | Description |
|-------------|-------------|
| VendorNumber | Unique vendor ID |
| VendorName | Vendor company name |
| Brand | Product brand |
| Description | Product description |
| PurchasePrice | Price at which product was purchased |
| ActualPrice | Selling price |
| TotalPurchaseQuantity | Total quantity purchased |
| TotalPurchaseDollars | Total purchase amount |
| TotalSalesQuantity | Total quantity sold |
| TotalSalesDollars | Total sales revenue |
| GrossProfit | Profit generated |
| ProfitMargin | Profit percentage |
| StockTurnover | Inventory turnover ratio |
| SalesToPurchaseRatio | Sales vs purchase efficiency |
| UnsoldInventoryValue | Value of unsold inventory |

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- Power BI
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection
Raw vendor dataset was obtained containing sales and purchase records.

### 2. Data Cleaning
Data preprocessing was performed to ensure consistency and remove errors.

Steps included:

- Handling missing values
- Correcting data types
- Removing duplicates

### 3. Exploratory Data Analysis (EDA)
EDA was performed to understand patterns in the dataset including:

- Vendor sales distribution
- Profit margins
- Inventory turnover
- Vendor profitability

### 4. Data Storage
The cleaned dataset was prepared for further analysis and database integration.

### 5. Dashboard Creation
An interactive dashboard was built in **Power BI** to visualize vendor performance metrics.

---

## Power BI Dashboard

An interactive dashboard was developed using **Microsoft Power BI** to monitor vendor performance and business metrics.

### Dashboard Preview

https://github.com/shreyash818/Vendor-Performance-Analysis/blob/main/Vendors%20Performance%20Data%20.jpeg

### Dashboard KPIs

The dashboard displays important business KPIs such as:

- Total Sales
- Total Purchases
- Gross Profit
- Profit Margin
- Unsold Inventory Value

### Key Visualizations

The dashboard includes the following charts:

- Vendor Sales Comparison
- Profit Margin by Vendor
- Sales vs Purchase Ratio
- Stock Turnover Analysis
- Vendor Profitability Scatter Plot
- Donut Chart for Sales Distribution

### Dashboard Filters (Slicers)

Users can filter data using:

- Vendor Name

---

## Key Insights

Some important insights from the analysis:

- Certain vendors generate high revenue but lower profit margins.
- Some vendors have significant unsold inventory value.
- Vendors with higher stock turnover generally show better sales performance.
- Profitability varies based on pricing strategy and purchase volume.

---

## Repository Structure

Vendor-Performance-Analysis

- Vendor performance Analysis.ipynb
- Exploratory Data Analysis.ipynb
- Convert data intoDB.ipynb
- dataset.csv
- dashboard.png
- README.md

---

## Future Improvements

Future enhancements for this project may include:

- Predictive analysis using machine learning
- Vendor performance ranking model
- Automated data pipeline
- Real-time dashboard integration

---

## Author

**Shreyash Yadav**

Aspiring Data Analyst

Skills: Python | SQL | Power BI | Data Analysis | Data Visualization
