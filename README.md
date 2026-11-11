# Telco Customer Churn — Classification

Predict which telecom customers will leave the company.

- Dataset: Telco Customer Churn (Kaggle, 7043 customers)
- Steps: cleaning, EDA, encoding, train/test split, scaling, imbalance check
- Model: Logistic Regression
- Metrics: confusion matrix, precision, recall, F1, ROC AUC

## Results
| Threshold | Recall (churn) | Precision (churn) | AUC |
|---|---|---|---|
| 0.5 | 0.56 | 0.66 | 0.84 |
| 0.3 | 0.76 | 0.52 | 0.84 |

Kaggle notebook: https://www.kaggle.com/code/amrbakr95/telco-customer-churn-logistic-regression
