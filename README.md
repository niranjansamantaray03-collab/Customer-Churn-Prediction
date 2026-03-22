# Customer Churn Prediction

## 📌 Project Overview
Customer churn is a critical problem for businesses as it directly impacts revenue and growth. This project aims to predict whether a customer will churn (leave the service) using machine learning techniques.

## 🎯 Objective
To build a classification model that identifies customers likely to churn based on their demographic and service usage data, enabling businesses to take proactive retention measures.

## 🛠 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 📊 Dataset
Telco Customer Churn Dataset from Kaggle containing customer demographics, account details, and service usage information.

## 🧹 Data Preprocessing
- Handled missing values
- Converted categorical variables using one-hot encoding
- Feature scaling applied for model improvement

## 📈 Exploratory Data Analysis (EDA)
- Analyzed customer distribution and churn patterns
- Identified key features affecting churn such as tenure, contract type, and monthly charges

## 🤖 Models Used
- Logistic Regression (Baseline Model)
- Random Forest (Improved Model)

## 📊 Model Performance
- Logistic Regression Accuracy: ~78%
- Model performs better on non-churn customers
- Moderate recall for churn class indicating improvement opportunities

## 🔍 Key Insights
- Customers with higher monthly charges are more likely to churn
- Long-term customers show lower churn rates
- Contract type significantly impacts customer retention

## 🚀 Future Improvements
- Hyperparameter tuning
- Advanced models like XGBoost
- Model deployment using Flask or Streamlit

## 👨‍💻 Author
Niranjan Samantaray
