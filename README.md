# credit-risk-prediction-using-machine-learning
Predicting loan default risk using machine learning models (Logistic Regression, Random Forest, XGBoost) on financial and credit data.
##  Dataset Overview
- Source: Kaggle (credit_risk_dataset.csv)
- Rows: 32,581 | Columns: 12
- Target: `loan_status` (1 = default, 0 = no default)

---

##  Models Built
1. **Logistic Regression**
   - Accuracy: 86%
   - Recall (Default): 56%
   - F1 Score (Default): 0.65  

2. **Random Forest**
   - Accuracy: 93%
   - Recall (Default): 72%
   - F1 Score (Default): 0.83  

3. **XGBoost**
   - Accuracy: 93%
   - Recall (Default): 75%
   - F1 Score (Default): 0.83  

---

##  Feature Importance
Top features according to XGBoost:
- `person_income`
- `loan_int_rate`
- `loan_percent_income`

---

##  Business Value
- Improve credit approval decisions
- Reduce default risk
- Increase trust in loan scoring systems

---

##  Conclusion
XGBoost achieved the best balance of performance and interpretability, making it an ideal model for real-world credit scoring tasks.
