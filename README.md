# Machine-Learning-Approach-to-Telecom-Churn-Prediction

# 📊 Telecom Customer Churn Analysis and Prediction (Python)

## Overview

This project analyzes customer churn behavior using telecom customer
data and builds predictive machine learning models to identify high-risk
customers. It covers the full data science workflow, from exploratory
analysis and statistical testing to model evaluation and business
interpretation.

The focus is on producing actionable insights that businesses can use to
improve customer retention.

------------------------------------------------------------------------

## Key Skills Demonstrated

-   Python (pandas, numpy, scipy, scikit-learn, statsmodels)
-   Exploratory Data Analysis (EDA)
-   Statistical Testing (t-tests, chi-square tests)
-   Feature Engineering and Preprocessing
-   Logistic Regression and Random Forest Models
-   Model Evaluation (Accuracy, Precision, Recall, F1-score)
-   Business-Oriented Data Interpretation

------------------------------------------------------------------------

## Dataset

Two datasets were used:

-   Monthly Contracts: 800 customers
-   Yearly Contracts: 600 customers

Features include: - Tenure - Monthly Charges - Total Charges - Contract
Type - Internet Services - Payment Method - Churn Label

After merging, the final dataset contains 1,400 customers with no
missing values.

------------------------------------------------------------------------

## Exploratory Data Analysis

Key insights from EDA:

-   Month-to-month customers show significantly higher churn
-   Most churn occurs in the first year of service
-   Tenure and total charges are highly correlated
-   Target variable is imbalanced

These findings guided model design and evaluation.

------------------------------------------------------------------------

## Statistical Analysis

-   Two-sample t-tests showed significant differences in tenure and
    total charges
-   Chi-square tests confirmed contract type influences churn

This validated contract duration as a major churn driver.

------------------------------------------------------------------------

## Feature Engineering

-   Created tenure categories (SHORT, MEDIUM, LONG)
-   One-hot encoded categorical variables
-   Standardized numerical features
-   Prevented data leakage in modeling

------------------------------------------------------------------------

## Machine Learning Models

### Logistic Regression

Used for interpretability. Key findings: - High churn risk:
month-to-month contracts, electronic checks - Low churn risk: long
tenure, tech support

Backward elimination improved performance and simplicity.

### Random Forest

Used for non-linear modeling. Top features: - Tenure - Total Charges -
Monthly Charges

Tested multiple tree counts for stability.

------------------------------------------------------------------------

## Model Evaluation

Metrics used: - Accuracy - Precision - Recall - F1-score

Key Result: Although accuracy reached \~68%, recall for churn remained
low (\~47%), highlighting business risk.

------------------------------------------------------------------------

## Business Insights

-   Early-stage customers are highest risk
-   Long-term contracts improve retention
-   Add-on services reduce churn
-   Models should prioritize recall

------------------------------------------------------------------------


Add-on services reduce churn
Models should prioritize recall
