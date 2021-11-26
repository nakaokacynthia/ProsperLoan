# (Prosper Loan Data Exploration)
## by (Cynthia Nakaoka)


## Dataset

> This [data set](https://docs.google.com/document/d/e/2PACX-1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub) contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
>The data dictionary that explains the variables in the data set you can find [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

This data analysis is divided into:
- Univariate Exploration
- Bivariate Exploration
- Multivariate Exploration




## Summary of Findings

> This data exploration was focused on analyzing the indicators that could increase a borrower's chances of getting a loan. Another point in focus was the other side of who lends the money, in this case, check which borrower features are best for predicting the highest rate of return.
A new Actual Returns column was created following the Actual Returns formula provided on Prosper's own website to help with better insights.

>To organize the data in some analyses, the data were categorized by:
- Numerical features: Borrower APR, Debt To Income Ratio, Monthly Loan Payment, Actual Returns, Estimated Loss, Current Credit Lines, Estimated Return, Total Inquiries, Bankcard Utilization, Percent Funded and Recommendations.
- Categorical features: Prosper Score, Income Range,Is Borrower Homeowner, Credit Grade, Employment Status and Income Range.

At the end of the exploratory and visualization analysis, the following data were found:

> The best features to predict the highest rate of return are:
>- Have a rating score below 8
>- Income range below 25,000
>- Being unemployed, without income or earning up to 25,000
>- Have a Prosper Rating less than B

> The best features to increase the chance of getting a loan are:
>- Monthly income above 3,000 dollars
>- Original amount over 4,000
>- Have a low debt to income ratio
>- Be employed or work Full-time


## Key Insights for Presentation

For this presentation I focused on the main return factors on the loan and borrower's features that could increase the chances of getting a loan.
I started with the main return factors on the loan:
- Actual Return distribution, item of greatest interest to understand its distribution.
- Actual Return by Income Range and Term
- Actual Return by Prosper Rating and Term
- Estimated Returns by Prosper Score and Income Range

Then i finished showing the borrower's features that could increase the chances of getting a loan:
- Loan Original Amount by Prosper Rating and term
- Monthly Income by Prosper Rating and Term
- Employment Status by Prosper rating
- Debt To Income Ratio








