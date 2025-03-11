# CreditScorePrediction_202401100300153
Project Overview:
The aim of this project is to predict the credit score of a customer based on their Age, Income, and Loan Amount using Machine Learning. Banks and financial institutions use Credit Scores to determine whether to approve or reject a loan application. Our project uses Random Forest Regressor to predict the credit score accurately.

How the Project Works:
We have a dataset (credit_data.csv) containing:

Age → Customer's Age
Income → Customer's Annual Income
Loan Amount → Loan Amount applied by Customer
Credit Score → Target variable (which we want to predict)
We cleaned the data by removing unnecessary columns like CustomerID.

We split the data into:

Training Data (80%) → Used to train the model.
Testing Data (20%) → Used to test the model's accuracy.
We used Random Forest Regressor, which is an ensemble learning technique that uses multiple decision trees to improve accuracy.

We then evaluated the model using:

Mean Squared Error (MSE) → Tells how much error is there in the prediction.
R-squared Score (R2) → Tells how accurate the model is.
Finally, we created two graphs:

Actual vs Predicted Graph → Shows how close the predicted credit scores are to the actual scores.
Feature Importance Graph → Shows which factor (Age, Income, Loan Amount) has the most influence on credit score.
✅ Why This Project is Important:
This project is used in banks, financial institutions, and credit card companies to make decisions about loan approval.
It helps reduce financial risk by predicting credit scores accurately.
