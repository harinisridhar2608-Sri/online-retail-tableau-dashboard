This repository contains my Tableau workbook created using the Online Retail Dataset.
The project includes four separate analysis sheets, each answering a key business question related to revenue, customer behaviour, and market demand.

 Project Overview

This Tableau project answers four questions asked by the CEO and CMO:

1️.Monthly Revenue Trend for 2011
Line chart showing revenue month-by-month.
Clear seasonal pattern with a strong peak in November.

2️.Top 10 Countries by Revenue (Excluding UK)
Horizontal bar chart showing which international markets generate the most revenue.
Germany, France, and Ireland stand out as high-performing regions.

3️. Top 10 Customers by Revenue
Identifies the highest-value customers.
Useful for loyalty, targeting, and retention strategies.

4️. Demand by Country (Excluding UK)
Total quantity sold used to measure demand.
Germany, Ireland, France, Netherlands, and Australia show strong product movement.

All visuals were created on separate sheets instead of a dashboard, as the focus of the project was on analysis, clarity, and answering leadership questions.

🧼 Data Cleaning

Before creating the visuals, I cleaned the dataset to ensure accuracy:
Removed rows where Quantity < 1 (returns or incorrect values)
Removed rows where UnitPrice < 0

Created a calculated field for Revenue:
Revenue = Quantity * UnitPrice

This allowed for reliable and meaningful analysis.

Tools Used
Tableau Desktop
Excel (for dataset)
GitHub (for version control and project hosting)

Key Insights

Q4, especially November, is the highest revenue season.
Strong international opportunities exist in Germany, France, Ireland, and the Netherlands.

A small group of customers contribute a large share of revenue.
Several countries have high demand and are strong candidates for expansion.

Repository Contents
.twbx — Tableau packaged workbook containing 4 analysis sheets
Screenshots of visuals 
README explaining the analysis
MIT License

🙋‍♀️ About Me

I am learning data analytics and Tableau visualisation.
This project represents one of my first structured data analysis projects shared on GitHub.
