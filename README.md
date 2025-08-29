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

VISUALIZATION:

<img width="558" height="393" alt="image" src="https://github.com/user-attachments/assets/b1dc3c12-0295-4aa0-8192-8e28854d4537" />

<img width="571" height="393" alt="image" src="https://github.com/user-attachments/assets/9ed53770-c598-4be8-9e07-646ccdf39a45" />

<img width="561" height="393" alt="image" src="https://github.com/user-attachments/assets/3b928ccf-7f69-4c46-b64f-6b1acdaa19ac" />

<img width="604" height="393" alt="image" src="https://github.com/user-attachments/assets/8fbc711a-39a3-45b2-82af-59fa7da1f5d7" />

<img width="558" height="393" alt="image" src="https://github.com/user-attachments/assets/f88a8509-849d-4dfc-b7a6-769e7de1c9ee" />

<img width="705" height="596" alt="image" src="https://github.com/user-attachments/assets/902b1d0e-110f-4a22-a669-b8496779224c" />





