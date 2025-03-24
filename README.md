# Telecom Churn Analysis

## Overview
This project analyzes customer churn for a telecom company using the Telco Customer Churn dataset. The goal is to identify factors driving churn and provide actionable insights for the marketing department to improve customer retention.

## Goals
- Clean and prepare the dataset for analysis.
- Explore factors influencing churn through summary statistics and visualizations.
- Communicate findings and recommendations to the marketing department.

## Structure
- `telecomchurn.ipynb`: Jupyter Notebook containing the full analysis pipeline (data wrangling, EDA, and findings).
- `data/WA_Fn-UseC_-Telco-Customer-Churn.csv`: Dataset used for analysis.

## Key Findings
- **Churn Rate**: 26.5% of customers churned.
- **Tenure**: Churners have shorter tenures (median ~10 months) compared to non-churners (median ~40 months). New customers are at higher risk of leaving.
- **Contract Type**: Month-to-month customers are more likely to churn compared to those on one-year or two-year contracts.
- **Monthly Charges**: Churners have higher monthly charges (average ~$74) compared to non-churners (average ~$61).
- **Internet Service**: Fiber optic customers have a higher churn rate than DSL or no-internet customers.

## Recommendations
- Focus on retaining new customers with better onboarding or incentives in their first year.
- Encourage longer-term contracts with discounts or added benefits.
- Review pricing strategies to offer competitive rates or bundles.
- Investigate and address issues with fiber optic service (e.g., reliability, cost).

## How to Run
1. Clone the repository:
