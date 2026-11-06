
# Olist E-Commerce Sales Dashboard

## Problem
Analyze Olist Brazilian e-commerce data to understand sales performance, customer experience and the impact of delivery time on ratings.

## Dataset
Olist Brazilian E-Commerce Dataset (Kaggle): https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Only delivered orders were used (~96K orders).

## Tools
Python (Pandas), Power BI, DAX

## Data Preparation
Merged 7 tables (orders, items, products, category translation, customers, reviews, payments) in the notebook. Created columns: month, delivery_days, is_late.

## KPIs
- Total Revenue: R$13.22M
- Total Orders: 96K
- Average Order Value: R$137.04
- Avg Review Score: 4.08
- Avg Delivery Days: 12.01
- Late Delivery %: 8.11%

## Key Insights
1. Orders grew through 2017 and levelled off in 2018 (about 6-7K per month).
2. Revenue follows the same trend and levels off around R$0.8M-1.0M per month.
3. São Paulo (SP) has the most orders, far ahead of RJ and MG.
4. bed_bath_table is the top category by orders, followed by health_beauty and sports_leisure.
5. 1-star orders took about 19 days to deliver vs about 10 days for 5-star orders.
6. AL and MA have the highest late delivery rates (about 20%+), though small states have fewer orders, so the rate is less reliable.

## Files
- olist project pandas.ipynb: data cleaning and merging
- olist_dashboard.pbix: Power BI dashboard
- dashboard.png: dashboard screenshot

## Notes
Revenue = product price only (freight excluded).
