# 🎯 Target SQL Business Case Study – Brazil E-commerce Analysis
# 📌 Overview
This project analyzes Target’s e-commerce operations in Brazil using SQL to derive actionable business insights. The dataset covers 100,000+ orders from Sept 2016 to Oct 2018, spanning 27 states and 8011 cities.

Through exploratory analysis, trend detection, and performance evaluation, this case study identifies growth opportunities, logistical challenges, and consumer behavior patterns to improve Target’s market strategy in Brazil.

# 📂 Dataset Details - [![Dataset](https://img.shields.io/badge/Google%20Drive-View%20Dataset-blue)](https://drive.google.com/drive/folders/1TGEc66YKbD443nslRi1bWgVd238gJCnb)

Source: Internal dataset (8 CSV files) covering orders, customers, sellers, products, reviews, payments, order items, and geolocations.

| File Name        | Description                              |
| ---------------- | ---------------------------------------- |
| customers.csv    | Customer demographics & location         |
| sellers.csv      | Seller details                           |
| order\_items.csv | Product, seller, price, and freight data |
| geolocation.csv  | Zip code to city/state mapping           |
| payments.csv     | Payment method, installments, and value  |
| reviews.csv      | Customer reviews & scores                |
| orders.csv       | Order timestamps, status, delivery info  |
| products.csv     | Product category & attributes            |



# 🛠 Tools & Technology
Google BigQuery – SQL querying & analysis

SQL functions: Aggregations, Joins, Window Functions, Date/Time Functions, CTEs

# 📊 Key Insights
Growth Trend: E-commerce in Brazil grew steadily until Nov 2017, followed by a seasonal dip.

Peak Month: November had the highest orders; September had the lowest.

Purchase Time: Night orders dominate, followed by Afternoon and Morning.

Regional Insights: State SP contributed ~42% of customers; AP & RR had the least.

Economic Impact: Revenue grew by ~143% (Jan–Aug 2017 vs Jan–Aug 2018).

Freight & Delivery: SP had the lowest freight and fastest delivery (~8 days); AP & RR had the slowest (~28 days).

Payment Preferences: Credit Cards dominate, followed by UPI, vouchers, and debit cards.

Product Trends: Top categories – Bed Table Bath, Sports Leisure, Furniture; lowest – CD Music DVDs.



# 💡 Recommendations
Expand product variety in top-selling categories.

Promote slow months with discounts, vouchers, and free delivery offers.

Establish warehouses near high-freight states to reduce costs.

Improve delivery speed in slower states via stock forecasting.

Partner with banks to promote debit card usage through exclusive offers.

Bundle complementary products to increase basket size.

# 📑 Deliverables
SQL scripts answering all business questions.

First 10-row query outputs (screenshots).

Final PDF report with analysis, insights, and recommendations.
