# Customer Churn Analysis using SQL

## 📌 Project Overview
This project focuses on analyzing customer churn for an e-commerce platform using SQL. The objective is to identify churn patterns, uncover key drivers of customer attrition, and generate actionable business insights to improve customer retention.

The analysis is performed on a customer-level dataset and follows a structured approach including data cleaning, exploratory analysis, advanced analytics, and business recommendations.

---

## 🎯 Business Objectives

The project aims to answer the following key business questions:

1. What is the overall churn rate of the platform?
2. Which customer behaviors indicate higher churn risk?
3. How do factors like payment mode, satisfaction score, and app usage impact churn?
4. Which high-value customers are at risk of leaving?
5. What strategic actions can help reduce churn?

---

## 🗂 Dataset Description

The dataset contains customer-related attributes such as:

- Customer demographics  
- Transactional behavior  
- App usage patterns  
- Satisfaction scores  
- Complaints  
- Order history  
- Cashback details  
- Churn status  

Each record represents a unique customer along with various behavioral and engagement metrics.

---

## 🛠 Tools & Technologies Used

- **SQL (MySQL)** for data processing and analysis  
- Relational database concepts  
- Window functions  
- Common Table Expressions (CTEs)  
- Data cleaning and transformation techniques  

---

## 🔄 Project Workflow

The project follows a structured analytics pipeline:

### 1. Database Setup & Exploration
- Creation of database and tables  
- Initial data inspection  
- Creation of working copy for analysis  

### 2. Data Cleaning & Preparation
- Duplicate record detection and removal  
- Standardization of categorical values  
- Handling missing values  
- Data validation and transformation  

### 3. Exploratory Data Analysis (EDA)
Key analyses performed include:

- Overall churn rate calculation  
- Churn by payment mode  
- Churn by satisfaction score  
- Impact of customer complaints  
- App usage vs churn  
- Cashback-based churn trends  

These analyses helped in understanding general patterns and customer behavior.

### 4. Advanced Analytics

To derive deeper insights, advanced SQL analytics were implemented:

- **Tenure-Based Customer Segmentation**  
  Customers were categorized into New, Growing, and Loyal segments to evaluate churn trends.

- **SQL-Based Churn Risk Scoring Model**  
  A risk score was developed using factors like:
  - Inactivity  
  - Complaints  
  - Low satisfaction  
  - Low order frequency  

- **High-Value Customer Identification**  
  Detection of high-value customers who are at risk of churning based on order count and inactivity.

- **Churn Driver Analysis**  
  Analysis of how payment modes and other behavioral factors influence churn probability.

- **Consolidated Churn Drivers Summary**  
  Aggregated view of the most impactful churn indicators.

---

## 📊 Key Insights

From the analysis, the following patterns were observed:

- Customers with **complaints and low satisfaction scores** show significantly higher churn rates.  
- Inactive customers (no recent orders) are more likely to churn.  
- Certain payment methods are associated with better retention.  
- Low app engagement strongly correlates with churn behavior.  
- High-value customers with declining activity form a critical risk group.

---

## 💡 Business Recommendations

Based on the findings, the following actions are suggested:

1. Strengthen customer support to quickly resolve complaints.  
2. Introduce loyalty programs targeting inactive customers.  
3. Encourage digital payment methods with incentives.  
4. Run feedback and engagement campaigns for low-satisfaction users.  
5. Monitor high-value customers and implement proactive retention strategies.

---

## 🚀 Conclusion

This project demonstrates how SQL can be used effectively for:

- End-to-end data cleaning  
- Exploratory analytics  
- Customer segmentation  
- Risk modeling  
- Business decision-making

---
