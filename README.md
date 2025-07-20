               # Product Analytics Intelligence Project: Churn and Customer Retention Case Study

# 📦 Product Analytics Intelligence Project

## 🔍 Project Overview

A simulated end-to-end product analytics system using SQL, Excel, and Python to replicate real-world e-commerce analysis. The project includes data cleaning, churn modeling, cohort analysis, RFM segmentation, pricing strategies, and business recommendations,  all backed by real-world-style messy data and stakeholder-ready insights.

## 📊 Tools & Stack

- **SQL** – for cleaning, joining, filtering transactional data
- **Excel** – for cohort modeling, churn segmentation, pivoting
- **Python (Pandas, NumPy, Seaborn, Matplotlib)** – for RFM segmentation, churn prediction, seasonal analysis
- **Google Colab** – environment used
- **Dataset** – 12K+ orders, 4K+ users, 1K+ products

## 🔢 Key Project Phases

### 🧹 Phase 1 – SQL Cleaning & Joins

- Cleaned missing values across orders and user data (~800 rows)
- Joined user–order–product tables for behavioral insights
- Key finding: Signups peak early month, most users place their first order within 14 days

  ![Distribution of user segment]([path/to/image](https://www.notion.so/Product-Analytics-Churn-and-Customer-Retention-Case-Study-22fc6ddfff8680a5997ece92ef7a898f?source=copy_link#230c6ddfff868032af28e0a1b55960fb))


### 📊 Phase 2 – Excel-Based Cohort & Churn Modeling

- Created cohorts by signup month and calculated D30/D60/D90 retention
- Labeled users: **New**, **Active**, **Dormant**, **Churned**
- Found the majority churned after 30 days, revealing critical intervention window

attachment:8217d765-8f22-4d6b-a458-c2c761d75df0:Distribution_of_Valid__User_Segment.png

### 🧠 Phase 3 – Python RFM Segmentation

- Segmented users into: High Spenders, Recent Low Value, Inactive, Other
- Built personalized re-engagement strategy for each segment
- Bonus: Found "Other" segment (approx 32%) as an untapped upsell zone

![User_count_RFM_segment.png](attachment:7188a682-1199-4fb5-a3ff-1de2a9f2ed46:User_count_RFM_segment.png)

### 🗓️ Phase 4 – Seasonal + Weekly Demand Analysis

- Friday = strongest day (160+ orders); Tuesday-Wednesday maintain consistency (150+ orders each)
- Monday shows 19% performance drop (~118 orders), Thursday shows 7% performance drop (~138 orders)
- 1,000+ missed orders annually due to weekly performance dips
- December surge (54 orders) and February volatility - 2023 was worst performing month while 2024 was strong (50 orders), suggesting external factors drive seasonal variance

![Orders by week.png](attachment:319e781e-0333-443c-85be-573d55c92129:Orders_by_week.png)

![Monthly order volumne over time.png](attachment:0f5fc605-548c-45e7-95ab-4fa5da8446e6:Monthly_order_volumne_over_time.png)

### 💸 Phase 5 – Pricing & Product Strategy

- Identified full pricing spectrum across categories ($5 → $490)
- Gadgets and Electronics reach highest price points (~$489)
- Home products span full range from $5.39 to premium tiers
- Recommended bundling strategy i.e. create tiered offerings within each category, bundle low-entry items with premium products across categories.

![TotalRevenue by Product.png](attachment:970e7cba-93d0-418b-a780-dc43c7dbcc38:TotalRevenue_by_Product.png)

## 📈 Business Recommendations

| Area | Strategy |
| --- | --- |
| **Retention** | Implement 15/20/25 day automated re-engagement email sequences - cheaper than acquiring new clients with 25-30% churn reduction potential |
| **Revenue** | Launch "Monday Back-to-Work Sales" and "Thursday Flash Sales" to capture 1,000+ annual missed orders |
| **Marketing** | Allocate 70% of annual budget to April–October period, reserve 30% for Q4 optimization with 2-month inventory preparation lead time |
| **Segmentation** | Deploy targeted campaigns using RFM segments: VIP treatment for 180 High Spenders, upsell campaigns for 300 Recent Low Value users, win-back sequences for 115 Inactive users, and strategic engagement for 320 "Other" segment users |
| Operations | Prepare inventory 2 months ahead for Q4 demand surge and be prepared for February volatile nature. |

## 🎯 **Quantified Impact Projections**

- 25-30% churn reduction through early intervention
- 1,000+ annual order recovery through weekly optimization
- 320 "Other" segment users represent approximately 32% untapped revenue potential
- Strategic marketing budget reallocation for maximum ROI during peak periods
