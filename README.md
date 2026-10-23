# 🛍️ Customer Shopping Behavior Analysis

**An End-to-End Data Analytics Project Using Python, MySQL, and Power BI**

## 📌 Project Overview

This project explores customer shopping behavior to uncover purchasing patterns, evaluate product category performance, and understand customer preferences using data analytics.

The project follows a structured analytical workflow, starting with data loading and preparation in Python, continuing with Exploratory Data Analysis (EDA) and SQL-based business analysis in MySQL, and concluding with an interactive Power BI dashboard and a business-focused report.

The goal is to transform raw customer data into meaningful insights that support data-driven retail decision-making.

## 🎯 Business Objectives

* Analyze customer purchasing patterns and preferences.
* Compare sales and revenue across product categories.
* Explore customer demographics and age-group purchasing behavior.
* Examine subscription status, discounts, and shipping preferences.
* Investigate customer ratings and payment preferences.
* Present key performance indicators and analytical findings through an interactive dashboard.
* Translate data insights into practical business recommendations.

## 📂 Dataset

**Dataset:** `customer_shopping_behavior.csv`

The dataset contains information about customer demographics, purchased products, transaction amounts, and shopping preferences.

### Key Attributes

| Category             | Example Columns                                                   |
| -------------------- | ----------------------------------------------------------------- |
| Customer Information | Customer ID, Age, Gender, Location                                |
| Product Information  | Item Purchased, Category, Size, Color, Season                     |
| Purchase Details     | Purchase Amount (USD), Previous Purchases, Frequency of Purchases |
| Customer Feedback    | Review Rating                                                     |
| Shopping Preferences | Subscription Status, Shipping Type, Payment Method                |
| Promotions           | Discount Applied, Promo Code Used                                 |

## 🛠️ Tools & Technologies

| Tool     | Purpose                                             |
| -------- | --------------------------------------------------- |
| Python   | Data analysis and preparation                       |
| PyCharm  | Python development environment                      |
| Pandas   | Data manipulation, cleaning, and analysis           |
| MySQL    | SQL queries and business analysis                   |
| Power BI | Interactive dashboard development and visualization |
| Gamma    | Presentation creation                               |

## 🔄 Project Workflow

### 1. Data Loading and Inspection — Python

* Imported the CSV dataset into Python using Pandas.
* Examined the dataset structure, column names, and data types.
* Reviewed the data to understand its contents and analytical potential.

### 2. Data Cleaning and Preparation — Python & Pandas

* Checked data quality and consistency.
* Examined missing values and duplicate records.
* Reviewed data types and prepared the data for analysis.
* Applied relevant cleaning steps based on the issues identified.

### 3. Exploratory Data Analysis (EDA) — Python

* Explored customer demographics and shopping patterns.
* Analyzed purchase amounts and product categories.
* Investigated customer ratings, subscription status, and shopping preferences.
* Examined trends and relationships to identify areas for further analysis.

### 4. SQL Business Analysis — MySQL

Used MySQL to investigate customer shopping behavior and answer business questions through SQL queries.

The analysis may include techniques such as:

* Filtering and sorting records.
* Aggregate functions.
* GROUP BY and HAVING.
* Conditional logic.
* Joins and subqueries, where applicable.
* Category-level and customer-segment comparisons.

Queries are designed to summarize data, compare performance, and support business-focused analysis.

### 5. Interactive Dashboard Development — Power BI

Developed a Power BI dashboard to provide a visual overview of customer shopping behavior.

**Key Performance Indicators (KPIs):**

* Total Customers
* Average Purchase Amount
* Average Review Rating

**Dashboard Visualizations:**

* Customer Distribution by Subscription Status
* Revenue by Product Category
* Sales by Product Category
* Revenue by Age Group
* Sales by Age Group

**Interactive Filters:**

* Subscription Status
* Gender
* Category
* Shipping Type

