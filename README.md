# 📦 Supply Chain Analysis

End-to-End Data Analysis | Delivery Performance | Profitability | Machine Learning

📄 Source Report:[Supply_Chain_Analysis_Report.docx](https://github.com/user-attachments/files/26905231/Supply_Chain_Analysis_Report.docx)


### 🚀 Project Overview

This project presents a complete end-to-end supply chain analysis of a global e-commerce dataset (180K+ records).

The goal was to:

- Identify delivery delays
- Analyze profitability trends
- Detect operational bottlenecks
- Build a machine learning model to predict late deliveries
### 🎯 Business Problem

A global e-commerce company is facing:

- High late delivery rates
- Mismatch between promised vs actual shipping
- Declining operational efficiency
- Potential impact on customer satisfaction & retention
  
### 📊 Dataset Summary
- Rows: 180,519
- Columns: 53
- Cleaned Rows: 172,765
- Revenue: $36.78M
- Net Profit: $3.97M
  
### 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
  
## 🧹 Data Cleaning & Preprocessing

Key steps performed:

- Removed PII data (Email, Password, Names)
- Dropped:
  - Missing columns (Product Description)
  - High-null columns (Order Zipcode ~86%)
  - Redundant & ID columns
- Converted date columns to datetime
- Removed canceled orders
- Created new features:
  - Delay
  - Is_Delayed
  - Order Processing Time
  - Profitability Flag
  - Time-based features (month, day, hour)
    
### 📈 Key KPIs
* KPI	                  Value
- Late Delivery Rate	  54.71%
- On-Time Delivery	    45.29%
- Total Revenue	        $36.78M
- Net Profit	          $3.97M
- Avg Profit Margin	    12.06%
- 90th Percentile Delay	3 Days
  
## 🔍 Exploratory Data Analysis (EDA)

Major Findings:
- 54%+ orders are delayed → Critical issue
- Most delays are 1–3 days (fixable)
- No strong correlation between delay & profit
- ~18.7% orders are loss-making
### ⚠️ Critical Insights
- 1. First Class Shipping Failure
  - 100% late delivery rate
  - Indicates systemic failure in SLA planning
2. Second Class Issues
  - ~79.8% delayed
  - Major operational bottleneck
3. Same Day Shipping
  - 0% delay
  - Most reliable mode
4. Global Problem
  - Delays exist across all regions → not location-specific
5. Revenue Concentration

Top 3 categories contribute:

  - 42% of total revenue
### 📊 Bottleneck Analysis

Delay drivers analyzed across:

- Shipping Mode
- Region
- Customer Segment
- Department
- Order Status

### 👉 Conclusion:

- Shipping Mode = strongest factor
- Customer segment has minimal impact
## 🤖 Machine Learning Model
### 🎯 Objective

Predict whether an order will be delayed or not

### 🔧 Model Used
- Random Forest Classifier
## ⚙️ Features Used
- Shipping Mode
- Order Region
- Category Name
- Customer Segment
- Order Month & Hour
- Scheduled Shipping Days
### ⚖️ Handling Imbalance
- Applied SMOTE (Synthetic Oversampling)
### 📊 Performance
- Accuracy: ~80%
- Recall (Late Orders): ~85–90%
- Precision: ~75–80%

### 👉 Model successfully predicts late deliveries before shipment

### 📌 Key Business Insights
- Delay is a systemic issue, not random
- Over-promising delivery dates is a major cause
- Discounts are reducing profitability
- Logistics needs re-optimization

### 📬 Contact

Vedant Kharwade
Aspiring Data Analyst

📧 vedantkharwade123@gmail.com

🔗 https://www.linkedin.com/in/vedant-kharwade-45b82224b/
