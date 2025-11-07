# Credit Card Financial Dashboard - Visualization Project

This is an end-to-end data analysis project building a comprehensive financial dashboard for a credit card company. The project uses Power BI to connect to a SQL database, process and model the data, and build two interactive, professional-grade dashboards.

## 📊 Project Dashboards

This project includes two main dashboard pages:

1.  **Transaction Report:** A high-level overview of key financial metrics, including:
    * Total Revenue, Interest, Transaction Amount, and Transaction Count.
    * Revenue vs. Transaction Count by Quarter.
    * Breakdowns of revenue by expenditure type, education level, and job type.
    * Key metrics (Revenue, Interest, Fees) by card category.

2.  **Customer Report:** A detailed breakdown of the customer base and their financial behavior, including:
    * KPIs for Revenue, Interest, Total Income, and Customer Satisfaction Score.
    * Week-over-week revenue trends, segmented by gender.
    * Revenue breakdowns by top 5 states, marital status, income group, and dependent count.
    * A summary table of revenue, interest, and income by customer job type.

## 🛠️ Technologies & Skills Demonstrated

* **Database:** Connecting to a SQL server (PostgreSQL/MySQL) as a live data source.
* **Data Transformation (Power Query):** Importing and processing data from the database.
* **Data Modeling:** Creating relationships between tables within Power BI.
* **DAX (Data Analysis Expressions):**
    * Creating new columns (e.g., `Age Group`, `Income Group`).
    * Writing measures for complex, week-over-week (WoW) analysis (e.g., `Current_week_Revenue`, `Previous_week_Revenue`, `WoW Revenue %`).
* **Data Visualization:**
    * Building interactive charts (line, bar, tree map, KPI cards).
    * Using slicers and filters for a dynamic user experience.
* **Dashboard Design:**
    * Creating a clean, professional layout.
    * Applying custom themes, colors, and formatting.

## 📈 Project Insights (YTD Overview)

* **Overall Revenue:** 57M
* **Total Interest:** 8M
* **Total Transaction Amount:** 46M
* **Gender:** Male customers contribute more revenue (31M) than female customers (26M).
* **Card Tiers:** Blue & Silver credit cards account for 93% of all transactions.
* **Geography:** The top 3 states (TX, NY, CA) contribute 68% of all revenue.
* **Key Metrics:** The overall customer activation rate is 57.5%, and the delinquent rate is 6.06%.
