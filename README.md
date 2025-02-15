# Loan Repayment and Default Prediction

Overview

This project analyzes bank loan repayment data and builds a predictive model using logistic regression to determine the likelihood of a borrower defaulting on a loan. The analysis follows the PACE framework: Plan, Analyze, Construct, and Execute.

![image alt](https://github.com/Maximus-247/Loan-Repayment-and-Default/blob/main/Screenshot%202025-01-25%20170714.png?raw=true)
## Problem Statement

Banks rely on loans as a major source of revenue, but they also carry the risk of borrower default. To mitigate this risk, the bank has gathered historical loan data and aims to build a robust machine learning model that predicts loan default probability and identifies key factors affecting repayment.

## Objectives

1. Understand the loan dataset in the context of banking operations.

2. Identify key features that influence loan repayment and default.

3. Build a predictive model using logistic regression to classify borrowers as likely to repay or default.

4. Evaluate the model’s accuracy and interpret its predictions to provide actionable insights for the bank’s finance department.

## General Analysis of Results

1. The dataset includes borrower characteristics such as age, income, employment length, home ownership status, and credit history.

2. Logistic regression was applied, and key predictors of loan repayment/default were identified.

3. Feature importance analysis showed that income, employment length, and home ownership were among the strongest predictors of loan repayment ability.

4. The model achieved a reasonable accuracy, with an ROC-AUC score indicating good performance in distinguishing defaulters from non-defaulters.

5. The confusion matrix revealed some misclassifications, indicating room for improvement through feature engineering or alternative modeling approaches.

## Conclusion

The logistic regression model provides a data-driven approach to assessing loan default risk. While it performs well, further refinements such as incorporating additional borrower data or exploring alternative models (e.g., decision trees, ensemble methods) could enhance predictive accuracy.

## Recommendations

1. Implement the model in the bank’s decision-making pipeline for assessing loan applications.

2. Monitor model performance over time and update it with new data to improve predictions.

3. Explore additional features such as credit scores, past loan performance, and transaction history for enhanced predictive power.

4. Consider alternative models like random forests or gradient boosting for comparison.
