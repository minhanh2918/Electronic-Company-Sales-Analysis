# Electronic-Company-Sales-Analysis
<img width="2425" height="1354" alt="image" src="https://github.com/user-attachments/assets/5e439f18-972f-4481-805a-10357331bc68" />
Dashboard view: https://app.powerbi.com/view?r=eyJrIjoiNDM4OTBjMWUtODc4ZC00OTNkLWI5MjktY2UyMjU4ZDUxYWNmIiwidCI6ImJlODMyOWE3LTcyMTgtNDlhMy05YWMxLWQ3Yjk1NDU2M2YzOSIsImMiOjEwfQ%3D%3D
# Project Overview

This project analyses the sales and profit performance of an electronics company between September 2023 – September 2024. The company sells products such as Smartphones, Laptops, Tablets, Smartwatches, and Headphones. The goal is to track overall business health, identify top-performing products, evaluate customer behaviour, and provide actionable insights for growth.

# Dataset
The dataset covers transactional sales data between September 2023 and September 2024. It contains aggregated monthly values by product, payment type, shipping method, and customer demographics.

# Key Features:
- date (transaction month/year)
- product_type (Smartphone, Laptop, Tablet, Smartwatch, Headphones)
- revenue (monthly revenue amount)
- profit (monthly profit amount)
- profit_margin (%)
- total_orders (monthly order count)
- cancellation_rate (%)
- rating (average customer rating per product)
- shipping_type (Standard, Same Day, Expedited, Overnight, Express)
- payment_type (PayPal, Credit Card, Debit Card, Bank Transfer, Cash)
- customer_gender, loyalty_status, age_group

# Steps to reproduce
**1. Import Datas:** 
Load the dataset into Power BI for visualisation and analysis.

**2. Data Collection**
Collect monthly order, revenue, profit, shipping, and customer data from Sep-2023 → Sep-2024.

**3. Data Cleaning**

**Handling Duplicates**

Remove duplicate rows (same date, product, revenue, profit, etc.) to avoid double-counting.

**Handling Invalid Records**

Ensure profit and revenue values are numeric. Replace errors (e.g., blanks or text) with null and handle accordingly.

**Missing Values**

If profit = 0, keep explicitly.

If data is missing, mark it as null for investigation.

**Standardising Categories**

Normalise product type names (e.g., “Smartp…” → “Smartphone”).

Ensure shipping and payment type categories are consistently labelled.

**Date Formatting**

Convert all dates into YYYY-MM-DD format.

Extract year and month for time-series analysis.

**Profit Validation**

Validate that revenue – cost = profit.

Ensure totals match across product, shipping, and payment breakdowns.

**4. KPI Calculation & Derived Metrics**

Average Monthly Profit: $4.36M

YoY Change: compare Sep 2023 → Sep 2024 growth trends.

MoM Change: identify monthly increases/decreases in orders, revenue, and profit.

QoQ Change: assess quarterly sales performance.

High/Low Flags: identify months with peak sales (Jan 2024: 2,049 orders) and low sales.

**5. Exploratory Data Analysis (EDA)**

**Business Health**

Total Orders: ~20K

Revenue: ~$64M

Profit: ~$52.3M

Profit Margin: 82%

Cancellation Rate: 33%

Avg Rating: 3.09 (low, potential quality or service issue).

**Product Performance**

Smartphone = $21.5M revenue (34%) → top performer.

Smartwatch = $14M (22%) → strong growth.

Laptop = $12.3M (19%).

Tablet = $11.7M (18%).

Headphones = $4.0M (6%) → lowest contribution.

**Customer Analysis**

Customer Count: 12.1K

Avg Revenue per Customer: $5.24K

Avg Orders per Customer: 1.65

Loyalty Rate: 32% (loyal customers generate 21% of revenue).

Gender Split: Male (51%) vs Female (49%), nearly even.

**Payment Methods**

PayPal & Credit Card dominate (~$31M combined).

Debit Card and Cash remain smaller channels.

**Shipping**

Standard shipping = $17.6M profit (highest).

Same Day + Expedited + Overnight = $27.5M profit combined.

**Trends**

MoM: Revenue peaked Jan 2024 ($6.62M), steady decline mid-year, recovery by Aug 2024.

QoQ: Profit dropped in Q2/Q3, partial recovery in Q4.

Customer Retention: Sharp drop after first month (~10% retained after 2 months).

**6. Insights & Recommendations**

Focus Products: Smartphones and Smartwatches are key growth drivers.

Risk Products: Headphones contribute least — consider repositioning or bundling.

Customer Loyalty: Only 32% repeat — invest in loyalty programs to increase retention.

Cancellations: High cancellation rate (33%) needs urgent attention (review fulfilment, product quality, or customer expectations).

Ratings: Average rating 3.09 indicates service/product improvements are required.

Shipping Strategy: Standard shipping dominates, but express and fast delivery options are profitable — opportunity to expand premium delivery upsell.

Payment Strategy: Focus on PayPal/Credit Card partnerships since they account for the majority of revenue.

## Summary
The electronic company shows strong overall profitability (82% margin), but faces issues in customer retention, product ratings, and cancellations. Growth is concentrated in Smartphones and Smartwatches, while Headphones underperform. By cleaning and structuring the data, the dashboard provides actionable insights for product strategy, customer engagement, and operational improvements.
