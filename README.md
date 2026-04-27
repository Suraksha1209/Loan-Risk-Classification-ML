# 🏦 loan-risk-classification-ml

An intelligent Machine Learning-powered Loan Approval System designed to automate and optimize the loan verification process for financial institutions.

# 📌 Project Overview

This System is built to help banks replace their traditional manual loan verification process with a data-driven, intelligent system.

Previously, loan officers manually evaluated applications by reviewing income proofs, employment details, and credit history. This approach was:

- ⏳ Time-consuming

- ⚖️ Biased & inconsistent

- 📉 Risk-prone (financial losses)

This system predicts whether a loan should be Approved (1) or Rejected (0) using historical customer data.

# 🎯 Problem Statement

A mid-sized financial company, SecureTrust Bank, faced two major issues:

- ❌ Good customers were sometimes rejected → Loss of business

- ⚠️ High-risk customers were sometimes approved → Financial losses

To solve this, the bank introduced an intelligent loan approval system powered by Machine Learning.

# 🧠 Objective

Build a Machine Learning model that:

- Learns hidden patterns from past loan applications

- Predicts loan approval status accurately

- Provides fast and unbiased decisions

- Assists final human verification

# 📊 Dataset Description

Each row represents a loan applicant with personal, financial, and credit-related attributes.

**🗂️ Features**
| Column Name        | Description                             |
| ------------------ | --------------------------------------- |
| Applicant_ID       | Unique applicant ID                     |
| Applicant_Income   | Monthly income of applicant             |
| Coapplicant_Income | Monthly income of co-applicant          |
| Employment_Status  | Salaried / Self-Employed / Business     |
| Age                | Applicant age                           |
| Marital_Status     | Married / Single                        |
| Dependents         | Number of dependents                    |
| Credit_Score       | Credit bureau score                     |
| Existing_Loans     | Number of running loans                 |
| DTI_Ratio          | Debt-to-Income ratio                    |
| Savings            | Savings balance                         |
| Collateral_Value   | Value of collateral                     |
| Loan_Amount        | Requested loan amount                   |
| Loan_Term          | Loan duration (months)                  |
| Loan_Purpose       | Home / Education / Personal / Business  |
| Property_Area      | Urban / Semi-Urban / Rural              |
| Education_Level    | Graduate / Postgraduate / Undergraduate |
| Gender             | Male / Female                           |
| Employer_Category  | Govt / Private / Self                   |
| Loan_Approved      | 🎯 Target (1 = Approved, 0 = Rejected)  |

# ⚙️ Technologies Used

- 🐍 Python
- 📊 Pandas & NumPy
- 📈 Matplotlib & Seaborn
- 🤖 Scikit-learn
- 📓 Jupyter Notebook

# 🔬 Machine Learning Models Used

- Logistic Regression

- K-Nearest Neighbors (KNN)

- Naive Bayes


# 📈 Model Evaluation Metrics

Models were compared based on:

_ Precision (important to reduce approving risky customers)

-  Recall

-  F1-Score

-  Accuracy
  
-  Confusion Matrix

_The best-performing model was selected based on business needs and evaluation metrics._

# 🚀 Project Workflow
```
1. Data Cleaning

2. Exploratory Data Analysis (EDA)

3. Feature Engineering

4. Data Preprocessing

5. Model Training

6. Model Evaluation

7. Model Comparison

8. Final Model Selection
```

# 💡 Key Benefits

✅ Faster loan approval decisions
✅ Reduced human bias
✅ Improved risk management
✅ Increased business profitability

```
# 📁 Repository Structure

loan-risk-classification-ml/
│
├── Intelligent Loan Approval Classification System.ipynb
├── Dataset.csv
└── README.md
```
Machine Learning Enthusiast | AI Engineer in Progress 🚀
