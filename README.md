Project Overview

This project delivers an end-to-end customer behavior analysis using real-world transactional data.
By combining Python for data preparation, PostgreSQL for business analysis, and Power BI for visualization, the project uncovers insights into spending patterns, customer loyalty, subscriptions, and product performance to support data-driven decision-making.

📊 Dataset Snapshot
Metric	Value
🧾 Total Purchases	3,900
📌 Features	18
📍 Locations	50
🛍️ Products	25
⚠️ Missing Values	37 (Review Rating only)

Key Data Includes:

Customer demographics (Age, Gender, Location, Subscription)

Purchase details (Category, Item, Amount, Season, Size, Color)

Behavioral metrics (Discount usage, purchase frequency, reviews, shipping type) 

Customer-Shopping-Behavior-Anal…

🐍 Python: Data Preparation & Feature Engineering

Key steps performed:

Loaded and explored data using pandas

Handled missing values using median imputation by product category

Standardized column names to snake_case

Engineered new features:

age_group

purchase_frequency_days

Ensured data consistency and removed redundant fields

Loaded cleaned data into PostgreSQL for analysis 

Customer Shopping Behavior Anal…

🗄️ SQL: Business-Focused Analysis

Using PostgreSQL, the project answers real business questions, including:

💰 Revenue Insights

Male customers generate 68% of total revenue

Significant opportunity to grow female customer revenue

⭐ Product Performance

Top-rated products: Gloves, Sandals, Boots

Discount-heavy products: Hats, Sneakers, Coats

👥 Customer Segmentation
Segment	Customers
Loyal	3,116
Returning	701
New	83

Only 958 repeat buyers are subscribed, while 2,518 are not → strong conversion opportunity

🚚 Shipping & Subscription Trends

Express shipping users spend slightly more on average

Non-subscribers generate most revenue due to volume, not value

All queries are documented in the SQL script for transparency and reproducibility. 

Customer Shopping Behavior Anal…

📈 Power BI Dashboard

An interactive Power BI dashboard was built to visualize insights, featuring:

KPI cards (customers, avg spend, avg rating)

Revenue & sales by category and age group

Filters for gender, subscription, shipping type, and category

Designed for business stakeholders and decision-makers 

Customer-Shopping-Behavior-Anal…

🎯 Key Business Recommendations

✔ Boost subscriptions with exclusive benefits
✔ Launch loyalty programs for repeat customers
✔ Optimize discount strategy to protect margins
✔ Promote top-rated products in campaigns
✔ Target high-revenue age groups and express-shipping users 

Customer-Shopping-Behavior-Anal…

🛠️ Tech Stack

Python (pandas, data cleaning & feature engineering)

PostgreSQL (business SQL analysis)

Power BI (interactive dashboards)

GitHub (version control & documentation)
