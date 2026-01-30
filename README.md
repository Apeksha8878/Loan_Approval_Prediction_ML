🏦 Loan Approval Prediction using Machine Learning

📌 Overview

This project predicts whether a loan will be approved or not using machine learning.
The goal is to help banks make faster and more accurate loan decisions based on applicant details.

🎯 Objective

Predict loan approval status
Clean and preprocess real-world data
Compare machine learning models
Select the most suitable model

📊 Dataset

Records: 614
Features: Applicant income, loan amount, credit history, education, property area, etc.
Target: Loan_Status (Approved / Not Approved)

🛠️ Tools Used

Python
Pandas,NumPy
Matplotlib,Seaborn
Scikit-learn

🔄 Project Steps

Loaded and explored the dataset
Handled missing values
Converted categorical data into numerical form
Split data into training and testing sets

🤖 Models Used

🔹Random Forest (Baseline Model)
Handles tabular data well
Reduces overfitting
Provides stable performance

🔹Gradient Boosting (Improvement Attempt)

Learns from previous model errors
Tries to improve prediction accuracy
Used for comparison with Random Forest

📈 Results

Model	Accuracy
Random Forest	76%
Gradient Boosting	76%
Both models achieved similar accuracy.

✅ Final Model Choice

Random Forest was selected as the final model because it:
Is stable and reliable
Performs consistently well
Is easier to interpret

📄 Conclusion
This project shows a complete machine learning workflow, from data cleaning to model selection, using real-world loan data.
Trained machine learning models

Evaluated model performance
