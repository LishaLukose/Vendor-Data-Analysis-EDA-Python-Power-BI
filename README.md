# Vendor Data Analysis & Performance Dashboard

This project focuses on analyzing vendor performance using vendor-related datasets. The goal is to evaluate vendors on multiple KPIs such as delivery timelines, quality, and cost efficiency, and present insights through interactive dashboards.

## Objective

To analyze vendor performance patterns using EDA (Exploratory Data Analysis), MySQL integration, and Power BI visualization. The aim is to uncover trends and relationships between vendor attributes and business outcomes, enabling data-driven vendor selection and performance monitoring.

## Dataset

- `sales.csv`

- `purchases.csv`

- `begin_inventory.csv`
 
- `end_inventory.csv`

- `purchase_prices.csv`

- `vendor_invoice.csv`

## Tools Used

- Python (Jupyter Notebook) → Data preprocessing, cleaning, and EDA.

- Pandas, NumPy → Data wrangling and transformations.

- Matplotlib & Seaborn → Data visualization in Python.

- MySQL → Vendor database queries and management.

- Power BI → Interactive dashboards and performance monitoring.

 ## Key Features

Extracted vendor dataset from MySQL and prepared it for analysis.

Performed univariate and bivariate analysis on vendor KPIs (delivery, cost, defects, quality).

Visualized vendor performance patterns across multiple categories.

Designed Power BI dashboard for real-time tracking and insights.

Compared vendors using statistical and graphical methods.

## Key Insights

Top Vendors by On-Time Delivery: Vendors A & B consistently met deadlines with minimal delays.

Cost vs Quality Tradeoff: Some vendors offered lower costs but showed higher defect rates.

Defect Rate Impact: Vendors with higher defect rates directly correlated with lower performance ratings.

Category-Wise Vendor Efficiency: Vendors supplying electronics performed better in timelines than those in perishable goods.

Power BI Dashboard: Provides drill-down insights into vendor rankings, trends, and KPIs for procurement teams.
