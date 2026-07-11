# 📊 Task 1: Term Deposit Subscription Prediction (Bank Marketing)

## 📌 Project Overview
This project focuses on predicting whether a bank customer will subscribe to a term deposit based on demographic information, financial details, and previous marketing campaign interactions.

The objective is to build and compare multiple classification models while applying Explainable AI (XAI) techniques to interpret model predictions.

---

## 🎯 Objective
- Predict customer subscription to a term deposit.
- Compare the performance of different classification algorithms.
- Interpret model predictions using SHAP.
- Extract meaningful business insights from customer behavior.

---

## 📂 Dataset
**Dataset:** Bank Marketing Dataset (UCI Machine Learning Repository)

The dataset contains customer demographic information, financial attributes, and previous marketing campaign details used to predict whether a customer will subscribe to a term deposit.

---

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP

---

## 📋 Project Workflow

1. Import Required Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning & Preprocessing
5. Feature Encoding
6. Exploratory Data Analysis (EDA)
7. Model Training
   - Logistic Regression
   - Random Forest Classifier
8. Model Evaluation
   - Accuracy
   - Confusion Matrix
   - Precision
   - Recall
   - F1-Score
   - ROC Curve
9. Explainable AI (SHAP)
10. Final Conclusion

---

## 📊 Model Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score

---

## 🔍 Explainable AI

To improve model transparency, SHAP (SHapley Additive exPlanations) was used to explain individual predictions and identify the most influential features affecting customer subscription decisions.

---

## 📈 Key Insights

- Proper preprocessing significantly improves model performance.
- Random Forest generally performs better than Logistic Regression on this dataset.
- Customer contact history and campaign-related features have a strong influence on prediction outcomes.
- SHAP explanations help understand why the model predicts a customer is likely (or unlikely) to subscribe.

---

## 📁 Repository Structure

```
Task1_Bank_Marketing_Prediction/
│
├── Task1_Bank_Marketing_Prediction.ipynb
├── bank.csv
├── README.md
└── images/ (optional)
```

---

## 🚀 How to Run

1. Clone this repository

```bash
git clone <repository-link>
```

2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn shap
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all cells sequentially.

---

## 🎓 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Classification Modeling
- Model Evaluation
- Explainable AI (SHAP)
- Customer Behavior Analysis

---

## 👨‍💻 Author

**Muhammad Miswan**

BS Artificial Intelligence  
Dawood University of Engineering & Technology

LinkedIn: www.linkedin.com/in/muhammadmiswan

---

⭐ If you found this project helpful, consider giving it a star.
