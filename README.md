# Online Retail Sales Analysis & Customer Segmentation
## Project Overview
This project analyzes an Online Retail dataset using Python and Power BI to discover valuable business insights. The project covers the complete data analysis process, including data cleaning, exploratory data analysis (EDA), customer segmentation using the RFM model, and interactive dashboard creation.
The objective is to help businesses understand customer purchasing behavior, identify valuable customers, and improve decision-making through data visualization.
---
## Project Objectives
- Analyze overall sales performance.
- Identify top-selling products.
- Analyze country-wise revenue contribution.
- Understand customer purchasing patterns.
- Segment customers using the RFM Model.
- Build interactive Power BI dashboards for business insights.
---
## Dataset
The dataset contains online retail transactions including:
- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country
---
## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- DAX
---
## Python Analysis
The following tasks were performed:
### Data Cleaning
- Removed duplicate records
- Removed cancelled invoices
- Removed missing Customer IDs
- Removed invalid Quantity and Unit Price values
### Feature Engineering
Created new columns:
- Total Revenue
- Weekday
- Month
- Year
### Exploratory Data Analysis
Performed analysis on:
- Monthly Revenue Trend
- Country-wise Sales
- Top Selling Products
- Sales by Weekday
- Top Customers
- Revenue Distribution
### Customer Segmentation (RFM)
Calculated:
- Recency
- Frequency
- Monetary Value
Generated:
- R Score
- F Score
- M Score
Created customer segments such as:
- Champion
- Loyal Customer
- Potential Loyalist
- At Risk
- Others
---
  ## Power BI Dashboard
### Page 1 – Sales Dashboard
Includes:
- Total Revenue
- Total Customers
- Total Orders
- Average Order Value
- Country Filter
- Date Filter
- Monthly Revenue Trend
- Top Products
- Revenue by Country
- Sales by Weekday
- Top Customers
---
### Page 2 – Customer Segmentation Dashboard
Includes:
- Total Customers
- Champions
- At Risk Customers
- Potential Loyalists
- Customer Details Table
- Customer Distribution
- Revenue Contribution
- Average Monetary
- Average Recency
- Average Purchase Frequency
---
## Key Business Insights
- United Kingdom contributes the highest revenue.
- A small number of customers generate most of the revenue.
- Champion customers have the highest purchase frequency and monetary value.
- At Risk customers require retention strategies.
- Potential Loyalists can be converted into loyal customers through marketing campaigns
----
## Project Structure
```
Online-Retail-Sales-Analysis/
│
├── Dataset/
├── Python/
├── Dashboard/
├── Reports/
├── Images/
└── README.md
```
## Author
Atoofa anwar
