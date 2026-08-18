☕ Dirty Coffee Shop - Sales Analysis Dashboard
📌 Project Overview
<img width="1312" height="729" alt="Untitled sales 1" src="https://github.com/user-attachments/assets/4215f1e9-7ae5-4f7d-92ee-2e34374512f0" />

This project provides a comprehensive end-to-end sales performance analysis for a coffee shop chain using raw data sourced from Kaggle. The raw data was processed, cleaned, and transformed to uncover key business metrics, customer purchasing behaviors, and operational trends across various locations and sales channels.

🛠️ Project Workflow & Tools Used
1. Data Extraction & Cleaning (Power Query)
Data Source: Raw sales dataset extracted from Kaggle ("Dirty Coffee Shop Sales").

Power Query Transformations:

Cleaned missing values, duplicates, and standardized data types across columns.

Handled missing attributes by categorizing unidentified records as UNKNOWN.

Created structured custom columns for date dimensions, quarters, and months for dynamic filtering.

2. Data Modeling & DAX Measures (Power BI)
Developed key business indicators (KPIs) using custom DAX calculations:

Total Transactions: 9K requests analyzed.

Total Sales Volume: 29K items sold.

Total Revenue Generated: $84.723K.

Average Transaction Value: $9 per order.

3. Interactive Dashboard Design
Built an interactive and cohesive dashboard featuring custom dynamic visuals:

KPI Summary Cards: Quick insight into total requests, units sold, total revenue, and average transaction value.

Requests by Location: Visualized distribution across In-store, Takeaway, and UNKNOWN locations using pie chart breakdown.

Revenue by Payment Method: Funnel analysis across Digital Wallet, Cash, Credit Card, and UNKNOWN channels.

Top-Selling Items: Horizontal bar chart highlighting dynamic product performance (led by Salads, Sandwiches, and Smoothies).

Monthly Revenue Trends: Line chart depicting sales performance and seasonality from January to December.

Product vs. Location Analysis: Clustered column chart comparing item sales volume across operational locations.

📊 Key Insights
Top Revenue Drivers: Food items such as Salads ($16.5K) and Sandwiches ($13.0K) outperformed traditional beverage sales in total revenue.

Sales Seasonality: Peak sales spikes occurred during June ($7,350) and October ($7,295).

Payment Diversity: Digital Wallets ($19.51K), Cash ($19.49K), and Credit Cards ($19.44K) hold an almost equal distribution in customer payment preferences.

🚀 How to View the Project
Clone this repository:

Bash
git clone https://github.com/YourUsername/Coffee-Shop-Sales-Analysis.git
Open the .pbix file using Power BI Desktop.

Interact with slicers (Location, Quarter/Month) to filter data dynamically.
