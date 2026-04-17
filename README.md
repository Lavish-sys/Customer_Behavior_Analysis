# Customer_Behavior_Analysis

📊 Customer Behavior Analytics Dashboard
🚀 Overview

This project analyzes customer purchasing behavior using Python, SQL, and Power BI to generate meaningful insights and support data-driven decisions.

It follows an end-to-end workflow — from data cleaning to dashboard creation — similar to real-world analytics projects.

🎯 Objective
Understand customer purchase patterns
Analyze the impact of discounts on sales
Identify high-performing product categories
Segment customers based on demographics
🛠️ Tech Stack
Python (Pandas) – Data cleaning and preprocessing
PostgreSQL (SQL) – Data storage and querying
Power BI – Data visualization and dashboard creation
🔄 Workflow
1. Data Preprocessing (Python)
Cleaned and prepared raw data using Pandas
Handled missing values
Standardized column formats
Created derived features such as age groups and purchase frequency
2. Data Storage (SQL)
Loaded cleaned data into PostgreSQL
Structured data for efficient querying
3. Visualization (Power BI)
Built an interactive dashboard to analyze:
Customer demographics
Purchase trends
Revenue by category
Discount impact on sales
📊 Dashboard Highlights
Customer segmentation by age group
Purchase frequency analysis
Revenue distribution across categories
Discount vs sales comparison
Interactive filtering for deeper analysis
📈 Key Insights
Customers with higher purchase frequency contribute more to overall revenue
Discounts influence purchasing behavior but may reduce margins
Some product categories consistently perform better than others
Different age groups show distinct buying patterns
📂 Project Structure
├── analysis.ipynb                      # Data preprocessing (Python)
├── customer_behavior_sql_queries.sql   # SQL queries
├── Customer_Behavior_Dashboard.pbix    # Power BI dashboard
├── dataset.csv                         # Raw dataset
└── README.md                           # Documentation
⚙️ How to Run
Clone the repository:
git clone https://github.com/your-username/customer-behavior-analytics-dashboard.git
cd customer-behavior-analytics-dashboard
Install dependencies:
pip install pandas sqlalchemy psycopg2-binary
Set up PostgreSQL and update the connection string in the notebook.
Run analysis.ipynb to process and load data.
Open the .pbix file in Power BI Desktop to view the dashboard.
💼 Skills Demonstrated
Data cleaning and preprocessing
Feature engineering
SQL database integration
Data visualization and dashboard design
Extracting business insights from data
