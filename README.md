## credit-risk-classification (Module 20 Challenge)

## Credit risk classification report and Overview of the Analysis:

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* In this challenge, my task involves employing diverse techniques to train and assess a model focused on loan risk. Utilizing a dataset containing historical lending data from a peer-to-peer lending services company, my goal is to develop a model capable of discerning the creditworthiness of borrowers.

* The provided financial data includes details such as the loan amount, interest rate, borrower's income, debt-to-income ratio, the borrower's number of accounts, the count of derogatory remarks on their credit report, and the total debt of the borrower. I am examining this information to forecast the loan status of borrowers, categorized as either 0 or 1. In this context, 0 signifies a favorable loan, while 1 indicates a higher risk of defaulting on the loan.

## Dataset Overview:

* The dataset comprises information on 77,536 loans, with 2,500 categorized as high risk and 75,036 as healthy loans.

## Machine Learning Process:

* Applied steps include data preprocessing, model training, validation, and outcome prediction.

## Model Choice:

* Employed a logistic regression model, a statistical method specifically designed for predicting binary outcomes from the available data.




## Results

* Logistic Regression Model:
    * Accuracy: This model had an accuracy of ~96%
    * Precision: This model predicts healthy loans at a rate of 100% and high-risk loans at a rate of 85%
    * Recall scores: The recall for healthy loans is 99% and for high-risk loans at 91%








## Summary

The logistic regression model exhibits high accuracy and precision, especially for healthy loans. It demonstrates a balanced performance in correctly identifying both healthy and high-risk loans. However, the choice of the best-performing model depends on the specific objectives of the problem. If prioritizing the identification of high-risk loans is crucial, the recall for high-risk loans becomes a vital metric to consider in the evaluation process.