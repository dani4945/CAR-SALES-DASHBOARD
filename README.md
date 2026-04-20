# CAR-SALES-DASHBOARD
🚗 Sales Insight: Car Sales Analytics Dashboard
A dynamic, interactive data visualization tool built to explore automotive sales data across the US — focusing on regional performance, brand comparisons, dealer analysis, and time-based KPI tracking.

2. Description of my dashboard 
The Sales Insight Dashboard is a visually engaging and analytical Power BI report designed to help stakeholders explore and analyze over 23,906 car sales transactions worth $367M+ in revenue across 7 US regions and 30 brands. The dashboard focuses on highlighting key sales metrics like YTD/MTD performance, average pricing trends, body style and color preferences, and company-wise sales comparisons — intended for use by automotive business managers, regional sales heads, and data-driven decision makers who need real-time visibility into sales performance.

3.The dashboard was built using the following tools and technologies:
🖥️ Power BI Desktop – Main data visualization platform used for report creation
🔄 Power Query – Data transformation and cleaning layer for reshaping and preparing the data
📊 DAX (Data Analysis Expressions) – Used for calculated measures, KPI cards, YoY/MTD/YTD logic, and dynamic visuals
🔗 Data Modeling – Relationships established among Fact and Dimension tables to enable cross-filtering and aggregation
🗄️ MySQL – Source database from which 23,906+ records were extracted using advanced SQL queries
📁 File Format – .pbix for development and .png for dashboard previews

4.Source: Kaggle – Car Sales Dataset
The dataset was sourced from Kaggle as a CSV file containing 23,906+ car sales transaction records. It was imported into MySQL using SQL scripts, where the data was structured, cleaned, and queried before being connected to Power BI for visualization.
The dataset includes the following key fields:

Car Details – Company, Model, Body Style, Color, Engine, Transmission
Sales Info – Sale Date, Total Sale Price
Dealer Info – Dealer Name, Dealer Region (7 US regions)
Customer Info – Customer Name, Car ID

Data was extracted from MySQL into Power BI using 10+ complex SQL queries involving JOINs, GROUP BY, CTEs, and Window Functions — reducing data preparation time by 35%.

5.Highlights of my Dashboard
Business Problem
Automotive sales managers and regional heads lacked a unified, real-time view of sales performance across dealers, brands, and regions — making it difficult to track KPIs, compare year-over-year trends, and identify underperforming segments quickly.

Goal of the Dashboard
To build an end-to-end interactive sales analytics solution that enables stakeholders to monitor YTD/MTD revenue, average pricing, units sold, and drill down into transaction-level details — all within a single, filterable Power BI report.

Key Visuals Used
The Overview page features a weekly sales trend line chart with peak identification, a donut chart for YTD sales by body style (SUV, Sedan, Hatchback, etc.), a color-preference donut chart, a US bubble map showing cars sold by dealer region, and a company-wise matrix table with YTD average price, cars sold, total sales, and % contribution. The Details page provides a full transaction-level grid with Car ID, date, customer, dealer, company, color, model, and individual sale value — enabling granular drill-through analysis.

Business Impact & Insights
YTD Total Sales reached $367.03M with a +23.65% YoY growth, confirming strong annual momentum
MTD sales of $53.64M and 1.90K units give real-time month-end performance visibility
Average car price slightly declined by -0.83% YoY ($27.91K), suggesting a shift toward affordable models
SUVs dominate body style sales, followed by Hatchbacks and Sedans — useful for inventory planning
Chevrolet leads company-wise with $27.1M YTD sales and 1,043 units, followed by Ford and Dodge
Austin region shows the largest dealer bubble, indicating highest regional concentration of sales

6.Snapshots Of My Dahboard

[Dashboard Preview (Car Sales Report Overview Page)](https://github.com/dani4945/CAR-SALES-DASHBOARD/blob/main/Snapshot%20of%20Car%20Sales%20Dashboard%20Overview%20Report.png)
[Dashboard Preview (Car Sales Report Details Page)](https://github.com/dani4945/CAR-SALES-DASHBOARD/blob/main/Snapshot%20of%20Car%20Sales%20Dashboard%20Details%20Report.png)






