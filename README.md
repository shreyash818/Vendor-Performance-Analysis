# Vendor Performance Analysis

## Project Overview
This project focuses on analyzing vendor performance using sales and purchase data.  
The objective is to identify top-performing vendors, profitability, inventory movement, and sales efficiency using data analysis and visualization techniques.

The analysis was performed using Python in Jupyter Notebook and the results were visualized in Power BI to build an interactive dashboard.

---

## Project Objectives
- Analyze vendor sales performance
- Identify profitable vendors and products
- Understand purchase vs sales behavior
- Detect unsold inventory value
- Evaluate stock turnover and profit margin

---

## Dataset Features

The dataset contains vendor and product level performance metrics such as:

- VendorNumber
- VendorName
- Brand
- Description
- PurchasePrice
- ActualPrice
- TotalPurchaseQuantity
- TotalPurchaseDollars
- TotalSalesQuantity
- TotalSalesDollars
- GrossProfit
- ProfitMargin
- StockTurnover
- SalesToPurchaseRatio
- UnsoldInventoryValue
- FreightCost
- TotalExciseTax

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

### 1 Data Collection
Raw vendor sales and purchase dataset was collected.

### 2 Data Cleaning
Data cleaning was performed using Python:
- Handling missing values
- Removing inconsistencies
- Formatting columns

### 3 Exploratory Data Analysis (EDA)
EDA was performed to understand:
- Sales trends
- Vendor performance
- Profit margins
- Inventory movement

### 4 Database Integration
Clean data was stored into a database for structured analysis.

### 5 Power BI Dashboard
An interactive dashboard was created to visualize vendor performance metrics.

---

## Power BI Dashboard Insights

The dashboard includes the following KPIs:

- Total Sales
- Total Purchases
- Gross Profit
- Profit Margin
- Unsold Inventory Value

### Key Visualizations
- Vendor Sales Comparison
- Profit Margin by Vendor
- Sales vs Purchase Ratio
- Stock Turnover Analysis
- Scatter Plot for Vendor Profitability

---

## Repository Structure
Vendor-Performance-Analysis
│
├── Vendor performance Analysis.ipynb
├── Exploratory Data Analysis.ipynb
├── Convert data intoDB.ipynb
├── dataset.csv
└── README.md


---

## Key Insights

- Some vendors generate higher sales but lower profit margins.
- Certain vendors have high unsold inventory value.
- Stock turnover varies significantly between vendors.
- Profitability depends on pricing strategy and sales volume.

---

## Future Improvements

- Add predictive analysis
- Implement vendor ranking system
- Automate dashboard refresh
- Deploy dashboard for real-time monitoring

---
## Power BI Dashboard

The Power BI dashboard provides an interactive visualization of vendor performance including sales, purchases, profitability, and inventory metrics.

### Dashboard Preview

[![Vendor Dashboard](dashboard.png](https://github.com/shreyash818/Vendor-Performance-Analysis/blob/main/Vendors%20Performance%20Data%20.jpeg)

### Dashboard Highlights

- Total Sales Performance
- Vendor Profit Margin Comparison
- Sales vs Purchase Ratio
- Stock Turnover Analysis
- Unsold Inventory Value

The dashboard allows users to filter vendors and analyze their performance using interactive charts and slicers.

## Author

Shreyash Yadav  
Aspiring Data Analyst
