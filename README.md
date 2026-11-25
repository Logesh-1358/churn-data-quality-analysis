# Customer Churn: Data Quality & EDA

Audit, cleaning, and exploratory analysis of a synthetic customer churn dataset.

## Files
- `churn_analysis.ipynb`: profiling, validation, cleaning, summary stats, charts, and the data-quality summary (last section)
- `customer_churn_sample.csv`: original dataset
- `churn_cleaned.csv`: cleaned dataset
- `data_dictionary.md`: column definitions

## Headline findings
- 15 rows, no missing values, no duplicates, no outliers; nothing dropped or imputed
- Churn rate 46.7%; all Month-to-Month customers churned, none on One Year or Two Year contracts
- Churners have shorter tenure (7 vs 29 months) and more support tickets (4.3 vs 1.0)
- Small synthetic sample, so patterns are illustrative
