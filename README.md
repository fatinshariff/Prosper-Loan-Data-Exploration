# Prosper Loan Data Exploration

## by Fatin Shariff


## Dataset

This raw data set contains 113,937 loans with 81 variables. For this investigation
I have narrowed this data set to  113058 loans with 13 features after dropping 
duplicates and 8 of inconsistent data.


## Summary of Findings

In the exploration, I found that there was a strong relationship between Prosper 
rating and a few other features like loan status, borrower monthly income, 
borrower APR, and Estimated Loss and Return. The loan status that I was interested
in this data set were charged off and defaulted loan. Completed loan are used as 
refence and also for comparison purposes. In the bivariate exploration part, the 
significant relationship between loan status and prosper rating can be seen. 
As the level of the risk increase from AA to HR, the percentage of the completed loan
decrease while the charged off and defaulted loans increase with charged off 
having higher increase rate than defaulted. 

When plotting mean value of borrower's monthly income against prosper rating, 
a clear relationship is observed with lower-risk borrower associated with high income
and vice versa. 

Besides that, BorrowerAPR, LenderYield, EstimatedLoss and EstimatedReturn all show
a positive relationship with Prosper risk rating as well. All the rates increase as
the listing risk goes up. 



## Key Insights for Presentation

For the presentation,I focus on the 2 main features and 2 predictors. The main
features were prosper rating and loan status while the predictor variables were
the monthly loan income and the debt to income ratio(DIR). I start by introducing
the the distribution of the 4 variables. 

Afterwards, I introduce the bivariate plot of loan status against Prosper Rating.
In this plot I show the proportion of interested loan status which are completed,
charged off and defaulted against risk rating from lowest-risk to highest-risk.
I also show how monthly income correlate with prosper rating by plotting the mean
monthly income.

Finally, I used point plots to show how the loan status and risk rating correlate
with the monthly mean income and the mean DIR.
