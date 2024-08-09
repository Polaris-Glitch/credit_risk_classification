## Overview

This analysis uses a logistic regression model to predict whether a loan is a high risk or not. By comparing the Y-variable (loan status) to the X-variable (loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, and total_debt) and creating both a confusion matrix and Classification report, we are able to see that this particular machine learning model works ver well in identifying good loans.

## Results

This model has an overall accuracy score of 99%
- for class 0, which is the majority, the model has a precission score of 100% and recall of 99%
- for class 1, which is the target class, the model has a a precission score of 85% and a recall of 91%

## Summary
Over all, the model works very well to classify good loans (class 0), but needs improvement to correctly flag high risk loans (class 1). Because this analysis is needed to identify high risk loans, this particular machine learning model is not recomended.

