# Online Retail Store – Exploratory Data Analysis

This notebook explores 541,909 rows from an online retail store between 2010-12-01 and 2011-12-09. The company wants to understand its customers, products, cancellations, sales performance and international markets.

## Dataset
- Source: https://www.kaggle.com/datasets/mahendra77/retail-dataset
- Period: 1 December 2010 – 9 December 2011
- Size: 541,909 rows, 8 columns (522,568 rows after cleaning)

## Files
- `Retail Store project.ipynb` – the full analysis notebook
- `Online Retail 2.xlsx` – the raw dataset
- `Online Retail Store Exploratory Data Analysis Report.pdf` – the EDA report for non-technical readers

## How to run
1. Install the libraries: `pip install pandas numpy matplotlib seaborn missingno scipy openpyxl jupyter`
2. Put `Online Retail 2.xlsx` in the same folder as the notebook
3. Open the notebook and run all cells (Kernel → Restart Kernel and Run All Cells)

## What the notebook covers
- Data loading and audit
- Preparing the sales data
- Univariate analysis
- Bivariate analysis
- Missing data and outliers
- Cleaning decisions
- Feature engineering
- Business insights

## Key findings
- 7.87% of order lines bring 49% of revenue
- No sales on Saturday
- Orders come during office hours, so customers are mostly businesses
- November is the peak (about £1.45M), and the rise starts in September
- The Netherlands is #2 by revenue with few order lines (big customers)

## Author
Khodor El-Rifai – November 2026v