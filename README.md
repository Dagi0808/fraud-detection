📌 Fraud Detection Project — E-commerce & Credit Card Transactions
📖 Overview

This project builds a machine learning system to detect fraudulent transactions in both e-commerce and credit card datasets. The goal is to reduce financial loss while minimizing false positives and maintaining customer trust.

📂 Datasets
Fraud_Data.csv → E-commerce transactions (user behavior, device, IP, time)
creditcard.csv → Bank transactions (PCA anonymized features)
IpAddress_to_Country.csv → Geolocation mapping
⚙️ Project Pipeline
1. Data Understanding & Cleaning
Missing value analysis
Duplicate removal
Data type conversion (timestamps)
2. Exploratory Data Analysis (EDA)
Class imbalance analysis
Fraud pattern exploration
Feature distribution analysis
Fraud by country analysis (IP mapping)
3. Feature Engineering

Created behavioral fraud signals:

Transaction velocity features:
time_since_prev_txn
rapid_transaction flag
User behavior features:
user_transaction_count
device_transaction_count
Time-based features:
hour_of_day
day_of_week
time_since_signup
4. Data Preprocessing
One-hot encoding (categorical variables)
StandardScaler normalization
Removal of ID columns (user_id, device_id)
5. Class Imbalance Handling
SMOTE applied ONLY on training data
Ensures no data leakage
📊 Current Status

✔ Task 1 completed
✔ Feature engineering completed
✔ Dataset ready for modeling

🚀 Next Steps (Task 2)
Logistic Regression (baseline)
Random Forest / XGBoost
Evaluation metrics:
F1-score
Precision-Recall AUC
Confusion matrix
Model explainability using SHAP
🧠 Key Learning
Fraud detection requires feature engineering more than complex models
Class imbalance significantly impacts model evaluation
Data leakage prevention is critical in SMOTE workflows
🛠 Tech Stack

Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn, Matplotlib, Seaborn

👨‍💻 Author

Fraud Detection Project — Adey Innovations ML Challenge