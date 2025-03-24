# Loan Approval 

This project focuses on building a machine learning model to predict loan approval based on various factors such as applicant's credit score, income, loan amount, employment status, and other demographic details. The objective is to build a model that can help financial institutions make data-driven decisions regarding loan approvals.

## Key Insights:
- Identified important features influencing loan approval (e.g., applicant's credit score, annual income, loan amount).
- Built a machine learning model to predict loan approval based on historical data.
- Evaluated model performance using metrics like accuracy, precision, recall, and F1 score.
- Analyzed the impact of various factors (e.g., gender, marital status, number of dependents) on loan approval chances.

## Techniques Used:
- **Data Preprocessing**: Handled missing values, data scaling, encoding categorical variables, and outlier treatment.
- **Feature Engineering**: Created new features based on existing data to improve model performance.
- **Modeling**: Trained machine learning models (e.g., Logistic Regression, Random Forest, Decision Trees) to predict loan approval.
- **Model Evaluation**: Evaluated model performance using cross-validation and classification metrics (accuracy, precision, recall, F1-score).

## Data Overview:
The dataset includes the following key features:
- **Loan ID**: Unique identifier for each loan application.
- **Gender**: Gender of the applicant.
- **Marital Status**: Marital status of the applicant.
- **Dependents**: Number of dependents of the applicant.
- **Education**: Education level of the applicant.
- **ApplicantIncome**: Income of the applicant.
- **CoapplicantIncome**: Income of the coapplicant (if any).
- **LoanAmount**: Amount of the loan requested.
- **CreditHistory**: Credit history of the applicant (whether they have a history of credit defaults).
- **PropertyArea**: Area where the applicant resides (urban/rural/semiurban).
- **LoanStatus**: Target variable (whether the loan was approved or not).

## Installation:
To run this analysis, you will need to install the following dependencies:
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install dependencies using the following command:
```bash
pip install -r requirements.txt
