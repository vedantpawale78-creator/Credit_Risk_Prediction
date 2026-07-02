# Credit Risk Prediction using Random Forest

A machine learning project that predicts the credit/loan default risk of applicants using a **Random Forest Classifier**. The project covers the full ML pipeline — from data cleaning and exploratory analysis to model training, evaluation, and reporting.

## 📌 Project Overview

Financial institutions need reliable ways to assess whether a loan applicant is likely to default. This project builds a supervised classification model that predicts credit risk (default vs. no default) based on applicant and financial data, helping automate and support lending decisions.

## 🎯 Objective

- Clean and preprocess raw applicant/loan data
- Perform exploratory data analysis (EDA) to understand key risk factors
- Engineer relevant features for better model performance
- Train and evaluate a classification model to predict default risk
- Generate a clear accuracy/performance report

## 🗂️ Dataset

- The dataset contains applicant details such as income, loan amount, credit history, employment status, and other financial attributes, along with a target label indicating default status.
- Raw data was cleaned to handle missing values, duplicates, and inconsistent entries before modeling.
- Final cleaned dataset is included in the repo as a CSV export.

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, scikit-learn, Matplotlib/Seaborn
- **Model:** Random Forest Classifier
- **Environment:** Jupyter Notebook

## 🔄 Workflow

1. **Data Cleaning** – Handled missing values, removed duplicates/outliers, fixed data types
2. **EDA** – Analyzed feature distributions and correlations with default risk
3. **Feature Engineering** – Encoded categorical variables, scaled numerical features
4. **Train-Test Split** – Split cleaned data into training and testing sets
5. **Model Training** – Trained a **Random Forest Classifier** on the processed data
6. **Evaluation** – Assessed performance using accuracy, precision, recall, F1-score, and confusion matrix
7. **Reporting** – Generated a PDF accuracy report summarizing model performance

## 📁 Repository Structure

```
credit-risk-prediction/
│
├── data/
│   └── cleaned_dataset.csv        # Cleaned, ready-to-use dataset
│
├── notebooks/
│   └── credit_risk_model.ipynb    # Full notebook: EDA, preprocessing, training, evaluation
│
├── reports/
│   └── accuracy_report.pdf        # Model performance/accuracy report
│
├── README.md
└── requirements.txt
```

## 📊 Results

| Metric      | Score |
|-------------|-------|
| Accuracy    | 93%   |
| Model Used  | Random Forest Classifier |

The Random Forest model outperformed baseline models due to its ability to handle non-linear relationships and reduce overfitting through ensemble averaging of multiple decision trees.

## 🚀 How to Run

```bash



```

## 📄 Accuracy Report

A detailed PDF report (`reports/accuracy_report.pdf`) is included, covering:
- Confusion matrix
- Precision, recall, F1-score
- Feature importance analysis

## 🧠 Model: Why Random Forest?

Random Forest was chosen as the final model because it:
- Handles both numerical and categorical features well
- Is robust to outliers and missing data
- Provides feature importance, useful for interpreting risk factors
- Generally performs better than a single Decision Tree by reducing variance through ensembling

## 📬 Contact

Feel free to reach out for feedback, suggestions, or collaboration on this project.
