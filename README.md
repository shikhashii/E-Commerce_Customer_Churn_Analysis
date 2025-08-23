# 📊 E-Commerce Customer Churn Analysis – SQL Project

## 📌 Project Overview
Customer churn is a critical challenge for e-commerce and subscription-based businesses. This project analyzes customer churn data using SQL to uncover patterns, identify at-risk customer segments, and provide actionable recommendations for reducing churn.

The project includes:
- **SQL Queries**: Data cleaning, exploration, and analysis
- **Churn Insights**: Key findings with churn rates across different dimensions
- **Business Recommendations**: Practical steps to improve customer retention
---

## 🗂 Dataset
- **Source**: E-commerce churn dataset (Kaggle)
- **Size**: 5,500+ customers  
- **Key Columns**:  
  - `CustomerID` – Unique identifier  
  - `City_Tier` – Tier 1 / Tier 2 / Tier 3  
  - `Payment_Mode` – COD, Credit Card, E-Wallet, etc.  
  - `Satisfaction_Score` – 1–5 rating  
  - `Complaints` – Whether customer raised complaints  
  - `App_Usage_Hours` – Daily usage in hours  
  - `Login_Device` – Phone, Computer, Mobile App  
  - `Order_Category` – Mobile Phones, Fashion, Grocery, etc.  
  - `Cashback_Amount` – Cashback received  
  - `Churn` – 1 = Churned, 0 = Retained  

---

## 🔍 SQL Analysis
The SQL workflow includes:
1. **Data Cleaning**  
   - Handling null values, duplicates, and inconsistent entries
2. **Exploratory Data Analysis (EDA)**  
   - Distribution of churn vs non-churn  
   - Segmentation by demographics & behavior  
3. **Churn Analysis Queries**  
   - Churn rate by City Tier, Payment Mode, Device, and Order Category  
   - Impact of complaints, cashback, and satisfaction on churn  
   - Identification of high-risk customer groups  

---

## 📈 Key Insights
- **Overall Churn**: 770 of 4,293 customers → **17.94%**  
- **City Tier**: Tier 3 (22.39%) & Tier 2 (21.74%) churn higher than Tier 1 (15.49%)  
- **Payment Mode**: COD (24.20%) & E-Wallet (23.48%) highest; Credit Card lowest (15.08%)  
- **Satisfaction**: High scorers churn more (25.35%) than low scorers (12.35%)  
- **Complaints**: Customers with complaints churn **3× more** (33.58% vs 11.84%)  
- **App Usage**: Medium users churn most (18.07%)  
- **Device**: Phone (21.21%) > Computer (20.66%) > Mobile App (14.42%)  
- **Order Category**: Mobile Phones churn highest (26.44%); Grocery lowest  
- **Cashback**: Medium cashback churn highest (17.99%)  

---

## 💡 Recommendations
- 🎯 Focus retention campaigns on **Tier 2 & Tier 3 customers**  
- 💳 Encourage shift from **COD/E-Wallet to Credit Card** with cashback offers  
- 🛠️ Investigate why **high-satisfaction customers still churn**  
- 📞 Improve **complaint resolution process** to reduce churn risk  
- 🚀 Offer **loyalty benefits for high-value categories** (Mobile Phones, Fashion)  

---
