# Predictive Insights into Banking Customer Churn

**NST DVA Capstone 2 – Project Repository**  
Newton School of Technology | Data Visualization & Analytics  

---

## Project Overview

This project analyzes customer data from a banking dataset to identify patterns behind customer churn. Using Python for data analysis and Tableau for visualization, the goal is to generate actionable insights that help banks retain customers and reduce churn.

---

## Business Problem

Customer churn leads to revenue loss in banks. Identifying customers likely to leave and understanding the reasons behind churn is crucial for improving retention strategies.

---

## Core Business Question

Which customers are most likely to churn, and what factors influence their decision?

---

## Objective

- Identify high-risk customers  
- Analyze behavioral and financial patterns  
- Support data-driven retention strategies  

---

## Dataset

- **Source:** Kaggle – Bank Customer Churn Data  
- **Rows:** 28,382  
- **Columns:** 20+  
- **Format:** CSV  

---

## Key Features

| Column | Description |
|--------|------------|
| customer_id | Unique ID |
| age | Customer age |
| gender | Gender |
| dependents | Number of dependents |
| occupation | Job type |
| city | Location |
| vintage | Relationship duration |
| current_balance | Account balance |
| current_month_credit | Monthly credit |
| current_month_debit | Monthly debit |
| churn | Target variable |

---

## KPIs

| KPI | Formula |
|-----|--------|
| Churn Rate | (Churned / Total Customers) × 100 |
| Avg Balance | Avg(current_balance) |
| Customer Lifetime | Avg(vintage) |
| Activity Score | Credit + Debit |

---

## Dashboard

- Built using Tableau Public  
- Includes filters for age, city, gender, and balance  
- Shows churn trends and customer segmentation  

---

## Key Insights

- Low balance customers are more likely to churn  
- Customers with low activity show high churn risk  
- Short tenure customers churn more  
- Drop in balance indicates churn risk  
- High-value customers are more stable  

---

## Recommendations

- Offer incentives to low-balance customers  
- Target inactive users with engagement campaigns  
- Improve onboarding for new customers  
- Monitor sudden balance drops  
- Create loyalty programs for mid-tier customers  

---

## Project Structure

```
Predictive-Insights-into-Banking-Customer-Churn/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_extraction.ipynb
│   ├── 02_cleaning.ipynb
│   ├── 03_eda.ipynb
│   ├── 04_statistical_analysis.ipynb
│   └── 05_final_load_prep.ipynb
│
├── tableau/
├── reports/
├── docs/
└── README.md
```

---

## Tech Stack

- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Tableau Public
- Jupyter Notebook
- GitHub

---

## Academic Integrity

All work in this repository is original and completed as part of the NST DVA Capstone project.
