📊 Customer Shopping Behavior Analysis
🔍 Overview

This project showcases an end-to-end data analytics workflow to analyze customer shopping behavior using Python, PostgreSQL, and Power BI.
The objective is to extract actionable insights from transactional data and present them through clear visualizations and business-ready reports.

📁 Dataset
Total Records: 3,900 customer purchases
Total Columns: 18
Data Includes:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Item, Category, Amount, Season, Size, Color)
Shopping behavior (Discount, Previous Purchases, Review Rating, Shipping Type)
Missing Values: 37 missing values in the review_rating column (handled during cleaning)

🛠 Tools & Technologies

Python 
PostgreSQL (SQL queries for business analysis)
Power BI (Interactive dashboard)
Jupyter Notebook
Gamma (Presentation / PPT)

⚙️ Project Steps

Loaded the dataset in Python using Pandas
Performed data cleaning and preprocessing
Conducted Exploratory Data Analysis (EDA)
Engineered features such as age groups and purchase frequency
Loaded cleaned data into PostgreSQL
Ran SQL queries to answer business questions
Built an interactive Power BI dashboard
Created a detailed report and presentation using Gamma

🧮 SQL Analysis (PostgreSQL)

Key business questions answered using SQL:
Revenue comparison by gender
Spending behavior of discount users
Top-rated and most-purchased products
Subscriber vs non-subscriber spending
Shipping type impact on purchase amount
Customer segmentation (New, Returning, Loyal)
Revenue contribution by age group

📈 Power BI Dashboard

The dashboard provides insights on:

Customer demographics and segmentation
Category-wise and seasonal sales trends
Subscription and discount impact
Key performance indicators (KPIs)

📁 File: customer_behavior_dashboard.pbix

📊 Key Results & Insights

Loyal and returning customers contribute higher revenue
Subscribers show higher average spending than non-subscribers
Certain products are highly discount-dependent
Specific age groups and shipping types generate higher revenue
Top-rated products align strongly with repeat purchases

📌 Business Recommendations

Promote subscription benefits to increase customer lifetime value
Introduce loyalty programs for repeat customers
Optimize discount strategies to protect margins
Highlight top-rated and best-selling products in marketing campaigns
Target high-revenue age groups and express-shipping users

▶️ How to Run the Project

Clone this repository
git clone https://github.com/your-username/your-repo-name.git
Open Customer_Shopping_Behavior_Analysis.ipynb and run the Python analysis
Load the cleaned dataset into PostgreSQL
Execute SQL queries from customer_behavior_sql_queries.sql
Open the Power BI dashboard file to explore insights
Review the report and Gamma presentation for summarized findings
