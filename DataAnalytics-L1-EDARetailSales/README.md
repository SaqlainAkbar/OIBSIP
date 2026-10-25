# EDA on Retail Sales Data

**Intern:** Saqlain Akbar | **Track:** Data Analytics | **Company:** Oasis Infobyte
**Task:** Level 1, Task 1 — Exploratory Data Analysis on Retail Sales

## Objective
Explore 4 years of retail transactions (2022–2025) to find sales trends, customer behaviour and business insights.

## Dataset
Sales_transactions_2022_2025.csv (18,045 rows × 36 columns; 17,991 rows after cleaning). Source: Kaggle (add your dataset link here).

## What I did
- Data inspection: shape, dtypes, null check
- Cleaning: removed 45 duplicates, standardised text, fixed dates, removed impossible values, handled missing data
- Descriptive statistics (mean, median, mode, std)
- Monthly and quarterly sales trends
- Customer analysis: age groups and gender
- Product analysis: top 10 products, revenue by category
- Correlation heatmap and profit margin analysis

## Key findings
- Q4 (Oct–Dec) is the strongest quarter every year; Q4 2025 sales were ~45% above Q3 2025.
- Customers aged 36–45 generate ~36% of revenue.
- Electronics is ~59% of revenue but has one of the lowest profit margins (~19%); Appliances (~22%) and Furniture (~21%) are more profitable.
- Higher discounts reduce profit (correlation −0.19).

## Recommendations
1. Prepare inventory and promotions before Q4.
2. Focus marketing on customers aged 26–55.
3. Grow Furniture and Appliances to reduce dependence on Electronics.

## Tools
Python, pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook (Google Colab)

## Files
- `retail_sales_eda.ipynb` — full analysis notebook
- `Sales_transactions_2022_2025.csv` — dataset
- `*.png` — chart screenshots
