Overview

In this repository you will find analysis of lending data that I ran through a linear regression model to see if it would be useful in predicting weather a potential borrower would be qualified for a loan or not. The data I used to train the model contained information on over 77,500 loans and included the loan size, it's interest rate, the borrower's income, their debt to income ratio, how many accounts they have, how many derogatory marks they have against them, their total debt, and finally if the loan was high-risk or healthy.    

Results

The results of running the data through a linear regression model were as follows:

The model was very good at predicting a healthy loan as it garnered perfect scores for both precision and recall

It was not as good at prediction a high-risk loan with it's precision being 87 and it's recall being 88 (for a f1-score of 88)

Summary

In summary the model preformed very well at predicting weather a borrower would be a good candidate for a loan and, despite a lower f1-score, it is good at predicting if they would be a poor candidate. I would recomend it's use for either purpose.
