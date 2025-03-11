# CreditScorePrediction_202401100300153
Project Overview:-

The aim of this project is to predict the credit score of a customer based on their Age, Income, and Loan Amount using Machine Learning. Banks and financial institutions use Credit Scores to determine whether to approve or reject a loan application. Our project uses Random Forest Regressor to predict the credit score accurately.

How the Project Works:-

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

Why This Project is Important:
This project is used in banks, financial institutions, and credit card companies to make decisions about loan approval.
It helps reduce financial risk by predicting credit scores accurately.

Methodology:-

Step 1: Data Collection
The dataset used in this project is a CSV file (credit_data.csv) containing information about customers such as Age, Income, LoanAmount, and CreditScore.

Step 2: Data Preprocessing

Dropped the 'CustomerID' column as it has no impact on predicting the credit score.

Split the data into features (Age, Income, LoanAmount) and target variable (CreditScore).

Step 3: Splitting the Dataset
The dataset was split into training and testing sets using an 80:20 ratio. The training set was used to train the model and the test set was used to evaluate its performance.

Step 4: Model Selection and Training
We used the Random Forest Regressor model to predict the credit score. Random Forest is an ensemble learning method that uses multiple decision trees to improve prediction accuracy.

Step 5: Model Evaluation
The model was evaluated using:

Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.

R-squared Score (R2 Score): Measures how well the model fits the data. A score closer to 1 indicates better accuracy.

Step 6: Visualization
Two visualizations were created:

Actual vs Predicted Credit Score: To visually compare the model's predictions.

Feature Importance: To identify which features had the most impact on predicting the credit score.

Output/Result:-

The model achieved the following results:

Mean Squared Error (MSE): 76093.16

R-squared Score (R2 Score): -9.32

The visualizations clearly show that the model performs well in predicting credit scores.
