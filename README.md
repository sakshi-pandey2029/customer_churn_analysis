# customer_churn_analysis

# 📊 Customer Churn Analysis & Retention Strategy
## 📌 PROJECT OVERVIEW

This project focuses on analyzing customer churn behavior to identify key drivers of customer attrition and recommend actionable strategies to improve retention.

The goal is not just to measure churn, but to understand why customers leave and propose data-driven solutions.


## 🎯 OBJECTIVES
Analyze customer churn patterns

Identify leading indicators of churn

Perform root cause analysis

Build a Churn Playbook with actionable recommendations


## 🛠️ TOOLS & TECHNOLOGIES
1. SQL Server (SSMS) – Data cleaning & analysis
2. Power BI – Data visualization (optional)
3. Excel – Initial data inspection

## 🧹 DATA CLEANING
1. Handled  null values in TotalCharges
2. Treated NULL values in TechSupport logically
3. Validated data types and removed inconsistencies

## 📊 KEY ANALYSIS
### 1. Churn Distribution
1. Calculated overall churn rate
2. Identified percentage of customers leaving

### 2. Churn by Tenure (Customer Lifecycle)
1. Segmented customers into tenure groups
2. Found highest churn in early months (0–3 months)

### 3. Churn by Customer Type
1. Compared new vs old customers
2. New customers showed significantly higher churn

### 4. Churn by Contract Type
1. Month-to-month customers had highest churn
2. Long-term contracts improved retentio
  
### 5. Churn by Services
1. Customers without Tech Support showed higher churn
2. Service usage strongly impacts retention


## 🔍 KEY INSIGHTS
🔥 Early-stage customers (0–3 months) are most likely to churn

📉 Month-to-month contracts lead to higher churn

⚠️ Lack of tech support increases churn risk

💰 High monthly charges may lead to dissatisfaction


## 🚨  HIGH RISK SEGMENT

### 🔴 Segment A: New Customers
1. Tenure ≤ 3 months
2. High churn probability

### 🔴 Segment B: Flexible Contract Users
1. Month-to-month plan
2. Low commitment

### 🔴 Segment C: No Support Users
1. TechSupport = 0
2. Higher dissatisfaction risk


## 🚀  CHURN PLAYBOOK (ACTION PLAN)

## 🔥 Segment A: New Customers (0–3 months)
### 📉 Problem:
High early churn
### 🧠 Root Cause:
1. Poor onboarding
2. Low engagement
### ✅ Actions:
1. Send onboarding email series (Day 1, 3, 7)
2. Provide product tutorials/videos
3. Offer first-month incentives

## 🔥 Segment B: Month-to-Month Customers
### 📉 Problem:
1. Easy to churn anytime
### 🧠 Root Cause:
1. No long-term incentive
### ✅ Actions:
1. Offer discount on yearly plans
2. Show savings comparison
3. Provide loyalty rewards

## 🔥 Segment C: No Tech Support
### 📉 Problem:
1. Customers lack assistance
### 🧠 Root Cause:
1. Unresolved issues → frustration
### ✅ Actions:
1. Offer free tech support trial
2. Provide proactive help emails
3. Add chatbot/live support
   
## 🔥 Segment D: High Monthly Charges
### 📉 Problem:
1.Customers feel cost is high
### 🧠 Root Cause:
1. Low perceived value
### ✅ Actions:
1. Offer personalized discounts
2. Bundle services
3. Provide premium support

## ⚡HIGH-RISK COMBINATION (CRITICAL 🔥)
## 🚨 Customers with:
1. Tenure ≤ 3 months
2. Month-to-month contract
3. No tech support

#### 👉 Highest churn probability

### ✅ Action:
1. Immediate engagement campaign
2. Assign customer success support
3. Offer retention discount


## 🤖AUTOMATED RETENTION RULES

Turn insights into real actions:

If tenure ≤ 7 days → send onboarding email

If new + inactive → send reminder

If high-value + no support → assign support agent

If month-to-month → show yearly upgrade offer


## 📊BUSINESS IMPACT
1. 📉 Reduce churn rate
2. 💰 Increase customer lifetime value (LTV)
3. 📈 Improve retention and revenue stability


## 🧠FINAL SUMMARY 

This playbook translates data insights into actionable strategies, focusing on early customer engagement, service support, and contract optimization to reduce churn and improve retention.

