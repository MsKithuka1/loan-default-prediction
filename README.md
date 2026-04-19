## 📌 Project Overview

This project builds a machine learning model to predict loan default risk using borrower financial and credit-related data. The goal is to identify key factors that influence whether a borrower is likely to default on a loan.

---

## 🎯 Objective

To analyze loan applicant data and develop a predictive model that classifies borrowers as either high-risk (default) or low-risk (non-default) based on financial and demographic features.

---

## 📊 Dataset Features

The dataset includes information such as:

* Income levels
* Loan amount
* Loan interest rate
* Employment length
* Credit history length
* Loan purpose and grade
* Loan-to-income ratio

Target variable:

* **loan_status** (0 = no default, 1 = default)

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Logistic Regression

---

## 🔍 Process Followed

1. Data cleaning and handling missing values
2. Exploratory data analysis (visualizations and distributions)
3. Feature engineering (including loan-to-income ratio)
4. Encoding categorical variables
5. Model training using Logistic Regression
6. Model evaluation using accuracy, confusion matrix, and classification report
7. Feature importance analysis

---

## 📈 Key Findings

* The most important predictor of loan default is the **loan-to-income ratio (loan_percent_income)**
* Borrowers with higher relative loan burden are more likely to default
* Income and loan amount alone are less predictive than their ratio
* The final model improved recall for detecting defaulters after handling class imbalance

---

## 📊 Model Performance

* Accuracy: ~0.81
* Improved recall for default cases after class balancing
* Confusion matrix analysis used to evaluate risk detection performance

---

## 💡 Key Insight

Relative borrowing capacity (loan amount compared to income) is a stronger predictor of default risk than individual financial attributes alone.

---

## 🚀 Future Improvements

* Use ensemble models (Random Forest, XGBoost)
* Improve feature engineering
* Handle class imbalance with advanced techniques (SMOTE)
* Deploy model as a simple web app

---

## 👤 Author

Actuarial Science background with growing focus in Data Science and Machine Learning.
