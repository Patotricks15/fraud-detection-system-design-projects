# Fraud Detection System Design Projects

A portfolio of independent card-fraud detection systems, from a transparent
logistic baseline to a cost-aware decision policy and drift monitoring. Each
project is its own GitHub repository with a time-ordered split, precision-recall
metrics (fraud is rare, so accuracy is not reported as a primary metric), and a
README that records the decision and one limitation.

## Projects

| # | Name | Dataset | Main method | Repository |
|---|------|---------|-------------|-------------|
| 1 | Logistic Baseline | Credit Card Fraud Detection (Kaggle) | Transparent logistic regression baseline | [fraud-logistic-baseline](https://github.com/Patotricks15/fraud-logistic-baseline) |
| 2 | Cost-Sensitive XGBoost | Credit Card Fraud Detection (Kaggle) | Cost-sensitive XGBoost with time-ordered validation | [fraud-cost-sensitive-xgboost](https://github.com/Patotricks15/fraud-cost-sensitive-xgboost) |
| 3 | Unsupervised Anomaly Detection | Credit Card Fraud Detection (Kaggle) | Isolation Forest and LOF on a time-ordered split | [fraud-unsupervised-anomaly](https://github.com/Patotricks15/fraud-unsupervised-anomaly) |
| 4 | Threshold Cost Policy | Credit Card Fraud Detection (Kaggle) | Cost-based threshold chosen on validation, reported once on test | [fraud-threshold-cost-policy](https://github.com/Patotricks15/fraud-threshold-cost-policy) |
| 5 | Drift Monitoring | Credit Card Fraud Detection (Kaggle) | Drift monitoring with alert rules and a retraining trigger | [fraud-drift-monitoring](https://github.com/Patotricks15/fraud-drift-monitoring) |

Velocity and graph features (FD04) is planned but blocked until a real dataset
with card and device identifiers is verified, so it is not listed here.

## Scope

This is part of a larger fraud detection portfolio plan. Projects are added here
as they are completed; each repository listed above is self-contained and can be
cloned, tested, and run independently.
