# Quantium Retail Strategy & Analytics
### Data Analytics Virtual Experience — Forage

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## Project Overview
Customer analytics project completed as part of the **Quantium Data Analytics 
Virtual Experience Programme** on Forage.

Analysis of **246,740 chip transactions** across **71,287 customers** to identify 
key purchasing behaviours and provide strategic recommendations to the 
Category Manager.

---

## Key Findings

- **Mainstream Young Singles/Couples** are the highest value segment — 
  spending $147,582 vs $39,052 for Premium in the same lifestage
- **Mainstream customers** generate the most revenue at **$700,865** — 
  outperforming Premium customers by 48%
- **Doritos and Smiths** dominate sales across ALL customer tiers
- Purchase **frequency** — not price per visit — is the primary driver 
  of revenue differences between segments

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python 3.12 | Core programming language |
| Pandas | Data cleaning and analysis |
| Matplotlib | Data visualisation |
| Prophet | Time series forecasting |
| Jupyter Notebook | Development environment |

---

## Project Structure
```
quantium-retail-analytics/
│
├── data/
│   ├── QVI_transaction_data.xlsx      ← 264,836 transaction records
│   └── QVI_purchase_behaviour.csv     ← 72,637 customer profiles
│
├── notebooks/
│   └── task1_customer_analytics.ipynb ← Full analysis notebook
│
├── requirements.txt                   ← Python dependencies
└── README.md
```

---

## 📊 Analysis Steps

1. **Data Loading & Exploration** — initial summaries and data checks
2. **Data Cleaning** — fixed dates, removed non-chip products, 
   cleaned product names
3. **Feature Engineering** — extracted pack size and brand name
4. **Outlier Detection** — verified data quality across all columns
5. **Customer Segmentation** — merged and analysed 7 lifestages 
   across 3 spending tiers
6. **Insights & Recommendations** — commercial strategy for the 
   Category Manager

---

## How to Run
```bash
# Clone the repo
git clone https://github.com/Abdulkareem007/quantium-retail-analytics.git

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook notebooks/task1_customer_analytics.ipynb
```

---

## Certificate
Completed via **Forage — Quantium Data Analytics Virtual Experience Programme**

---

*Part of my data analytics portfolio — transitioning into data analytics* 
career with a focus on finance and technology sectors.*# quantium-retail-analytics
Customer analytics and chip purchasing behaviour analysis using Python and Pandas
