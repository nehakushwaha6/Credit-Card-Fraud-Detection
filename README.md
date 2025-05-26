# 💳 Credit Card Fraud Detection

A Machine Learning project focused on detecting fraudulent credit card transactions using supervised learning techniques. This project applies data preprocessing, exploratory data analysis, model building, and evaluation on a real-world dataset to identify fraudulent behavior effectively.

---

## 📌 Table of Contents
- [About the Project]
- [Dataset]
- [Technologies Used]
- [Project Workflow]
- [Model Evaluation]
- [Results]


---

## 📝 About the Project

Credit card fraud is a significant problem in the banking and financial sectors. The goal of this project is to build a machine learning model that can accurately classify credit card transactions as fraudulent or genuine.

This project demonstrates:
- Effective handling of **imbalanced datasets**
- Use of various **classification algorithms**
- Deployment of **evaluation metrics** for performance measurement

---

## 📂 Dataset

- **Source**: [Jupyternotebook - Credit Card Fraud Detection].

- Features:
  - 31 total columns (Time, V1–V28, Amount, Class)
  - Class `0` = Genuine, Class `1` = Fraudulent
  - Highly imbalanced dataset (only 0.17% fraud cases)

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Streamlit
- Scikit-Learn (Logistic Regression, Decision Tree, Random Forest, etc.)
- SMOTE (for handling imbalanced data)
- Jupyter Notebook / Google Colab

---

## 🔄 Project Workflow

1. **Data Loading & Cleaning**
2. **EDA (Exploratory Data Analysis)**
3. **Data Preprocessing**
   - Feature Scaling
   - Handling Imbalanced Dataset using SMOTE
4. **Model Training**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost
5. **Model Evaluation**
   - Accuracy
   - Precision, Recall, F1 Score
   - ROC-AUC Curve
6. **Confusion Matrix Visualization**

---

## 📈 Model Evaluation

| Model              | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------------------|----------|-----------|--------|----------|---------|
| Logistic Regression | 99.2%    | 0.88      | 0.79   | 0.83     | 0.95    |
| Decision Tree       | 99.5%    | 0.91      | 0.82   | 0.86     | 0.96    |
| Random Forest       | 99.7%    | 0.93      | 0.85   | 0.89     | 0.98    |

> ✅ Random Forest gave the best overall performance in detecting fraudulent transactions.

---

## ✅ Results

- Achieved **high precision and recall** despite data imbalance.
- Demonstrated effective use of **SMOTE** and **cross-validation**.
- Visualized important features influencing fraud detection.

---


