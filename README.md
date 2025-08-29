🏦 Loan Approval Prediction
This project predicts whether a bank should approve or reject a loan application using applicant data such as income, age, credit score, and loan amount.
A Random Forest Classifier is trained on historical loan data to make predictions.

📌 Features Used
income: Applicant’s annual income
age: Applicant’s age
credit_score: Applicant’s credit score
loan_amount: Requested loan amount
Target Variable → loan_status (Approved / Rejected)

⚙️ Workflow
Data Loading & Exploration

Load dataset (loan_approval.csv)
Perform exploratory data analysis (EDA):
Summary statistics
Missing/duplicate value check
KDE plots, Boxplots, Histogram, Pie chart
Correlation heatmap
Preprocessing

Encode target variable (Approved=1, Rejected=0)
Train-test split (70% train, 30% test)
Model Training

Random Forest Classifier with 100 estimators
Trained on applicant features
Prediction

Predict probability of loan approval for new applicants

Example:

new_applicant = [[55000, 35, 720, 20000]]
model.predict_proba(new_applicant)

🚀 Example Result
For an applicant with:

Income = 55,000
Age = 35
Credit Score = 720
Loan Amount = 20,000
Model Output:

Probability of Rejection → 0.87
Probability of Approval → 0.13
✅ The applicant has a 13% chance of loan approval.

🛠️ Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn