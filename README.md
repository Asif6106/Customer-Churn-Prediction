Customer Churn Prediction using Machine Learning
📌 Project Overview

Customer churn is one of the biggest challenges for telecom companies. This project predicts whether a customer is likely to leave the service based on customer demographics, account information, and service usage.

The objective is to build a machine learning model that helps businesses identify customers at risk of churning so they can take preventive actions.

📊 Dataset

Dataset: Telco Customer Churn Dataset

Total Records: 7,032
Features: 30
Target Variable: Churn
0 → Customer Stayed
1 → Customer Left
🛠 Technologies Used
Python
NumPy
Pandas
Matplotlib
Scikit-learn
Joblib
Jupyter Notebook
📋 Project Workflow
1. Data Loading
Loaded dataset using Pandas
Explored dataset structure
Checked missing values
Checked duplicate records
2. Data Cleaning
Removed customerID
Converted TotalCharges to numeric
Handled missing values
3. Exploratory Data Analysis (EDA)

Performed analysis using visualizations.

Examples:

Customer Churn Distribution
Gender vs Churn
Contract Type vs Churn
Internet Service vs Churn
Payment Method vs Churn
4. Data Preprocessing
Label Encoding
One-Hot Encoding
Feature Scaling using StandardScaler
Train-Test Split
5. Machine Learning Models

Models implemented:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
6. Hyperparameter Tuning

Optimized Random Forest using GridSearchCV.

7. Model Evaluation

Evaluation Metrics:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix
ROC Curve
ROC-AUC Score
Feature Importance
📈 Final Model Performance
Metric	Value
Accuracy	79.10%
ROC-AUC Score	0.82
📷 Results
ROC Curve

(Insert your ROC Curve image here)

Feature Importance

(Insert your Feature Importance image here)

Churn Distribution

(Insert your Churn Distribution image here)
