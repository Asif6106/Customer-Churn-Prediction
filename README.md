# Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. This project uses Machine Learning to predict whether a customer is likely to leave the service based on customer demographics, account information, and service usage.

The goal is to help businesses identify customers at risk of churning so they can take proactive actions to improve customer retention.

---

## 📊 Dataset

- **Dataset:** IBM Telco Customer Churn Dataset
- **Total Records:** 7,032
- **Features:** 30
- **Target Variable:** Churn

Target Values:

- **0** → Customer Stayed
- **1** → Customer Left

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📋 Project Workflow

### 1. Data Loading
- Loaded dataset using Pandas
- Explored dataset structure
- Checked missing values
- Checked duplicate records

### 2. Data Cleaning
- Removed `customerID`
- Converted `TotalCharges` to numeric
- Handled missing values

### 3. Exploratory Data Analysis (EDA)

Performed data visualization to understand customer behavior.

Visualizations include:

- Customer Churn Distribution
- Gender vs Churn
- Contract Type vs Churn
- Internet Service vs Churn
- Payment Method vs Churn

### 4. Data Preprocessing

- Label Encoding
- One-Hot Encoding
- Feature Scaling using StandardScaler
- Train-Test Split

### 5. Machine Learning Models

Implemented and compared the following models:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 6. Hyperparameter Tuning

Optimized the Random Forest model using **GridSearchCV**.

### 7. Model Evaluation

Performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score
- Feature Importance

---

## 📈 Model Performance

| Metric | Value |
|--------|-------|
| Accuracy | **79.10%** |
| ROC-AUC Score | **0.82** |

Among all the models, **Random Forest** achieved the best overall performance and was selected as the final model.

---

## 📷 Results

### ROC Curve

![ROC Curve](images/roc_curve.png)

---

### Feature Importance

![Feature Importance](images/feature_importance.png)

---

### Customer Churn Distribution

![Customer Churn Distribution](images/churn_distribution.png)

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── customer_churn.csv
├── requirements.txt
├── README.md
├── images/
│   ├── churn_distribution.png
│   ├── contract_vs_churn.png
│   ├── feature_importance.png
│   └── roc_curve.png
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Customer-Churn-Prediction.git
```

### 2. Navigate to the project directory

```bash
cd Customer-Churn-Prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

```bash
jupyter notebook Customer_Churn_Prediction.ipynb
```

---

## 🚀 Future Improvements

- Deploy the model using Streamlit
- Try XGBoost and CatBoost models
- Perform advanced feature engineering
- Improve prediction accuracy
- Add customer retention recommendations

---

## 👨‍💻 Author

**Asif Sheikh**

GitHub: https://github.com/Asif6106

---

## 📄 License

This project is created for learning and educational purposes.
