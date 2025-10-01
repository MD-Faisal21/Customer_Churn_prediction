# 📊 Telecom Customer Churn Prediction
## 📌 Overview

- This project focuses on predicting customer churn in the telecom industry using machine learning techniques.
- Churn prediction is critical for telecom companies to identify customers likely to leave and take proactive retention measures.

The notebook covers:
- Exploratory Data Analysis (EDA)
- Feature Engineering & Preprocessing
- Model Building (Logistic Regression, Random Forest, etc.)
- Model Evaluation (Confusion Matrix, ROC-AUC, Accuracy, etc.)

## 📂 Dataset

The dataset contains customer information such as AccountWeek, ContractRenewal, DataPlan, DataUsage and churn status.

Target variable: Churn (1/0)

Link: https://www.kaggle.com/datasets/barun2104/telecom-churn

## ⚙️ Methodology

1. Data Preprocessing
  - Handling missing values
  - Exploratory Data Analysis (EDA)
  - Distribution of features
  - Correlation analysis
  - Churn rate analysis

2.Model Building

- Logistic Regression
- Decision Tree
- Random Forest
-
3.Model Evaluation
- Confusion Matrix
- ROC-AUC Score
- Accuracy, Precision, Recall, F1-score

## 📈 Results

- Logistic Regression achieved a baseline accuracy.
- Random Forest improved prediction with higher ROC-AUC score.
- The ROC curve visualization shows trade-offs between sensitivity and specificity.

## 🚀 How to Run

Clone the repository
```bash
git clone https://github.com/your-username/telecom-churn-prediction.git
cd Customer_Churn_prediction
```

Run Jupyter Notebook
```bash
jupyter notebook Telecom_Churn_Prediction.ipynb
```
## 📌 Future Improvements

- Try other models (XGBoost, LightGBM, Neural Networks)
- Hyperparameter tuning
- Feature importance analysis
- Deploy model as a web app (Flask/Streamlit)

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

## 📜 License

This project is licensed under the MIT License.