The dashboard allows users to explore customer segments and compare purchasing patterns through interactive filters and visualizations.

### 6. Reporting and Presentation

* Organized the analysis into a business-focused project report.
* Summarized key findings and recommendations.
* Created a presentation using Gamma to communicate the project objectives, analytical workflow, dashboard, and conclusions.

## 📊 Power BI Dashboard Preview

The dashboard combines KPI cards, category-level comparisons, customer segmentation, and interactive filters to make shopping behavior easier to explore.

**Dashboard Screenshot**

Add your actual Power BI dashboard screenshot here.

To display it in GitHub, save the screenshot in your repository's `images` folder and use:

`![Customer Shopping Behavior Power BI Dashboard](images/customer_behavior_dashboard.png)`

Replace the path with the actual screenshot location in your repository.

## 💡 Results and Business Value

This project demonstrates how customer shopping data can be analyzed and presented to support retail business decisions.

The analysis focuses on:

* Comparing sales and revenue across product categories.
* Exploring purchasing patterns across age groups and genders.
* Examining customer distribution by subscription status.
* Understanding shopping preferences, including shipping and payment methods.
* Identifying potential opportunities for customer segmentation and targeted marketing.

**Note:** Specific numerical findings and recommendations should be added after verifying them against the actual Python analysis, MySQL query results, and Power BI dashboard.

## ▶️ How to Run the Project

### Prerequisites

Install or prepare:

* Python 3
* PyCharm
* Pandas
* MySQL Server
* MySQL Workbench
* Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

Replace the placeholders with your actual repository URL and folder name.

### Step 2: Set Up Python

Open the project in PyCharm and install the required libraries in your project environment.

```bash
pip install pandas numpy matplotlib seaborn
```

Install only the libraries used by your actual Python scripts.

### Step 3: Load the Dataset

Place `customer_shopping_behavior.csv` in the appropriate project folder.

Example Python code:

```python
import pandas as pd

df = pd.read_csv("data/customer_shopping_behavior.csv")

print(df.head())
print(df.shape)
print(df.info())
```

Update the file path if your dataset is stored elsewhere.

### Step 4: Run the Python Analysis

Open your Python script in PyCharm and execute it to reproduce the data preparation and EDA steps implemented in your project.

### Step 5: Run the MySQL Queries

1. Start MySQL Server.
2. Import the dataset into MySQL or use your existing database table.
3. Open the project's SQL script in MySQL Workbench.
4. Update database and table names where necessary.
5. Execute the queries to reproduce the SQL analysis.

### Step 6: Open the Power BI Dashboard

Open the `.pbix` file in Power BI Desktop.

If necessary, update the dataset source path and refresh the data.

## 📁 Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── python/
│   └── customer_shopping_analysis.py
│
├── sql/
│   └── customer_shopping_analysis.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── images/
│   └── customer_behavior_dashboard.png
│
├── reports/
│   └── customer_shopping_analysis_report.pdf
│
├── presentation/
│   └── customer_shopping_analysis_presentation.pptx
│
└── README.md
```

This is a suggested structure. Keep only files and folders that you actually create and intend to share.

## 🧠 Skills Demonstrated

* Python Programming
* Pandas Data Manipulation
* Data Cleaning and Preparation
* Exploratory Data Analysis (EDA)
* SQL Querying with MySQL
* PyCharm Development Environment
* Power BI Dashboard Development
* KPI Analysis and Data Visualization
* Business Reporting and Data Storytelling

## 🏁 Conclusion

The Customer Shopping Behavior Analysis project demonstrates an end-to-end approach to working with customer data—from Python-based preparation and exploratory analysis to MySQL querying and interactive Power BI visualization.

By combining analytical techniques with dashboard development and business reporting, the project showcases practical skills relevant to Data Analyst and Business Intelligence roles.

**Project Domain:** Retail Analytics | Customer Shopping Behavior
**Project Type:** Data Analytics Portfolio Project

