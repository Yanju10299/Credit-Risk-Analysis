# 📊 Credit Risk Analysis

## 🔍 Introduction
Credit risk modeling estimates potential losses a financial institution may face if a borrower defaults. It helps lenders assess the **probability of default (POD)** and make informed decisions on:

- Loan approval or rejection
- Credit amount allocation
- Interest rate determination

Accurate credit risk assessment **minimizes defaults and safeguards funds**.

---

## 📂 Dataset
- Source: **[Kaggle](https://www.kaggle.com/)**
- Features:
  - **Demographics**: Age, Income, Employment Length, Home Ownership
  - **Loan attributes**: Interest Rate, Loan Purpose, Loan Amount
- **Target variable**: Credit risk classification (default vs non-default)

---

## ⚙️ Workflow

### 1. Exploratory Data Analysis (EDA)
- Univariate analysis: Distribution of Age, Income, Loan Amount
- Bivariate analysis: Relationships between features and default probability
- Target analysis: Checked class imbalance for defaults

### 2. Data Preprocessing & Feature Engineering
- Imputed missing values for numerical and categorical features
- Detected and capped outliers
- Encoded categorical features numerically
- Scaled/standardized features where necessary

### 3. Handling Imbalanced Data
- Applied **SMOTE** and **undersampling** techniques

### 4. Model Training & Evaluation
Tested multiple machine learning algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Trees
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

**Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC-AUC

---

## 📈 Results
- **Random Forest** and **XGBoost** were the top-performing models
- Random Forest achieved **93% accuracy**, effectively handling class imbalance
- XGBoost offered competitive performance with better efficiency on large datasets

---

## 📝 Conclusion
- Ensemble models (**Random Forest, XGBoost**) outperform simpler algorithms in credit risk prediction
- Comprehensive **EDA, feature engineering, and data cleaning** improve predictive performance
- Demonstrates how **machine learning enables data-driven lending decisions**

---

## 🚀 Future Work
- Explore **Neural Networks and Deep Learning models**
- Apply **model explainability** (SHAP, LIME) for transparency
- Deploy a **web-based credit risk prediction tool**

---

## 📌 Key Takeaways
- Structured ML pipeline: EDA → Preprocessing → Feature Engineering → Model Training → Evaluation
- Handled **missing data, outliers, and class imbalance**
- Compared multiple models; **Random Forest achieved 93% accuracy**
