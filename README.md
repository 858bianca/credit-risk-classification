# credit-risk-classification

## Overview of the Analysis

For this analysis I used supervised learning to help determine if a borrower would be considered a healthy loan(0) or a high risk loan(1). To determine the results a Logistic Regression Model was used to perform this analysis. The analysis was conducted on lending data, specifically focusing on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The objective was to predict the loan status, either as a healthy loan (0) or a high-risk loan (1). 

Before training my model I had to first split the data into Training and Testing Sets. Two labels were created, y which was the loan status and X the remaining columns of the dataset. Once the labels were created the data was than split by using train_test_split. 
Next, I moved on to creating my Logistic Regression Model. The reason for choosing a Logistic Regression Model as a binary classifier for this analysis was because I am trying to classifying loans as healthy OR high-risk and only those two options. Afterwards, I fit the model by using the training data (X_train and y_train). Once the model was fit, a prediction was created using the X_test and fitted model. Lastly, I evaluted my model's performance by doing the folowing: generating a confusion matrix and printing the classification report to view the precision and accuracy of my model. 

## Results

*Accuracy Score

   ** For my overall Logistic Regression Model, I yield a 99% score.

*Precision Score

   **Healthy Loan(0): I yield a score of 100%
   
   **High-Risk Loan(1): I yield a score of 87%

*Recall Score

   **Healthy Loan(0): I yield a score of 100%
   
   **High-Risk Loan(1): I yield a score of 95%

* Machine Learning Model 1:
* 
    * Overall I belive my model yield good results due to its high scores in accuracy, precision, and recall. 

## Summary

Overall my model is doing an excellent job predicting healthy loans, with a high precision and recall score of 100%. With high risk loans, my model is still doing a good job with a precision score of 87% and a recall score of 95%. Due to the score influctuation between health and high risk loans could be because of the imbalance in dataset. With healthy loans I had 18759 datasets to work with compared to 625 datasets for the high risk loans. If more datasets were present or added for high risk loans, I beleive the precision and recall scores would increase, because there would be more data for the model to learn from. In my perspective it is more important to evaluate the high risk borrowers when giving out loans because the finance company could lose a substantial amount of money than a borrower with good standing status. Overall the model had a accuracy score of 99%. 

