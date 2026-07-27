# Customer Churn Logistic Regression Analysis

## Overview
This project investigates which customer and service-related factors are associated with customer churn. A multiple logistic regression model was developed in Python to identify the variables that significantly influence the likelihood of a customer leaving the company.

## Business Question
Which customer and service-related factors significantly influence customer churn?

## Dataset
- Customer Churn Dataset
- Response Variable:
  - Churn
- Predictor Variables:
  - Population
  - Area
  - Children
  - Age
  - Marital
  - Outage_sec_perweek
  - Yearly_equip_failure
  - Techie
  - Multiple
  - Tenure
  - MonthlyCharge
  - Bandwidth_GB_Year
  - Income
  - Contract

## Tools
- Python
- Pandas
- NumPy
- Statsmodels
- Matplotlib
- Seaborn
- Jupyter Notebook

## Statistical Method
- Multiple Logistic Regression
- Maximum Likelihood Estimation (MLE)

## Results
The logistic regression model identified several customer and service characteristics that significantly influenced the likelihood of customer churn. Variables related to contract type, tenure, monthly charges, bandwidth usage, and customer service characteristics were among the strongest predictors.

## Conclusion
The analysis demonstrates that customer demographics, service selections, and usage patterns are associated with the probability of customer churn. These findings can help organizations identify at-risk customers and support data-driven customer retention strategies. While the model identifies statistically significant relationships, it does not establish causation.

## Recommendations

The company should consider using these findings to:

- Identify customers with a high probability of churn.
- Develop targeted customer retention strategies.
- Improve contract and pricing decisions.
- Enhance customer service for high-risk customer segments.
- Support proactive business decision-making using predictive analytics.

## Project Files

- [View the Jupyter Notebook](customer_churn_logistic_regression.ipynb)
- [View the Full Written Report](Customer_Churn_Logistic_Regression_Report.pdf)
