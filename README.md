
# 💳 Credit Card Fraud Detection with Machine Learning

📖 **Overview**

This project implements a machine learning–based fraud detection system to classify credit card transactions as **fraudulent** or **legitimate**.
It uses the **Kaggle Credit Card Fraud Dataset**, applies preprocessing and feature scaling, and trains models such as **Random Forest**, **Logistic Regression**, and **XGBoost** to detect anomalies in real or simulated transactions.

⚡ **Features**

* Preprocesses raw transaction data (scaling, handling class imbalance).
* Supports **real-time fraud detection** by passing new transactions for prediction.
* Uses **RandomForestClassifier**.
* Evaluation metrics: **accuracy, precision, recall, F1-score, ROC-AUC**.
* Provides ability to save trained models for later use.


⚙️ **Setup Instructions**

1. **Clone Repository & Create Virtual Environment**

```bash
git clone <your_repo_url>
cd fraud_detection
python3 -m venv venv
source venv/bin/activate
```

2. **Install Dependencies**

```bash
pip install -r requirements.txt
```

Dependencies include: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`, `imbalanced-learn`

3. **Download Dataset**

Get the dataset from Kaggle:
👉 [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)

Place it inside `data/creditcard.csv`

📊 **Model Evaluation**

Example output metrics:

* Accuracy: 99.7%
* Precision: 92%
* Recall: 85%
* F1-score: 88%
* ROC-AUC: 0.99

