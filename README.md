# Fraud Detection in Financial Transactions
Credit card fraud detection with Logistic Regression

# Overview
This project detects fraudulent credit card transactions using machine learning. 
Due to heavy class imbalance, recall is prioritized over accuracy.

# Dataset
- credit_card_fraud_10k.csv
- Target column: is_fraud (0 = Normal, 1 = Fraud)

# Steps
- Data loading and inspection
- Handling class imbalance
- One-hot encoding of categorical features
- Feature scaling (StandardScaler)
- Logistic Regression (baseline)
- Logistic Regression with class_weight='balanced'

# Results
- Baseline: High accuracy, lower recall
- Balanced model: Accuracy ~96%, Recall = 100%

# Key Insight
In fraud detection, recall is more important than accuracy because missing fraud is costly.

# Tools
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
