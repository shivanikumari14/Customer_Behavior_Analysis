# Customer Shopping Behavior Analysis

## 1. Project Overview

This project focuses on analyzing customer shopping behavior using transactional data from **3,900 purchases** across different product categories.

The main objective is to understand customer purchasing patterns, spending behavior, product preferences, subscription trends, and customer segments to generate meaningful business insights.

The project follows an end-to-end data analytics workflow, starting with data loading and cleaning in Python, performing business analysis using MySQL, and presenting insights through an interactive Power BI dashboard and a project report.

## 2. Dataset

- **Total Records:** 3,900
- **Total Columns:** 18
- **Dataset Type:** Customer Shopping Transaction Data

### Key Features

- Customer Demographics: Age, Gender, Location, Subscription Status
- Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
- Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases
- Customer Feedback: Review Rating
- Delivery Information: Shipping Type

### Data Cleaning

- Handled 37 missing values in the Review Rating column using category-wise median imputation.
- Standardized column names into snake_case.
- Created age_group using age-based quartile segmentation.
- Created purchase_frequency_days to convert shopping frequency into numerical days.
- Checked discount_applied and promo_code_used for redundancy and dropped promo_code_used.

## 3. Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation and cleaning |
| Jupyter Notebook | Writing and executing Python code |
| MySQL | Database management and SQL analysis |
| SQL | Business queries and customer segmentation |
| Power BI | Interactive dashboard creation |
| Gamma AI | Project presentation (PPT) |

## 4. Project Workflow

### Step 1: Data Loading & Exploration (Python)

- Imported the dataset using Pandas.
- Explored the dataset using `head()`, `info()`, and `describe()`.
- Checked missing values and data types.
- Understood the structure of the dataset.

### Step 2: Data Cleaning & Feature Engineering (Python)

- Handled missing values using category-wise median imputation.
- Standardized column names.
- Created age groups: Young Adult, Adult, Middle-aged, and Senior.
- Converted purchase frequency into numerical days.
- Removed redundant columns after checking data consistency.

### Step 3: Database Integration (MySQL)

- Connected Python with MySQL using SQLAlchemy and mysql-connector-python.
- Created a database named `customer_behavior`.
- Loaded the cleaned DataFrame into a MySQL table named `customer`.

### Step 4: Business Analysis (MySQL)

Performed SQL analysis to answer 10 important business questions:

1. Revenue comparison between male and female customers.
2. Identification of high-spending customers who used discounts.
3. Top 5 products based on average review ratings.
4. Comparison of average purchase amounts for Standard and Express shipping.
5. Spending and revenue comparison between subscribers and non-subscribers.
6. Identification of products with the highest percentage of discounted purchases.
7. Customer segmentation into New, Returning, and Loyal customers.
8. Identification of the top 3 most purchased products in each category.
9. Analysis of the relationship between repeat purchases and subscriptions.
10. Revenue contribution by age group.

### Step 5: Dashboard Development (Power BI)

- Connected and imported the analyzed data.
- Created an interactive dashboard.
- Used visualizations to present customer behavior and purchasing trends.
- Presented important business metrics and insights in an easy-to-understand format.

### Step 6: Project Report & Presentation

- Created a detailed project report summarizing the analysis and business recommendations.
- Used Gamma AI to prepare a professional PowerPoint presentation explaining the project workflow, analysis, and findings.

## 5. Power BI Dashboard

The Power BI dashboard provides a visual overview of customer shopping behavior and helps understand purchasing trends and business performance.


## 6. Key Results & Business Recommendations

Based on the analysis, the following business recommendations were identified:

- **Boost Subscriptions:** Promote exclusive benefits to encourage more customers to subscribe.
- **Customer Loyalty Programs:** Reward repeat buyers to encourage them to become loyal customers.
- **Review Discount Policies:** Balance discount strategies with profitability and margin control.
- **Product Positioning:** Highlight top-rated and best-selling products in marketing campaigns.
- **Targeted Marketing:** Focus marketing efforts on high-revenue age groups and Express shipping users.

## 7. Project Deliverables

| Deliverable | File |
|---|---|
| Python Analysis | Customer_Shopping_Behavior_Analysis.ipynb |
| SQL Analysis | SQL queries file |
| Power BI Dashboard | Customer_Shopping_Behavior_Dashboard.pbix |
| Project Report | Customer Shopping Behavior Analysis Report.pdf |
| Presentation | Gamma AI PPT |

## 8. How to Run This Project

Follow these steps to reproduce the analysis:

**Prerequisites:**
- Python 3.x
- Jupyter Notebook
- MySQL Server
- Power BI Desktop

**Step 1: Clone the Repository**

```bash
git clone https://github.com/ShivaniKumari/customer-shopping-behavior-analysis.git
```

**Step 2: Navigate to the Project Folder**

```bash
cd customer-shopping-behavior-analysis
```

**Step 3: Install Required Python Libraries**

```bash
pip install pandas sqlalchemy mysql-connector-python jupyter
```

**Step 4: Open Jupyter Notebook**

```bash
jupyter notebook
```

Open `Customer_Shopping_Behavior_Analysis.ipynb` and execute the cells.

**Step 5: Configure MySQL Connection**

Update your MySQL username, password, host, port, and database details in the notebook.

**Step 6: Run SQL Queries**

Execute the SQL queries using MySQL Workbench or another MySQL client.

**Step 7: Open Power BI Dashboard**

Open the `.pbix` file in Power BI Desktop to explore the dashboard.

## 9. Skills Demonstrated

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Python & Pandas
- SQL & MySQL
- Data Manipulation
- Customer Segmentation
- Business Analysis
- Data Visualization
- Power BI Dashboard Development
- Business Insights & Reporting

## 10. Conclusion

This project demonstrates an end-to-end data analytics workflow, from raw data preparation to business insights and interactive visualization.

By combining Python, MySQL, and Power BI, the project helps transform raw customer transaction data into meaningful information that can support data-driven business decisions.

---

**Project Type:** End-to-End Data Analytics Project

**Created by:** Shivani Kumari

**Role:** Aspiring Data Analyst
