# (Loan Data from Prosper Analysis)
## by (Emmanuel Eshun)


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, Occupation, StatedMonthlyIncome, IsBorrowerHomeowner, EmploymentStatusDuration, EmploymentStatus and many others. 


## Summary of Findings

The objective of this work is to investigate factors affecting borrower APR:

In the exploratory analysis, I found out that most of our dataset was coming from the year 2013 and the least data was also from 2005. Upon estimating the distribution of our BorrowerRate and BorrowerAPR it was found out that it was a normal distribution and a multimodal distribution respectively. In analysing the distribution of stated monthly income, it was noticed that it was skweed to the right with most of the stated income less than 30K. Most of the loan status was current followed by being completed and lastly was cancelled which turned out to be the lowest. Analysing the top 20 Borrower's state, most of these listings was from the CA, TX, NY, FL and IL, we had the least from IA, WY, ME, ND. Doing same for the various Occupations, marjority of the applicants selected "other" for Occupations which tend to lead in the dataset followed by Professional which is the second highest. I also observed Visually that number of borrower's in the 50K-74K range are somwehat closer to the 25K-49K range, same applies to 100K-&5K and the 1-24K and 0. 

Moving on to the Bivariates Exploration, There's was a negative correlation between the borrowerAPR and MonthlyLoanPayment, StatedMonthlyincome, whereas a positive one between the statedMonthlyincome and the monthly loan Payment. Box Plot for BorrowerAPR vs. Employment status and BorrowerAPR vs is Borrower Home Owner, first plot shows an indication that the employment status is a good determining factor of borrower's APR. People without employment tend to have the highest APR as compared to Part-time employees, and also the second observation shows that borrorwer's who are Home owners have lower APR compared those who are not.

For the multivariate exploration, I explored the replationship between Estimated EffectiveYield , Estimated Return and Estimated Loss and to my surprise there's a strong positive relationship between them in the first plot.
Again, Exploration of the BorrorwerAPR, Borrower Rate and Lender Yield also showned a strong positive relationship too.


## Key Insights for Presentation

For the presentation, I focused on the distribution of the BorrorweAPR then also the Loan status for the data set.

Then furthur explained the correlations of the variable of interest and analysed the relationship BorrowerRate and LenderYield have on the BorrorwerAPR.