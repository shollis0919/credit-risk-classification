# credit-risk-classification

This repository contains a machine learning process done on lending data to assess whether a person would be a loan risk or not. This would allow for a possibly faster determination of whether a person should receive a loan.  The information given was mostly financial like income, debt, number of accounts, and the actual size of the loan given. With this data, we needed to see if that loan would present a risk of not being paid back on time. The signifier for this would be a "0" for a healthy loan or no risk, and a "1" indicates high risk. Logistic Regression was the main method of machine learning in this instance as it provides a better fitting model than just linear regression. 

⬤ Machine Learning Model 1:

● Balanced accuracy score: The score returned was a .95 showing the predictions made are mostly correctly attributed as positive or negative.    
● Precision Score:  The precision score for the first round of predictions was fairly accurate overall. For the healthy-risk loans, it was extremely accurate to the point where each positive prediction was accurate. It was less so for the case for high-risk loans at 85% which is still accurate but not as much as the healthy loan scores.  
● Recall Score: Just like with the Precision scores both recall scores were accurate overall with healthy-risk loans being a bit more accurate than the high-risk loans.

⬤ Machine Learning Model 2:

● Balanced accuracy score: The resampled data yielded similar results to the first round of data showing that the model can continue to be balanced and stable.     
● Precision Score: The precision scores continue to be quite accurate with the new resampled data with scores of 1.00 and 0.84    
● Recall Score: The recall scores continue to be quite high showing the accuracy of the model with the new resampled data.


Overall I would recommend using the logistic regression model with the resampled data as it showed a bit more accuracy for both the healthy and high-risk loans as seen 
in the classification scores. However, I would also recommend using the model strictly for predicting healthy-risk loans rather than both healthy and high-risk loans.
If needed for quick evaluations I would also recommend looking over results for the high-risk loans as it is still possible to give an inaccurate evaluation, though this chance is quite small,
