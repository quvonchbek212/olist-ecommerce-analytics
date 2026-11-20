# 🛒 Olist E-Commerce SQL Analytics & Business Intelligence

[![SQLite](https://img.shields.io/badge/SQLite-3-003B57.svg?style=flat&logo=sqlite&logoColor=white)](https://sqlite.org)
[![SQL](https://img.shields.io/badge/SQL-Advanced%20Queries-CC292B.svg)]()
[![Python](https://img.shields.io/badge/Python-Pandas%20%26%20Colab-3776AB.svg?style=flat&logo=python&logoColor=white)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

An in-depth relational SQL analytics and business intelligence project conducted on the **Brazilian Olist E-Commerce dataset** (100,000+ real orders from 2016 to 2018).

---

## 🎯 Strategic Business Dimensions Solved

1. **Profitability & Category Margins:** Identified top-grossing product categories versus high-volume loss-leaders.
2. **Customer Lifetime Value (CLV):** Cohort analysis revealing repeat buyer rates and churn inflection points.
3. **Seller Performance & Concentration:** Pareto analysis (80/20 rule) of merchant revenues.
4. **Logistics & Delivery Bottlenecks:** Quantified carrier delay patterns across Brazilian states and their direct correlation with customer satisfaction scores.
5. **Review Score Elasticity:** Modeled the quantifiable revenue impact of 1-star vs 5-star customer feedback on repeat purchases.

---

## 🗄 Relational Schema & Queries

The analysis joins 8 relational entities:
* `orders`, `order_items`, `order_payments`, `order_reviews`
* `customers`, `sellers`, `products`, `geolocation`

Key SQL patterns utilized:
* Multi-table window functions (`ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`)
* Common Table Expressions (CTEs) for multi-tiered aggregations
* Date/time interval math for logistics lead-time calculations

---

## 🚀 Running the Analysis

Open the Google Colab notebook or run locally:
```bash
# Clone repository
git clone https://github.com/quvonchbek212/olist-ecommerce-analytics.git
cd olist-ecommerce-analytics

# Run analysis script
python analyze.py
```

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).
