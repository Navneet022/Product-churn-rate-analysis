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



### 📊 Phase 2 – Excel-Based Cohort & Churn Modeling

- Created cohorts by signup month and calculated D30/D60/D90 retention
- Labeled users: **New**, **Active**, **Dormant**, **Churned**
- Found the majority churned after 30 days, revealing critical intervention window


### 🧠 Phase 3 – Python RFM Segmentation

- Segmented users into: High Spenders, Recent Low Value, Inactive, Other
- Built personalized re-engagement strategy for each segment
- Bonus: Found "Other" segment (approx 32%) as an untapped upsell zone


### 🗓️ Phase 4 – Seasonal + Weekly Demand Analysis

- Friday = strongest day (160+ orders); Tuesday-Wednesday maintain consistency (150+ orders each)
- Monday shows 19% performance drop (~118 orders), Thursday shows 7% performance drop (~138 orders)
- 1,000+ missed orders annually due to weekly performance dips
- December surge (54 orders) and February volatility - 2023 was worst performing month while 2024 was strong (50 orders), suggesting external factors drive seasonal variance


### 💸 Phase 5 – Pricing & Product Strategy

- Identified full pricing spectrum across categories ($5 → $490)
- Gadgets and Electronics reach highest price points (~$489)
- Home products span full range from $5.39 to premium tiers
- Recommended bundling strategy i.e. create tiered offerings within each category, bundle low-entry items with premium products across categories.


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
