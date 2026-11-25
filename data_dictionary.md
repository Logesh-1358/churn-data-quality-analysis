# Data Dictionary (`churn_cleaned.csv`)

| Column | Type | Description |
|---|---|---|
| customer_id | text | Unique ID, format CUST-####|
| gender | category | Female / Male |
| age | integer | Customer age in years (23-60) |
| tenure_months | integer | Months as a customer |
| subscription_type | category | Basic / Pro / Enterprise |
| monthly_charges | float | Monthly fee (49.99 / 79.99 / 149.99 by plan) |
| total_charges | float | Equals monthly_charges x tenure_months |
| contract_type | category | Month-to-Month / One Year / Two Year |
| support_tickets | integer | Number of support tickets raised |
| payment_method | category | Credit Card / Debit Card / UPI / Bank Transfer |
| churn | category | Yes = customer left, No = retained |
| churn_flag | integer | Added during cleaning: 1 = Yes, 0 = No |
