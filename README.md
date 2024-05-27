# Ethereum Fraud Detection
## Overview
This project focuses on detecting fraudulent transactions within the Ethereum blockchain. By leveraging feature engineering techniques and training various machine learning models, we achieved impressive results.

## Key Steps
#### Data Preprocessing:
Initially, we faced challenges due to the large number of columns in our dataset. To address this, we applied feature engineering techniques to reduce the dimensionality.
We handled issues related to an imbalanced dataset, missing values, and normalization.
#### Feature Engineering:
Reduced the number of columns using domain knowledge and statistical analysis.
Addressed class imbalance by oversampling or undersampling the data.
Imputed missing values using appropriate methods.
Ensured consistent scaling of features.
#### Model Training:
We trained several models, but the XGBoost model stood out.
Achieved an impressive F-score of 0.99 on the training data.
Generalized well to the test data, achieving an F1-score of 0.93.
