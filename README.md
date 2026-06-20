# 📊 Customer Retention & Churn Analysis

## 📊 Project Overview

This project analyzes customer and subscription data for a telecommunications company to trace the core drivers of customer churn. The goal is to identify high-risk customer segments, calculate customer lifetime trends, and connect data analytics directly to business revenue by evaluating the exact financial impact of lost subscribers.

## 🎯 Answering the Core Business Questions

* **What is the financial impact of current churn?** Out of 7,032 analyzed customers, the overall corporate churn rate sits at 26.58%. This translates to a massive bleed of **$139,000+ in lost monthly revenue**.
* **Which customer segments are most likely to churn?** Contract type is the ultimate driver. Customers on Month-to-Month contracts account for the vast majority of churn compared to highly stable 1-year and 2-year subscribers. 
* **When are users dropping off?** The onboarding phase is the highest risk period. Churn spikes drastically within the first 1 to 5 months of tenure. If a customer survives the first 6 months, retention stabilizes significantly.
* **Why are customers leaving premium tiers?** Churned customers show a consistently higher median monthly expenditure. Specifically, Fiber Optic customers are churning at a highly disproportionate rate compared to DSL users, indicating a severe gap between price and perceived value.
* **What actions can improve customer retention?** By reallocating efforts to transition Month-to-Month users to annual contracts within their first 90 days (via targeted discounts) and mandating 30/60-day customer success check-ins, the business can rapidly recover lost capital.

## 🛠️ Tools & Technologies Used

* **Python (Pandas):** Data cleaning, feature engineering, cohort grouping, and KPI calculation (Churn Rates, Revenue Bleed).
* **Seaborn & Matplotlib:** Generating presentation-ready static dashboard visualizations and segment analysis charts.
* **Google Colab:** Environment for exploratory data analysis, code execution, and executive reporting.

## 📈 Visual Dashboards & Evidence

**1. The Primary Retention Driver: Contract Type**
![Contract Type Chart](Screenshot%20(228).png)

**2. Identifying the Drop-off Zone: Customer Tenure**
![Tenure Histogram](Screenshot%20(229).png)

**3. Price Friction: Monthly Charges Impact**
![Monthly Charges Impact](Screenshot%20(230).png)

**4. Service Tier Friction: Internet Service Type**
![Internet Service Chart](Screenshot%20(231).png)

**5. Advanced Segment Analysis**
![Segment Analysis](Screenshot%20(232).png)

**6. Customer Lifecycle Cohort Analysis**
![Cohort Analysis](Screenshot%20(233).png)
