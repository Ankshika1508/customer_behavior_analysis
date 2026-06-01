
🛍️ Customer Shopping Behavior Analysis

📌 Project Overview

This project analyzes customer shopping behavior data to uncover purchasing trends, customer engagement patterns, and business insights that can help optimize retail strategies.

The analysis focuses on understanding how factors like gender, age group, subscriptions, discounts, shipping preferences, product categories, reviews, and purchase frequency influence customer purchasing behavior and revenue generation.

The project follows a complete Data Analytics workflow using Python → SQL (MySQL) → Power BI.


---

🎯 Business Problem Statement

A retail company wants to better understand customer purchasing behavior in order to improve:

Sales performance

Customer engagement

Product strategy

Marketing decisions

Long-term customer loyalty


Key questions addressed:

Which customer segments generate the highest revenue?

Do subscribed customers spend more?

Which products receive the highest ratings?

How do discounts influence purchasing behavior?

Which categories perform best across customer groups?



---

🛠️ Tech Stack & Tools Used

Python (Data Cleaning & Feature Engineering)

Libraries used:

Pandas

NumPy


Tasks performed:

✔ Data Loading (CSV → Pandas DataFrame)

✔ Exploratory Data Analysis (EDA)

✔ Missing Value Handling

✔ Column Standardization

✔ Feature Engineering

Created new derived columns:

age_group

purchase_frequency_days


✔ Data Validation & Cleaning


---

MySQL (Data Storage & SQL Analytics)

Used MySQL Workbench for:

Database creation

Data loading from Python into MySQL

Running analytical SQL queries


Database:

customer_behavior

Table:

customer

SQL analysis included:

✔ Revenue analysis by gender

✔ Customer segmentation

✔ Subscription impact analysis

✔ Discount effectiveness analysis

✔ Product review analysis

✔ Category performance analysis

✔ Repeat buyer behavior analysis

✔ Revenue contribution by age groups


---

Power BI (Dashboard & Visualization)

Built an interactive dashboard for stakeholder reporting and business insights.

Dashboard features:

✔ KPI Cards

Number of Customers

Average Purchase Amount

Average Review Rating


✔ Interactive Filters / Slicers

Gender

Category

Subscription Status

Shipping Type


✔ Visualizations

Revenue by Category

Sales by Category

Revenue by Age Group

Sales by Age Group

Customer Subscription Distribution



---

📂 Project Workflow

Raw Dataset (.csv)
        ↓
Python (Cleaning + EDA + Feature Engineering)
        ↓
MySQL (Database + SQL Analytics)
        ↓
Power BI (Dashboard + Visualization)
        ↓
Business Insights & Recommendations


---

📊 Key Insights Generated

1. Revenue Contribution by Gender

Analyzed purchasing behavior differences between male and female customers to identify high-value customer groups.

2. Subscription Impact

Compared:

Average Spend

Total Revenue

Customer Counts


between subscribed and non-subscribed customers.

3. Discount Effectiveness

Identified products and customers where discounts influenced purchasing behavior.

4. Customer Segmentation

Customers categorized into:

New Customers

Returning Customers

Loyal Customers


based on previous purchase history.

5. Product Performance Analysis

Analyzed:

Top-rated products

Most purchased products

Category-wise performance


6. Age Group Analysis

Examined purchasing behavior across:

Young Adult

Adult

Middle-aged

Senior


customer groups.


---

📸 Dashboard Preview

(Add your Power BI dashboard screenshot here)

Example:

![Dashboard Screenshot](dashboard.png)


---

📁 Project Files

customer_analysis.ipynb       → Python Cleaning + EDA Notebook
customer_behavior.sql         → Database Export
Queries SQL.sql               → Analytical SQL Queries
customer_shopping_behavior.csv → Dataset
Customer Behavior Dashboard.pbix → Power BI Dashboard
README.md


---

🚀 How To Run The Project

Python

Run:

pip install pandas numpy sqlalchemy pymysql

Open:

customer_analysis.ipynb


---

MySQL

1. Create database:



CREATE DATABASE customer_behavior;

2. Import SQL file.


3. Execute analytical queries.




---

Power BI

Open:

Customer Behavior Dashboard.pbix

Refresh data connection if required.


---

🔮 Future Improvements

Possible future enhancements:

Predictive Analytics / Machine Learning models

Customer Churn Prediction

Sales Forecasting

Recommendation System

Automated Data Pipeline



---

👩‍💻 Author

Ankshika Ghosh

Data Analytics Project — Python | MySQL | Power BI


---

Optional upgrade for GitHub look ✨

After you add dashboard screenshot:

Put image inside repo folder.

Example:

dashboard.png

Then in README:

## Dashboard Preview

![Power BI Dashboard](dashboard.png)

