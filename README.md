# customer-churn-ml-pipeline
End-to-end machine learning project for predicting customer churn using the IBM Telco Customer Churn dataset. Includes EDA, preprocessing pipeline, multiple ML models, and performance evaluation.

# 📊 Telco Customer Churn Prediction

This project predicts customer churn using the **IBM Telco Customer Churn Dataset**.  
It includes full **EDA**, **preprocessing pipelines**, **model training**, and **evaluation** using:

- Logistic Regression  
- Random Forest  
- XGBoost  

---

## 🚀 Project Features
- Complete EDA with visualizations  
- Preprocessing using `ColumnTransformer`  
- One-hot encoding and scaling  
- Multiple ML models with evaluation 


## 📈 Model Performance Summary

| Model                 | Accuracy | Recall (Churn) | F1-Score (Churn) |
|----------------------|----------|----------------|------------------|
| Logistic Regression   | 0.74     | 0.78           | 0.61             |
| Random Forest         | 0.78     | 0.47           | 0.53             |
| XGBoost               | 0.75     | 0.67           | 0.59             |



Among all evaluated models, Random Forest achieved the highest overall accuracy (0.78), Logistic Regression delivered the strongest recall for churn cases (0.78), and XGBoost provided the best balance between recall and F1-score, making it the most stable performer across metrics.
