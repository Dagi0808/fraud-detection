# 💳 Fraud Detection Project (E-commerce + Credit Card)

## 📌 Overview
This project builds a fraud detection system for e-commerce and bank transactions using machine learning. The goal is to detect fraudulent activity while minimizing false positives and false negatives.

---

## 📊 Datasets
- **Fraud_Data.csv** → E-commerce transactions
- **creditcard.csv** → Bank credit card transactions (PCA features)
- **IpAddress_to_Country.csv** → IP geolocation mapping

---

## ⚙️ Work Completed (Task 1)

### 1. Data Cleaning
- Handled missing values
- Removed duplicates
- Converted timestamps to datetime format

### 2. Exploratory Data Analysis (EDA)
- Checked class imbalance
- Analyzed transaction behavior
- Explored fraud patterns by features

### 3. Feature Engineering
Created behavioral features:
- time_since_signup
- hour_of_day
- day_of_week
- user_transaction_count
- device_transaction_count
- time_since_prev_txn
- rapid_transaction flag

### 4. Preprocessing
- One-hot encoding for categorical variables
- Feature scaling using StandardScaler
- Removed ID columns (user_id, device_id)

### 5. Class Imbalance Handling
- Applied SMOTE on training data only

---

## 📌 Current Status
✔ Task 1 completed  
✔ Dataset ready for modeling  

---

## 🚀 Next Steps
- Train baseline model (Logistic Regression)
- Train ensemble models (Random Forest / XGBoost)
- Evaluate using F1-score and AUC-PR
- Model explainability using SHAP

---

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

---

## 👨‍💻 Author
Fraud Detection ML Project — Adey Innovations Challenge