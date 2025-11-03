 # Bank Loan Default Risk Analysis (EDA)
 
## Overview

This project performs Exploratory Data Analysis (EDA) on bank loan application data to uncover factors influencing loan repayment difficulties.
The goal is to identify demographic, financial, and behavioral patterns that drive default risk, providing actionable insights for smarter credit assessment and risk mitigation.

## Objectives

- Identify key variables associated with loan default risk.

- Analyze client demographics, financial ratios, and historical behavior.

- Examine imbalances in repayment outcomes and their business implications.

- Provide data-driven recommendations for policy refinement and future modeling.

## Key Steps

Data Cleaning: Removed redundant, low-value, and highly null columns.

Outlier Analysis: Detected extreme values using the IQR method (no removals).

Univariate & Bivariate Analysis: Explored demographic, employment, and financial patterns across repayment outcomes.

Ratio Analysis: Compared credit, income, and annuity ratios to assess repayment burden.

Historical Loan Behavior: Linked past approvals/refusals with current default tendencies.

## Insights

- Younger, early-career clients show higher default risk due to income instability.

- High annuity-to-income ratios indicate greater repayment stress.

- Clients with frequent reapplications or low-value past loans default more often.

- Past refusals and cancellations strongly correlate with current repayment difficulties.

## Next Steps

- Extend to predictive modeling (e.g., logistic regression, random forest).

- Enrich dataset with credit bureau and behavioral data.

- Build interactive dashboards for ongoing portfolio risk monitoring.

## Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)

- Jupyter Notebook for analysis and visualization (Hosted on Google Colab)

- Dataset: Home Credit Default Risk (Kaggle)

## Author
Mohd Azri — Data Analyst
🔗 [LinkedIn](https://linkedin.com/in/mohdazri4221)
