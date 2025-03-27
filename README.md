# Customer-Churn-Prediction-Using-Logistic-Regression

## **Project Overview**
This project applies the **Logistic Regression algorithm** to predict customer churn in the telecom industry. The goal is to help businesses identify customers who are likely to leave and take proactive measures to retain them.

## **Dataset**
- **Source:** [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Attributes Used:** Customer demographics, account details, and subscription data.
- **Target Variable:** `Churn` (Yes/No)

## **Project Steps**

### **1. Load the Dataset**
- Imported the dataset and displayed the first few rows to understand the structure.

### **2. Data Preprocessing**
- Converted relevant numerical columns that were incorrectly stored as strings.
- Checked for and handled missing values.
- Transformed categorical variables into numeric representations using Label encoding.

### **3. Splitting Data into Training & Testing Sets**
- Split the dataset into training and testing sets to evaluate model performance effectively.

### **4. Feature Scaling**
- Applied **StandardScaler** to standardize the feature set to improve model convergence and accuracy.

### **5. Train the Logistic Regression Model**
- Trained a **Logistic Regression** model on the preprocessed and scaled training data.

### **6. Make Predictions & Evaluate Performance**
- Used the trained model to make predictions on the test data.
- Evaluated the model's performance using accuracy score and classification metrics.

## **Final Predictions & Insights**
- The model predicts customer churn based on historical data.
- Provides a **baseline accuracy** without additional optimizations.
- Helps businesses identify customers at risk of churn and take preventive actions.
