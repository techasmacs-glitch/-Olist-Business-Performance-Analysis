# 📊 Olist E-Commerce Business Analysis

---

# 📌 Project Overview

Olist is one of Brazil's largest e-commerce marketplaces, connecting thousands of sellers with customers across Brazil.

This project transforms raw transactional data into meaningful business insights through data preparation, data modeling, and interactive reporting. The analysis focuses on evaluating business performance, identifying growth opportunities, understanding customer behavior, and assessing logistics efficiency to support data-driven decision-making.

---

# 🎯 Business Objectives

This project answers the following business questions:

- How is the business performing overall?
- Which products and categories generate the highest revenue?
- Who are the most valuable customers?
- How does customer behavior vary across different regions?
- How efficient is the delivery process?
- Does delivery performance impact customer satisfaction?
- What business improvements can be recommended based on the analysis?

---

# 📂 Dataset

**Source:** Olist Brazilian E-Commerce Public Dataset (Kaggle)

### Dataset Summary

- **99K+ Orders**
- **96K+ Unique Customers**
- **13.59M Total Revenue**
- **9 Related Tables**

The dataset contains transactional, customer, product, payment, seller, review, and logistics data covering the complete e-commerce order lifecycle.

---

# 🔄 Data Preparation

Data preparation was performed using **Power Query** to ensure data quality before analysis.

The preprocessing process included:

- Validating data types.
- Verifying data consistency.
- Removing unnecessary values.
- Translating product category names into English.
- Building table relationships.
- Optimizing the data model for reporting.

---

# 🏗️ Data Modeling

A **Star Schema** was implemented to simplify relationships, improve performance, and support efficient analytical reporting.

### Fact Table

- Order Items

### Dimension Tables

- Orders
- Customers
- Products
- Sellers

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard Development & Visualization |
| **Power Query** | Data Cleaning & Transformation |
| **DAX** | KPI & Business Calculations |
| **Data Modeling** | Star Schema Design |

---

# 📸 Dashboard Preview

## 📈 Executive Summary

![Executive Summary](Screenshots/Executive_Summary.png)

## 📦 Product Analysis

![Product Analysis](Screenshots/Product_Analysis.png)

## 👥 Customer Analysis

![Customer Analysis](Dashboard Screenshots
/Customer_Analysis.png)

## 🚚 Logistics & Delivery

![Logistics & Delivery](Screenshots/Logistics_Delivery.png)

## 💡 Business Recommendations

![Business Recommendations](Screenshots/Business_Recommendations.png)

---

# 🔍 Key Insights

- **Delivery times ranged from 8.7 days in São Paulo (SP) to 29 days in Roraima (RR), revealing a significant regional logistics gap that may negatively impact customer satisfaction.**

- **The Bed, Bath & Table category recorded the highest order volume (9,417) but the lowest average customer rating (3.97), indicating an opportunity to improve product quality and customer experience.**

- **Customers placed an average of only 1.03 orders each, suggesting limited customer retention and an opportunity to increase repeat purchases through loyalty initiatives.**

- **Revenue declined from 1.69M in September 2017 to only 145 in September 2018, revealing an anomaly that should be investigated to identify its root cause.**

- **Health & Beauty generated the highest revenue (1.26M) while maintaining a strong average rating (4.18), making it the strongest-performing product category.**

- **Orders with longer delivery times generally received lower customer ratings, indicating that improving logistics performance could enhance customer satisfaction.**

---

# 💡 Business Recommendations

- Improve logistics efficiency in northern states to reduce regional delivery disparities.
- Improve product quality within the **Bed, Bath & Table** category.
- Develop customer loyalty programs to encourage repeat purchases.
- Investigate the September 2018 revenue anomaly.
- Increase investment in the **Health & Beauty** category.
- Continuously monitor delivery performance to maintain customer satisfaction.

---

# 💼 Business Value

This project demonstrates an end-to-end Business Intelligence workflow, from data preparation and data modeling to business analysis and interactive reporting.

The dashboard enables stakeholders to:

- Monitor overall business performance.
- Identify high-performing products and categories.
- Analyze customer purchasing behavior.
- Evaluate logistics and delivery efficiency.
- Discover operational improvement opportunities.
- Support strategic decision-making through data.

---

# 📁 Repository Structure

```text
Olist-Ecommerce-Business-Analysis/
│
├── Dashboard/
│   └── Olist Dashboard.pbix
│
├── Dataset/
│
├── Screenshots/
│   ├── Executive_Summary.png
│   ├── Product_Analysis.png
│   ├── Customer_Analysis.png
│   ├── Logistics_Delivery.png
│   └── Business_Recommendations.png
│
└── README.md
```
