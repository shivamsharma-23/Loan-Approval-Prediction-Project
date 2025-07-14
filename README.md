 Loan Approval Prediction Project
 project Overview
This project aims to develop a machine learning classification model to predict the approval of loan applications based on various financial and personal factors of the applicant. Alongside this, a detailed Power BI dashboard was created to visualize approval trends and patterns, allowing for data-driven decision-making.

 Objective
Predict the likelihood of loan approval using financial indicators such as income, credit score, assets, and personal features like education and self-employment status.
Also, create an interactive Power BI dashboard to explore applicant segments and model-driven lending insights.

 Dataset Summary
 1. Raw Data – loan_approval_dataset.xlsx
Contains unprocessed applicant data:

Financial indicators: income_annum, loan_amount, loan_term, cibil_score, residential/commercial/luxury/bank assets

Personal attributes: education, self_employed, dependents

Target column: loan_status (Approved / Rejected)

 2. Final Data – loan_predictions_final.xlsx
Preprocessed version with:

Cleaned and scaled numeric columns

Label-encoded categorical variables

Feature engineered columns:

income_to_loan_ratio

asset_total

Final predictions from a trained ML classifier

 Process Workflow
 1. Data Preprocessing
Handled missing values

Label encoded: education, self_employed, loan_status

Scaled numeric features using StandardScaler

Removed any data inconsistencies and checked for outliers

 2. Exploratory Data Analysis (EDA)
Performed using seaborn and matplotlib:

Approval distribution by education, self_employed

Loan amount vs income relationships

CIBIL score impact

Outlier detection using box plots

 3. Feature Engineering
Added new meaningful features:

income_to_loan_ratio

asset_total = Sum of all asset types

 4. Machine Learning Model
Used Random Forest Classifier with train-test split:

Metrics evaluated: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

Achieved reliable prediction performance for classifying loan approvals

 Power BI Dashboard
An interactive dashboard was built to visualize and understand:

 Total applicants and approval rates (KPI cards)

 Loan status by education level

 Impact of self-employment on approval

 CIBIL score patterns of approved vs rejected

 Applicant segmentation by loan term, dependents, income

 Scatter plots of income vs loan amount with prediction insights

 Slicers for filtering by education, self-employment, dependents, and loan term

 Tools & Technologies
Tool	Purpose
Python (Jupyter Notebook)	Preprocessing, ML modeling
Pandas, NumPy	Data manipulation
Seaborn, Matplotlib	EDA visualizations
Scikit-learn	ML pipeline
Power BI	Dashboard & business insights
Excel	Final data export

 Project Highlights
 Realistic classification scenario using practical financial data

 Powerful visual analysis through Power BI

 Effective feature engineering improved prediction performance.
