# Cardiovascular Disease Survival Prediction

## Introduction
Cardiovascular disease is a leading cause of death globally, with millions of people affected each year. In this project, we analyzed medical records of 300 patients to predict their survival status after suffering from heart failure. Using data from the heart_failure.csv dataset sourced from GitHub, we developed a logistic regression model to evaluate the probability of survival based on key medical factors.

## Key Objectives:
- Analyze patient data to identify significant predictors of survival.
- Build a binomial logistic regression model to predict the likelihood of survival after a cardiovascular event.
- Examine critical medical features such as serum creatinine, serum sodium, ejection fraction, and age.

## Approach:
- Phase 1: Explored relationships between variables such as smoking, diabetes, hypertension, and patient survival. Initial findings highlighted age, ejection fraction, serum creatinine, and sodium as key indicators of survival risk.
- Phase 2: Refined the model using stepwise selection to identify the most significant predictors. Conducted goodness-of-fit tests, hypothesis testing, and residual analysis to evaluate the model's performance.

## Findings:
- The most important predictors of survival were serum creatinine, serum sodium, ejection fraction percentage, and age.
- Variables like smoking, diabetes, and anaemia did not significantly impact the survival outcome in the logistic regression model.
- The model effectively predicts survival status, providing a powerful tool for assessing cardiovascular risk using electronic medical records.

## Conclusion:
This project demonstrates the potential of using logistic regression models to predict patient survival from cardiovascular disease. The methodology can be extended to other health conditions like cancer or tumors, making it a valuable tool in medical risk assessment.
