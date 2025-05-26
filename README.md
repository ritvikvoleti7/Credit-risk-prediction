# Credit-risk-prediction

Overview
This dataset, named Dataset.csv, contains information about individuals' loan applications, their financial profiles, and loan characteristics. The dataset is designed to assist in predicting loan outcomes and analyzing factors influencing loan approval and repayment. It is particularly useful for machine learning models, statistical analyses, and exploratory data analysis (EDA).

File Format
The dataset is a CSV (Comma-Separated Values) file, making it easy to load into data analysis tools like Python (pandas), Excel, R, or SQL databases.

Data Description
The dataset contains 12 columns and several thousands of rows, each representing a single loan application. Below is a detailed description of each column:

Column Name	Description	Data Type
person_age	Age of the applicant (in years).	Integer
person_income	Annual income of the applicant (in USD).	Integer
person_home_ownership	Type of home ownership of the applicant (RENT, MORTGAGE, OWN, OTHER).	Categorical
person_emp_length	Employment length of the applicant (in years).	Float
loan_intent	Purpose of the loan (e.g., EDUCATION, PERSONAL, VENTURE, MEDICAL, HOMEIMPROVEMENT).	Categorical
loan_grade	Grade assigned to the loan based on its risk (A to G, with A being the least risky).	Categorical
loan_amnt	Amount of the loan requested by the applicant (in USD).	Integer
loan_int_rate	Interest rate of the loan (in percentage).	Float
loan_status	Loan repayment status (0 for paid back, 1 for default).	Integer
loan_percent_income	Loan amount as a percentage of the applicant's income.	Float
cb_person_default_on_file	Whether the applicant has a history of default (Y for yes, N for no).	Categorical
cb_person_cred_hist_length	Length of the applicant's credit history (in years).	Integer
Key Highlights
Loan Prediction: The dataset is suitable for predicting whether a loan will be repaid or defaulted based on various features.
Risk Analysis: It provides insights into factors like loan grades, interest rates, and credit history, which can be used to assess risk.
Diversity of Purposes: Loans in the dataset span multiple intents, including education, personal use, and business ventures.
Use Cases
Machine Learning:
Build supervised learning models to predict loan repayment (loan_status).
Use features like person_income, loan_amnt, and loan_percent_income to train regression or classification models.
Exploratory Data Analysis (EDA):
Analyze correlations between features like loan_grade and loan_int_rate.
Study the distribution of default rates across different loan_intent values.
Risk Assessment:
Identify patterns in loan defaults based on demographic and financial factors.
Assess the quality of loans based on loan_grade and repayment history.
