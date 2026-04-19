# Bright-TV-Viewership-Analytics

📺 TV Industry Insights: Data Analysis Project
📌 Project Overview
This project explores current trends in the television industry, focusing on Using SQL-based analysis, this repository provides data-driven insights into how viewership patterns are evolving.

🚀 Key Insights

Performance Metrics: Example: Top 5 shows accounted for 25% of total engagement.

🛠️ Tech Stack & Tools
Database: Databricks (Standard SQL)

Data Cleaning: Handling nulls, duplicate removal, and type casting.

Key Functions Used:

SUM(), AVG() (Aggregates)

OVER(PARTITION BY...) (Window Functions)

CASE WHEN (Conditional logic for genre grouping)

📁 Repository Structure
Plaintext
├── queries/
│   ├── revenue_analysis.sql    # Calculation of total and grouped revenue
│   └── genre_engagement.sql   # Analyzing viewership by genre
├── data/
│   └── (Optional: Link to source dataset if public)
├── visuals/
│   └── insights_dashboard.png # Screenshot of any charts/dashboards
└── README.md
📊 Sample Query
Here is a look at the logic used to calculate total revenue per retail segment:

SQL
SELECT 
  Category, 
  SUM(Revenue) AS total_Revenue 
FROM 
  `your-project-id.Retail_Sales.Retail`
GROUP BY 
  Category
ORDER BY 
  total_Revenue DESC;
🛠️ How to Use

📬 Contact
Created by Belinda madzhie– feel free to reach out for collaboration!

