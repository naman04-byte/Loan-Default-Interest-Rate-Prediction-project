# Loan Default & Interest-Rate Prediction
End-to-end ML project on 9,578 loan records: default classification + interest-rate regression. Handled class
imbalance (~16% defaulters) with class weights, evaluating on F1/Recall/ROC-AUC instead of misleading accuracy.
Logistic Regression won classification (best F1 & ROC-AUC); XGBoost won regression with R² ≈ 0.76.
EDA showed low FICO score and high interest rate to be associated with higher default rates.
**Tech:** Python, pandas, scikit-learn, XGBoost

