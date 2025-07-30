# 🧠 Multiclass Health Test Prediction Model

A full machine learning pipeline built to predict patient medical test outcomes (Normal, Abnormal, Inconclusive) using a synthetic healthcare dataset.

---

## 📌 Project Overview

Access to real medical records is limited due to privacy laws. This project uses a synthetic dataset that simulates real-world hospital data to build a multiclass classification model. The goal is to predict test results and evaluate model performance in a healthcare-like context.

---

## 📁 Repository Structure

📂 Multiclass-Health-Prediction-Model
├── multiclass-health-prediction-model-5.ipynb  # Main notebook
├── README.md                                   # Project overview
└── /assets                                     # Images, charts (optional)

---

## 📊 Techniques & Tools

- **Machine Learning Models:** Random Forest, CatBoost, XGBoost, Logistic Regression, Voting Classifier  
- **Evaluation Metrics:** Accuracy, Confusion Matrix, Classification Report, ROC-AUC  
- **Feature Engineering:** Label encoding, correlation analysis, feature importance ranking  
- **Visualization:** Matplotlib, Seaborn, bar plots, heatmaps, ROC curves  
- **Tools Used:** Python, Scikit-learn, Jupyter Notebook, Pandas, NumPy  

---

## 📈 Key Highlights

- 📁 **Dataset Size:** 55,500+ synthetic patient records  
- 🧪 **Target Variable:** Medical test result (3 classes: Normal, Abnormal, Inconclusive)  
- 🔍 **Top Features Identified:** Blood Pressure, Glucose, Cholesterol, Age  
- 🧠 **Best Model:** Random Forest Classifier (Accuracy ~44%)  
- 🔧 **Ensemble Learning:** Used VotingClassifier for better generalization  
- 📊 **Dashboards & Charts:** Feature importance, class imbalance, confusion matrix

---

## 🚀 How to Run

1. Clone the repo:  
```bash
git clone https://github.com/your-username/Multiclass-Health-Prediction-Model.git
cd Multiclass-Health-Prediction-Model

