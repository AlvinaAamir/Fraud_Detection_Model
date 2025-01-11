# Fraud Detection Model

## Objective
This project aims to build a machine learning model to detect fraudulent credit card transactions, minimizing undetected fraud while reducing false positives.

---

## Dataset
- **Source**: [Fraud Detection Dataset](https://raw.githubusercontent.com/delinai/schulich_ds1/main/Datasets/Fraud_Detection_Dataset.csv)
- **Features**:
  - Transaction Amount
  - Merchant Category
  - Location
  - Previous Transaction Amount
  - Time Since Last Transaction
  - Device Type
  - Fraud (Yes/No)

---

## Tools & Techniques
- **Language**: Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- **Models**:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - Support Vector Machines
- **Evaluation Metrics**:
  - Precision, Recall, F1-Score
  - ROC-AUC Curve

---

## Key Insights
1. **High Fraud Transactions**:
   - Fraudulent transactions tend to occur more frequently with specific merchant categories (e.g., electronics and travel).
2. **Time Between Transactions**:
   - Shorter times between transactions were associated with higher fraud likelihood.
3. **Device Type**:
   - Mobile transactions had a slightly higher incidence of fraud compared to desktop transactions.

---

## Final Model
- **Model Selected**: Gradient Boosting Classifier
- **Why Selected**:
  - Achieved the best performance with an F1-score of 0.92 and ROC-AUC of 0.95.
  - Robust in identifying fraudulent transactions with minimal false positives.

---

## Recommendations for Business Use
1. **Fraud Prevention Alerts**:
   - Integrate the model into transaction monitoring systems to flag high-risk transactions for manual review.
2. **Customer Education**:
   - Notify customers about common fraudulent practices for better awareness.
3. **Merchant Monitoring**:
   - Track specific merchant categories prone to fraud and take preventive measures.

---

## Files
1. **Jupyter Notebook**: [FinalExam.ipynb](./FinalExam.ipynb)
2. **Dataset**: [Fraud Detection Dataset](./Fraud_Detection_Dataset.csv)

---

## How to Use
1. Download the Jupyter Notebook and dataset.
2. Run the notebook to reproduce the analysis and results.
3. Use the trained model to integrate with transaction systems.

