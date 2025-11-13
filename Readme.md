# 🧮 Credit Card Fraud Detection (Machine Learning Project)

This project builds a fraud risk prediction model using the ULB Credit Card Fraud dataset.  
It demonstrates end-to-end data science skills including EDA, imbalanced data handling, model development, threshold optimization, and performance monitoring.

---

## 🚀 Features

✔ Exploratory Data Analysis  
✔ PCA feature interpretation  
✔ Handling class imbalance (SMOTE / class weights)  
✔ Logistic Regression & Random Forest models  
✔ ROC-AUC: 0.983, Recall: 0.89  
✔ Fraud risk scoring and model evaluation  
✔ Visualizations: ROC, Precision-Recall, feature importance

---

## 📂 Project Structure

notebooks/
└── Fraud_Detection_EDA_Modeling.ipynb
requirements.txt
README.md

---

## 🧠 Key Insights

- Fraud is only **0.17%** → requires special handling
- Models trained with balance correction show **strong recall**
- PCA components V17, V14, V12 are highly fraud-correlated
- Best model: RandomForestClassifier (AUC = 0.983)

---

## 🛠️ Tech Stack

Python, NumPy, pandas, scikit-learn, imbalanced-learn, Matplotlib, Seaborn

---

## 📊 Results

| Model               | Precision (Fraud) | Recall (Fraud) | F1   | ROC-AUC |
| ------------------- | ----------------- | -------------- | ---- | ------- |
| Logistic Regression | 0.05              | 0.92           | 0.10 | 0.97    |
| Random Forest       | 0.28              | 0.89           | 0.43 | 0.98    |

---

## 📝 Notes

- Dataset not included (Kaggle: Credit Card Fraud Detection – ULB)
- Notebook includes EDA, preprocessing, model training, and evaluation

---

## 👤 Author

Najmus Sakib  
Data Analyst | Machine Learning Enthusiast
