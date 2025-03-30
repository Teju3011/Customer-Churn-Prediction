# **Customer Churn Prediction**

## **Overview**

This project focuses on predicting customer churn using a machine learning model trained on the Telco Customer Churn dataset. The model utilizes feature engineering, data preprocessing, and a Random Forest classifier for predictions. Additionally, SHAP (SHapley Additive exPlanations) is used for model interpretability.

## **Features**

- Handles missing values

- Encodes categorical variables

- Feature scaling for improved model performance

- Random Forest model for prediction

- Model evaluation using accuracy, precision, recall, and ROC-AUC score

- SHAP analysis for explainability

- Feature importance visualization
## **Evaluation Metrics**

- Accuracy: Measures overall correctness of predictions.

- Precision: Fraction of correctly predicted positive cases.

- Recall: Measures how many actual positive cases were correctly predicted.

- ROC-AUC: Measures the probability that the model ranks a randomly chosen positive case higher than a randomly chosen negative case.

## **Model Interpretation**

- SHAP (SHapley Additive exPlanations) is used to understand the impact of each feature on the model's predictions. The script generates:

- SHAP Summary Plot

- SHAP Feature Importance Bar Chart

**Results**

- The feature importance plot provides insight into which features drive churn predictions.

- SHAP visualizations help interpret individual predictions.
