This project analyzes the historical stock performance of six stocks using Excel and Looker Studio.
The goal is to explore price trends, calculate daily returns, compute a 10-day moving average, and build interactive visualizations for deeper understanding.


---

📁 Project Files

Stock_Analysis.xlsx – cleaned dataset, daily returns, 10-day moving average

dashboard_link.txt – Looker Studio dashboard URL


README.md – project explanation



---

📊 Data Source

The historical price data was downloaded from NSE India (National Stock Exchange of India):

Data cleaned and merged from multiple yearly CSV files

Columns used: Date, Close Price



---

🧮 Analysis Performed

1. Data Cleaning

Combined multiple CSVs (year-wise)

Retained only required columns

Sorted dates from oldest → newest



2. Daily Returns Calculation
Formula:
(Close - Previous Close) / Previous Close


3. 10-Day Moving Average Computed on cleaned close prices for trend detection.


4. Interactive Dashboard (Looker Studio)

Close Price Trend

10-Day Moving Average


Year and Month Slicers

Multi-page navigation





---

📈 Visualizations

Built using Looker Studio, featuring:

Year-based filtering applied across all pages

Monthly filtering for seasonality

Clear time-series charts

Slicers for dynamic exploration


Dashboard Link:
(available in the dashboard_link.txt file)


---

🚀 Skills Demonstrated

Excel for financial data analysis

Data cleaning and transformation

Moving averages and return calculations

Looker Studio interactive dashboard

GitHub documentation and project structure
