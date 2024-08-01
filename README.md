# Loan-Approval-Prediction-using-Machine-Learning

### Objective
The goal of this project is to develop a machine learning model to predict whether a loan application will be approved or not. The model will help financial institutions to automate the loan approval process and make data-driven decisions.

### Problem Statement
Loan approval is a critical process for financial institutions, and it involves evaluating various factors to determine the likelihood of an applicant repaying the loan. The objective is to build a predictive model using historical data that can accurately predict the approval status of a loan application based on applicant information.

### Process
1. Data Import and Exploration:
Load the dataset using Pandas and explore the initial structure using df.head() and df.info().
Identify missing values and data types of each column.
2. Data Preprocessing:
   1.Handling Missing Values: Impute missing values using mode, mean, or appropriate methods for categorical and numerical features.

   2.Feature Engineering: Log transform the LoanAmount and TotalIncome columns to normalize their distributions.
                          Create a new feature TotalIncome by summing ApplicantIncome and CoapplicantIncome.

   3.Encoding Categorical Variables: Convert categorical variables into numerical values using LabelEncoder.
4. Data Visualization:
Use Seaborn to create count plots for categorical features such as Gender, Married, Dependents, Self_Employed, Credit_History, and Property_Area.
Plot histograms of transformed features like LoanAmount_log and TotalIncome_log.
5. Model Training: Split the dataset into training and testing sets using train_test_split.
Apply LabelEncoder to encode target labels and categorical features in the training data.
6. Model Evaluation:
Evaluate the model’s performance on the test set using appropriate metrics such as accuracy, precision, recall, and F1 score.
Compare the results and choose the best-performing model.
7. Conclusion:
Summarize the results of the analysis and model performance.
Highlight the key factors influencing loan approval.
Discuss the best model identified during the evaluation process.
### Conclusion
The Loan Approval Prediction project successfully implemented a machine learning model that can predict loan approval with reasonable accuracy. The model leverages features such as applicant income, loan amount, and credit history to make informed predictions. Among the models evaluated, the Support Vector Machine (SVM) demonstrated the highest accuracy, making it a suitable choice for automating loan approval decisions.

