# 🛍️ Customer Behavior Dashboard 

[![Power BI](https://img.shields.io/badge/Power_BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black)](#)
[![Data Analysis](https://img.shields.io/badge/PostgreSQL-blue?style=for-the-badge)](#)
[![Data Analysis](https://img.shields.io/badge/Python-red?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](#)


An end-to-end data analytics project focused on analyzing customer purchasing behavior, sales performance, revenue distribution, and subscription trends using **Python**, **Pandas**, **PostgreSQL**, **SQL**, and **Power BI**.

---

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Tech Stack](#-tech-stack)
- [Dataset Description](#-dataset-description)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Data Analysis Workflow](#-data-analysis-workflow)
- [Dashboard Features](#-dashboard-features)
- [Key Business Insights](#-key-business-insights)
- [Dashboard Preview](#-dashboard-preview)
- [Project Structure](#-project-structure)
- [Skills Demonstrated](#-skills-demonstrated)
- [Conclusion](#-conclusion)

---

## 🎯 Project Overview
The **Customer Behavior Dashboard** is an interactive business intelligence project developed to understand customer demographics, purchasing patterns, product category performance, and subscription behavior.

The project follows an end-to-end data analytics workflow, beginning with data cleaning and wrangling using **Python** and **Pandas**, followed by database integration and SQL analysis using **PostgreSQL**. Finally, **Power BI** is used to create an interactive dashboard with KPI cards, bar charts, horizontal bar graphs, and a donut chart.

The dashboard helps identify high-performing product categories, compare sales and revenue across age groups, monitor customer spending, and evaluate subscription status.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **Python** | Data processing and preparation |
| **Pandas** | Data cleaning, manipulation, and wrangling |
| **PostgreSQL** | Database storage and management |
| **SQL** | Data querying, filtering, grouping, and aggregation |
| **Power BI** | Interactive dashboard development and reporting |
| **Bar Charts** | Sales and revenue comparison by product category |
| **Donut Chart** | Subscription status visualization |
| **KPI Cards** | Display of key business performance metrics |

---

## 📊 Dataset Description
The dataset contains customer demographic information, purchasing details, product categories, review ratings, shipping preferences, and subscription status.

### Key Attributes
- **Customer Demographics:** Age group and gender
- **Product Categories:** Clothing, Accessories, Footwear, and Outerwear
- **Purchase Metrics:** Purchase amount, sales, and revenue
- **Customer Feedback:** Review ratings
- **Subscription Status:** Yes / No
- **Shipping Types:** 2-Day Shipping, Express, Free Shipping, Next Day Air, Standard, and Store Pickup

---

## ❓ Business Problem
Understanding customer purchasing behavior is essential for improving sales performance, optimizing marketing campaigns, and enhancing customer engagement.

However, analyzing raw customer data can make it difficult to identify top-performing product categories, compare customer segments, evaluate subscription participation, and monitor key purchasing metrics.

This project addresses these challenges by integrating Python-based data preparation, PostgreSQL database management, SQL analysis, and Power BI visualization into a unified reporting solution.

---

## 🎯 Project Objectives
- Clean and transform raw customer data using Python and Pandas.
- Connect the cleaned dataset to PostgreSQL for structured data storage.
- Perform SQL operations to filter, group, and analyze customer information.
- Analyze sales and revenue across product categories.
- Compare purchasing behavior across different age groups.
- Track customer count, average purchase amount, and average review rating.
- Visualize subscription status and customer segmentation.
- Develop an interactive Power BI dashboard to support data-driven business decisions.

---

## 🔄 Data Analysis Workflow

### 1. Data Cleaning and Wrangling — Python & Pandas
- Imported the raw dataset into Python using Pandas.
- Inspected the dataset structure, columns, and data types.
- Checked for missing values, duplicate records, and data inconsistencies.
- Cleaned and transformed the data where required.
- Standardized column names and corrected data types.
- Prepared the cleaned dataset for database integration.

### 2. Database Integration and SQL Analysis — PostgreSQL
- Connected the cleaned dataset to PostgreSQL.
- Stored customer data in a structured database table.
- Verified the imported data and table structure.
- Executed SQL queries to retrieve, filter, group, and aggregate records.
- Analyzed customer behavior, category performance, and subscription information.
- Prepared relevant data summaries for visualization.

### 3. Dashboard Development — Power BI
- Connected Power BI to the customer dataset.
- Created KPI cards to display important business metrics.
- Developed bar charts for sales and revenue by product category.
- Created horizontal bar charts to compare performance across age groups.
- Designed a donut chart to visualize subscription status.
- Added interactive filters for subscription status, gender, category, and shipping type.
- Organized the visuals into an interactive dashboard for easy interpretation.

---

## 📈 Dashboard Features

### 1. Key Performance Indicators (KPIs)
The dashboard displays the following headline metrics:

| KPI | Displayed Value |
| :--- | :--- |
| **Number of Customers** | 1.053K |
| **Average Purchase Amount** | $59.49 |
| **Average Review Rating** | 4 |

*These KPIs provide a quick overview of customer volume, average spending, and customer feedback.*

### 2. Revenue by Category
A vertical bar chart compares revenue across Clothing, Accessories, Footwear, and Outerwear.
- **Purpose:** Identify high-performing product categories and evaluate opportunities to improve revenue.

### 3. Sales by Category
A bar chart compares sales performance across different product categories.
- **Purpose:** Understand category-level performance and support product planning and promotional decisions.

### 4. Subscription Status Analysis
A donut chart visualizes the distribution of customers by subscription status.
- **Purpose:** Monitor subscription participation and identify opportunities to improve customer engagement.

### 5. Revenue by Age Group
A horizontal bar chart compares revenue across Middle-aged, Young Adult, Senior, and Adult customer segments.
- **Purpose:** Identify valuable customer segments and support targeted marketing strategies.

### 6. Sales by Age Group
A horizontal bar chart compares sales across different age groups.
- **Purpose:** Understand purchasing patterns and identify customer segments contributing strongly to sales.

### 7. Interactive Filters
The dashboard provides filters for:
- Subscription Status
- Gender
- Product Category
- Shipping Type

*These filters allow users to explore specific customer segments and interactively analyze the displayed metrics.*

---

## 💡 Key Business Insights
- **Category Performance:** Clothing and Accessories show strong performance in the displayed sales and revenue comparisons.
- **Customer Spending:** The average purchase amount is displayed as **$59.49**, providing a reference point for customer spending analysis.
- **Customer Satisfaction:** The average review rating is **4**, offering a high-level view of customer feedback.
- **Age Group Analysis:** Middle-aged and Young Adult customers show strong performance in the displayed age-group comparisons.
- **Subscription Monitoring:** The dashboard currently displays **100% Yes** for subscription status. This result should be validated against the complete dataset and active filters before interpreting it as the overall subscription rate.
- **Business Impact:** The combination of Python, PostgreSQL, SQL, and Power BI enables a structured workflow for transforming raw data into meaningful business insights.

> **Note:** Insights are based on the displayed dashboard. Further validation of the underlying data and metric definitions is recommended before making business decisions.

---


## 📁 Project Structure

```text
Customer-Behavior-Dashboard/
│
├── data/
│   └── customer_behavior.csv
│
├── python/
│   └── data_cleaning.py
│
├── sql/
│   └── customer_analysis.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── images/
│   └── customer_behavior_dashboard.png
│
└── README.md
```

---

## 🧠 Skills Demonstrated
- Python programming
- Pandas data cleaning and wrangling
- Data preprocessing and transformation
- PostgreSQL database integration
- SQL querying and aggregation
- Exploratory data analysis
- Power BI dashboard development
- KPI reporting and data visualization
- Customer segmentation
- Business intelligence and analytical thinking

---

## 📸 Dashboard Preview

![Customer Behavior Dashboard](https://github.com/ayushrivastava195/CustomerBehaviourReport/blob/main/Snap_CustomerBehavior.png)

*The dashboard presents customer KPIs, category-level sales and revenue, subscription status, and age-group comparisons in a single interactive interface.*

---

##  Conclusion
The **Customer Behavior Dashboard** demonstrates an end-to-end data analytics workflow, from data cleaning and wrangling with Python and Pandas to database integration with PostgreSQL and interactive visualization with Power BI.

This project showcases practical skills in data preprocessing, SQL analysis, database management, and business intelligence reporting. It transforms raw customer data into an organized dashboard that helps analyze purchasing patterns, evaluate category performance, and support data-driven business decisions.

---
