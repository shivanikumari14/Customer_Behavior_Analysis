Customer Shopping Behavior Analysis

1. Project Overview

This project focuses on analyzing customer shopping behavior using transactional data from 3,900 purchases across different product categories.

The main objective is to understand customer purchasing patterns, spending behavior, product preferences, subscription trends, and customer segments to generate meaningful business insights.

The project follows an end-to-end data analytics workflow, starting with data loading and cleaning in Python, performing business analysis using MySQL, and presenting insights through an interactive Power BI dashboard and a project report.

2. Dataset

Total Records: 3,900
Total Columns: 18
Dataset Type: Customer Shopping Transaction Data

Key Features
Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases
Customer Feedback: Review Rating
Delivery Information: Shipping Type

Data Cleaning
Handled 37 missing values in the Review Rating column using category-wise median imputation.
Standardized column names into snake_case.
Created age_group using age-based quartile segmentation.
Created purchase_frequency_days to convert shopping frequency into numerical days.
Checked discount_applied and promo_code_used for redundancy and dropped promo_code_used.

3. Tools & Technologies

Tool        Purpose

Python      Data analysis and preprocessing

Pandas      Data manipulation and cleaning

Jupyter 
Notebook    Writing and executing Python code

MySQL       Database management and SQL analysis

SQL         Business queries and customer segmentation

Power BI    Interactive dashboard creation

Gamma AI     Project presentation (PPT)


4. Project Workflow

Step 1: Data Loading & Exploration (Python)
Imported the dataset using Pandas.
Explored the dataset using head(), info(), and describe().
Checked missing values and data types.
Understood the structure of the dataset.

Step 2: Data Cleaning & Feature Engineering (Python)
Handled missing values using category-wise median imputation.
Standardized column names.
Created age groups: Young Adult, Adult, Middle-aged, and Senior.
Converted purchase frequency into numerical days.
Removed redundant columns after checking data consistency.

Step 3: Database Integration (MySQL)
Connected Python with MySQL using SQLAlchemy and mysql-connector-python.
Created a database named customer_behavior.
Loaded the cleaned DataFrame into a MySQL table named customer.

Step 4: Business Analysis (MySQL)
Performed SQL analysis to answer 10 important business questions:
Revenue comparison between male and female customers.
Identification of high-spending customers who used discounts.

Top 5 products based on average review ratings.
Comparison of average purchase amounts for Standard and Express shipping.
Spending and revenue comparison between subscribers and non-subscribers.
Identification of products with the highest percentage of discounted purchases.
Customer segmentation into New, Returning, and Loyal customers.
Identification of the top 3 most purchased products in each category.
Analysis of the relationship between repeat purchases and subscriptions.
Revenue contribution by age group.

Step 5: Dashboard Development (Power BI)
Connected and imported the analyzed data.
Created an interactive dashboard.
Used visualizations to present customer behavior and purchasing trends.
Presented important business metrics and insights in an easy-to-understand format.

Step 6: Project Report & Presentation
Created a detailed project report summarizing the analysis and business recommendations.
Used Gamma AI to prepare a professional PowerPoint presentation explaining the project workflow, analysis, and findings.

5. Power BI Dashboard
The Power BI dashboard provides a visual overview of customer shopping behavior and helps understand purchasing trends and business performance.
