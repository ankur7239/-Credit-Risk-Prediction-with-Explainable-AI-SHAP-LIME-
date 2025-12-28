# -Credit-Risk-Prediction-with-Explainable-AI-SHAP-LIME-
Built an explainable credit risk prediction model using Random Forest, SHAP, and LIME to deliver transparent and trustworthy loan decision insights.
# Credit Risk Prediction with Explainable AI (SHAP & LIME)

## 📌 Project Overview
This project focuses on predicting whether a loan applicant is likely to default using
machine learning models. Since financial decisions require transparency and trust,
the model is explained using Explainable AI (XAI) techniques such as **SHAP** and **LIME**.

The goal is not only high prediction performance, but also **clear justification of
loan approval or rejection decisions**, making the system suitable for real-world
financial use cases.

---

## 🧠 Problem Statement
Traditional black-box machine learning models achieve high accuracy but fail to explain
*why* a decision was made. In finance, this is risky due to regulatory, ethical, and
business requirements.

This project answers:
- Why was a loan rejected?
- Which features increase default risk?
- How can model decisions be made trustworthy?

---

## 📊 Dataset
- Source: Kaggle (Credit Risk Dataset)
- Type: Tabular financial data
- Target variable: Loan default (binary classification)
- Includes demographic, financial, and credit-related features

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Random Forest Classifier
- SHAP (Explainable AI)
- LIME (Local Explainability)
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🔄 Project Workflow
1. **Data Understanding & Cleaning**
   - Exploratory Data Analysis
   - Handling missing values
   - Target class imbalance analysis

2. **Feature Engineering & Preprocessing**
   - Categorical encoding
   - Feature scaling
   - Train-test split

3. **Model Development**
   - Baseline model
   - Random Forest classifier
   - Evaluation using Accuracy, Precision, Recall, F1-score

4. **Explainable AI (Core Contribution)**
   - SHAP for global feature importance
   - SHAP for class-specific explanations
   - LIME for instance-level decision explanations

---

## 📈 Key Results
- Built a robust credit risk prediction model
- Identified top features contributing to loan default
- Successfully explained individual predictions using SHAP & LIME
- Debugged and resolved real-world SHAP integration issues

---

## 💡 Business Impact
This system can help financial institutions:
- Reduce loan default risk
- Justify loan decisions to customers and regulators
- Detect bias and improve fairness
- Increase transparency and trust in ML systems

---

## 🚀 Conclusion
This project demonstrates how machine learning models can be made transparent and
trustworthy using Explainable AI. It bridges the gap between predictive performance
and real-world deployability in financial applications.
