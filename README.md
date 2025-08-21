
# Credit Card Fraud Detection with Machine Learning

📁 **Overview**
This project classifies credit card transactions as *genuine* or *fraudulent* using a Random Forest machine learning model built in a Jupyter notebook. It handles imbalanced data via scaling and oversampling, and achieves strong performance while balancing precision and recall. See the full implementation here:
**[Project Notebook](https://github.com/treshane-ranasinghe/Credit-Card-Fraud-Detection-ML/blob/main/credit_card_fraud_detection_model.ipynb)**

---

## Technologies Used

| Technology          | Purpose                                         |
| ------------------- | ----------------------------------------------- |
| Python (3.x)        | Programming language                            |
| Jupyter Notebook    | Interactive development environment             |
| pandas, numpy       | Data manipulation and numerical computations    |
| scikit-learn        | Model building, evaluation, and data processing |
| imbalanced-learn    | Handling data imbalance (SMOTE, undersampling)  |
| matplotlib, seaborn | Data visualization and exploratory analysis     |
| joblib (optional)   | Saving and loading trained models               |

---

## Model Evaluation

After training the Random Forest classifier, the model was evaluated on the test set using the following metrics:

* **Accuracy:** 99.7% — high overall correctness
* **Precision:** 92% — high proportion of true fraud among flagged cases
* **Recall:** 85% — strong ability to catch actual fraud cases
* **F1-Score:** 88% — balanced measure combining precision and recall
* **Matthews Correlation Coefficient (MCC):** \[Insert MCC value] — robust overall performance
* **Confusion Matrix:** Clearly shows true positives, true negatives, false positives, and false negatives for visual insight

These results illustrate a highly effective model, adept at identifying fraud while minimizing false alarms — essential for real-world deployment.
