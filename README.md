# Customer Churn Prediction (Machine Learning Project)

## 📌 Project Goal
Predict customer churn using machine learning models based on telecom customer data.

## 📂 Dataset
- Telco Customer Churn dataset (Kaggle)
- Rows: 7043
- Columns: 21
- Target: “Churn” (Yes/No)

## 🛠 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-Learn (SMOTE)
- Random Forest Classifier
- Pipeline + ColumnTransformer

## 🔍 ML Workflow
1. Data Cleaning  
2. Convert TotalCharges to numeric  
3. Drop customerID  
4. One-Hot Encode categorical variables  
5. Scale numeric features  
6. Train-Test Split  
7. Handle imbalance using SMOTE  
8. Train Logistic Regression  
9. Train Random Forest (best performer)

## 📊 Final Model Performance
- **Accuracy:** ~0.77
- **ROC-AUC:** ~0.81
- **Churn Recall:** ~0.56

## ⭐ Top Important Features
- Tenure  
- Contract Type  
- Monthly Charges  
- Internet Service  
- Online Security  
- Tech Support  

## 📁 Files in Repository
- `churn_model.ipynb` — full Jupyter notebook  
- `README.md` — documentation  

## 🚀 Next Steps (Optional)
- Build a Streamlit web app  
- Deploy the model  
- Hyperparameter tuning  
