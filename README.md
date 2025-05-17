# Loan-Default-Prediction-DeepLearning
# 🏠 Home Loan Default Prediction – Deep Learning Project

This project aims to build a deep learning model that predicts whether a loan applicant is likely to default, based on historical loan data. With a highly imbalanced dataset and multiple features, the project focuses on data preprocessing, balancing, and model optimization to ensure accurate and secure lending decisions.

---

## 🧾 Project Objective

**Goal:** Predict the probability of loan default using past applicant data.  
**Domain:** Finance / Lending / Credit Risk

Financial institutions need to assess risk effectively. This deep learning-based predictive model helps financial institutions identify high-risk loan applications before approval.

---

## 📂 Dataset Overview

- Contains past home loan applications and outcomes (default or not)
- Highly imbalanced (majority of applicants repay loans successfully)
- Includes:
  - Demographic information
  - Employment and financial history
  - Loan characteristics
  - Repayment status

**Target Variable:** `Loan_Default` (0 = no default, 1 = default)

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Pandas & NumPy** – Data cleaning & transformation
- **Matplotlib & Seaborn** – Visualization & EDA
- **Scikit-learn** – Preprocessing & balancing
- **TensorFlow / Keras** – Deep learning model
- **Imbalanced-learn** – SMOTE / ADASYN

---

## 🧪 Key Steps in Workflow

### ✅ 1. Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Scaled numeric features
- Addressed outliers

### 📈 2. Exploratory Data Analysis (EDA)
- Visualized distributions of income, loan amount, and default rate
- Identified patterns and correlations

### ⚖️ 3. Class Imbalance Handling
- Applied **SMOTE** to handle imbalance in the target variable

### 🤖 4. Deep Learning Model
- Built a multi-layer neural network using Keras
- Used ReLU activation, Dropout regularization, and sigmoid output
- Optimized using Adam optimizer and binary cross-entropy

### 📊 5. Evaluation
- Accuracy, Precision, Recall, F1-score
- ROC-AUC for overall performance

---

## 📌 Outcome

- Trained a robust deep learning classifier for predicting loan default risk
- Helped in making informed lending decisions
- Reduced chances of default by identifying risky applicants early

---

