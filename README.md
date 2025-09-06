# 💳 Loan Approval Prediction

## 📌 Overview
This project predicts whether a **loan application** will be **approved** or **rejected** using machine learning.  
It analyzes applicant information such as income, education, loan amount, credit history, and employment status.  
The goal is to help financial institutions **automate decision-making** and reduce human bias.  

---

## 🗂️ Dataset
The dataset contains the following columns:
- `Gender`, `Married`, `Dependents`, `Education`, `Self_Employed`  
- `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`  
- `Credit_History`, `Property_Area`  
- `Loan_Status` (target variable: Approved / Rejected)  

---

## ⚙️ Tech Stack
- Python 🐍  
- Pandas & NumPy (data preprocessing)  
- Matplotlib & Seaborn (visualization)  
- Scikit-learn (ML algorithms, evaluation)  

---

## 🚀 Workflow
1. Load dataset and explore data  
2. Handle missing values and encode categorical variables  
3. Split data into train and test sets  
4. Scale numerical features  
5. Train a classification model (Random Forest / Logistic Regression)  
6. Evaluate performance using Accuracy, Confusion Matrix, and Classification Report  
7. Predict loan status for new applicants  

---

## 📊 Results
- The model achieved high accuracy in predicting loan approvals.  
- **Credit history** and **income levels** were the most important predictors.  

---

## ▶️ How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/San999-dev/Loan-approval.git
   cd loan-approval-prediction
