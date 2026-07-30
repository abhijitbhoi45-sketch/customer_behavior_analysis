1. Customer Shopping Behavior Analysis

An end-to-end Data Analytics project that analyzes customer shopping behavior using Python, PostgreSQL, SQL, and Power BI to generate business insights and support data-driven decision-making.

2. Project Overview

This project analyzes customer shopping behavior using a dataset of 3,900 customer purchase records. The objective is to identify purchasing patterns, customer preferences, and revenue trends by applying data preprocessing, SQL-based business analysis, and interactive data visualization.

The project demonstrates the complete data analytics workflow:

Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL Business Analysis
- Interactive Dashboard Development
- Business Recommendations

3. Problem Statement

Retail businesses generate large volumes of customer transaction data every day. However, without proper analysis, it becomes difficult to understand customer behavior, identify high-value customers, evaluate product performance, and make informed business decisions.

This project aims to transform raw transactional data into meaningful business insights using modern data analytics tools.

4. Dataset Information
   
Attribute	Details
- Dataset	Customer Shopping Behavior
- Records	3,900
- Features	18
- Data Type	Customer Transactions
- Missing Values	37 (Review Rating column)
- Dataset Features
- Customer ID
- Age
- Gender
- Location
- Item Purchased
- Category
- Purchase Amount
- Season
- Size
- Color
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

5. Tools & Technologies

Tool              | Purpose
Python            | Data preprocessing and feature engineering
Pandas	         | Data manipulation and cleaning
PostgreSQL	      | Database management
SQL	Business    | analysis and querying
Power BI	         | Dashboard development
Jupyter Notebook	| Python development environment

6. Project Workflow

Raw Dataset
      │
      ▼
Data Cleaning (Python)
      │
      ▼
Feature Engineering
      │
      ▼
Load Cleaned Data into PostgreSQL
      │
      ▼
SQL Business Analysis
      │
      ▼
Power BI Dashboard
      │
      ▼
Business Insights & Recommendations


7. Data Preprocessing

The dataset was cleaned and transformed using Python.

- Data Cleaning
- Checked dataset structure
- Removed inconsistencies
- Renamed columns to snake_case
- Handled missing values
- Verified data quality
- Missing Value Handling

Missing values in the Review Rating column were filled using the median rating of each product category.

8. Feature Engineering

Created new analytical features including:

- Age Groups
- Purchase Frequency (Days)
- Data Consistency Checks
- Verified Discount Applied and Promo Code Used columns
- Removed redundant columns where necessary

9. SQL Business Analysis

The following business questions were answered using PostgreSQL.

Revenue Analysis
 - Total Revenue by Gender
 - Revenue by Age Group
 - Subscriber vs Non-Subscriber Revenue
  
Customer Analysis
 - Customer Segmentation
 - Repeat Buyer Analysis
 - High-Spending Discount Users

Product Analysis
 - Top 5 Highest Rated Products
 - Top 3 Products in Each Category
 - Discount-Dependent Products
  
Sales Analysis
 - Shipping Type Comparison
 - Subscription Spending Behavior

10. Power BI Dashboard

The interactive dashboard includes:

- Revenue Analysis
- Customer Demographics
- Purchase Distribution
- Product Category Performance
- Subscriber vs Non-Subscriber Analysis
- Shipping Type Analysis
- Interactive Filters
- KPI Cards

11. Key Business Insights
    
- Subscriber customers contribute significantly to total revenue.
- Loyal customers generate higher lifetime value.
- Certain product categories consistently receive higher customer ratings.
- Discounts increase purchase frequency but should be optimized to protect profit margins.
- Age-based customer segmentation helps improve targeted marketing campaigns.
- Shipping preferences influence customer purchasing behavior.

12. Business Recommendations
    
- Introduce attractive subscription benefits.
- Strengthen customer loyalty programs.
- Optimize discount strategies.
- Promote top-rated and best-selling products.
- Personalize marketing campaigns based on customer segments.
- Focus promotional efforts on high-value customer groups.

13. Repository Structure
    
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── Data_Cleaning_EDA.ipynb
│
├── SQL/
│   └── Business_Analysis.sql
│
├── PowerBI/
│   └── Customer_Shopping_Dashboard.pbix
│
├── Report/
│   └── Customer_Shopping_Behavior_Analysis.pdf
│
└── README.md
