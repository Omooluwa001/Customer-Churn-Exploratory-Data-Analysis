# 📉 Customer Churn — Exploratory Data Analysis

A business-focused EDA project analysing client and pricing data to understand the patterns and features associated with customer churn in an energy services company.

---

## 📌 Project Overview

This project was completed as part of a data analyst task (BCG Forage Virtual Experience). It explores two datasets — customer data and energy pricing data — to identify what distinguishes churned customers from retained ones. The analysis sets the foundation for future predictive modelling.

---

## 🎯 Objectives

- Understand the overall churn rate and its distribution
- Explore customer demographics and consumption patterns
- Identify which features differ between churned and retained customers
- Visualise energy consumption distributions by churn status
- Surface correlations in client-level data

---

## 🗂️ Project Structure

```
customer-churn-eda/
├── customer_churn_eda.ipynb    ← Main documented notebook
├── forage/
│   ├── client_data (1).csv    ← Customer data with churn labels
│   └── price_data (1).csv     ← Energy pricing history
└── README.md
```

---

## 🛠️ Tools & Libraries

| Library | Purpose |
|---|---|
| `pandas` | Data loading and manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Plotting and stacked bar charts |
| `seaborn` | Statistical visualisation |

---

## 📊 Key Analyses

- Overall churn rate (stacked bar chart with percentage labels)
- Distribution of all numeric features (histogram + KDE)
- Top categories for all categorical features (bar charts)
- Correlation heatmap across all numeric variables
- Unique value count per column (data quality check)
- Missing value audit for both datasets
- 12-month electricity consumption comparison: churned vs retained

---

## 🔧 Custom Functions

| Function | Description |
|---|---|
| `plot_stacked_bars()` | Renders an annotated stacked bar chart for churn breakdown |
| `annotate_stacked_bars()` | Adds percentage value labels inside bar segments |
| `plot_distribution()` | Plots a stacked histogram comparing churn vs retention for any numeric column |

---

## ▶️ How to Run

1. Clone or download this repository
2. Place both CSV files inside a `forage/` subfolder
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Open the notebook:
   ```bash
   jupyter notebook customer_churn_eda.ipynb
   ```

---

## 📁 Data Source

Datasets provided as part of the **BCG Data Science Virtual Experience** on Forage.  
- `client_data.csv` — Customer account details and churn labels  
- `price_data.csv` — Historical energy pricing per customer  

> Source: https://www.theforage.com/

---

## 👤 Author

ODETUNDE OLUMIDE | DATA ANALYST (https://www.linkedin.com/in/olumide-temitope-odetunde-209924201/)
