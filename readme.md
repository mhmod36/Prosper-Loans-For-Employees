# (Prosper Loan Data)
## by (Mahmoud Sallam)


## Dataset

 Prosper was founded in 2005 as the first peer-to-peer lending marketplace in the United States. Since then, Prosper has facilitated more than $18 billion in loans to more than 1,100,000 people.
 
 This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others

I made a subset from the dataset contains the columns  
the borrower’s APR - the loan amount - Term(The length of the loan expressed in months) - MonthlyLoanPayment - ProsperRating -  ListingCategory - BorrowerStat - EmploymentStatus - IsBorrowerHomeowner - DebtToIncomeRatio - StatedMonthlyIncome  
this new dataset was between 2009-07-20 and 2014-03-12   
i decided to work on the employees only as they have the majority of loans and i wanted the invistigation to be consistant.

## Summary of Findings

> -the huge increase of the loans nuber was in the beginning of 2014

>the graph, of the prosper score of risk to the loans after 2009 with 1 being the highest risk, is kind of normal  

>the debt consolidation takes the biggest number of loans (there is increase in taking out a new loan to pay off other liabilities and consumer debts.) maybe many peaple couldnt pay their loans so they take another one.

>65.1% of the loans is for 36 month, 33% of the loans is for 60 month, 1.9% of the loans is for 12 month

>54.3% of the Borrowers is Homeowner, 45.7% of the Borrowers is not Homeowner

>there are some outliers in the Stated Monthly Income, maybe they intered the anual salary as a Monthly Income

>there are many outliers in the DebtToIncomeRatio as it should be between 0 and 1, maybe the forgot to put the decimal point

>there is a positive correlation between BorrowerAPR and DebtToIncomeRatio, with a correlation of 0.1735

>about 75% of the loans for 12 months are for Amount less than 5000  
about 75% of the loans for 36 months are for Amount less than 10000  
about 75% of the loans for 60 months are for Amount less than 15000 with a peak at 15000 as they need more time to pay it back

>california has the biggest number of prosper loans then newyork then texas

>most of the 12 months loans is between 2011 and 2013  
there is an increase of the 60 months loans and 36 months loans from 2012  
there is a group of 12 months loans with BorrowerAPR more than 0.35 between 2010-07 till 2011-01 between 2011-07 till 2012-07 there are   some lines of BorrowerAPR maybe there was a fixed values for BorrowerAPR and except that group BorrowerAPR is less than 0.35

>most of the listing categories have 36 months loans more than 60 months loans then 12 months loans is the least  
as we saw before there is increase in the debt consolidation, home improvement and business

## Key Insights for Presentation

> -the huge increase of the loans nuber was in the beginning of 2014

>the debt consolidation takes the biggest number of loans (there is increase in taking out a new loan to pay off other liabilities and consumer debts.) maybe many peaple couldnt pay their loans so they take another one.

>65.1% of the loans is for 36 month, 33% of the loans is for 60 month, 1.9% of the loans is for 12 month

>54.3% of the Borrowers is Homeowner, 45.7% of the Borrowers is not Homeowner

>there is a positive correlation between BorrowerAPR and DebtToIncomeRatio, with a correlation of 0.1735

>about 75% of the loans for 12 months are for Amount less than 5000  
about 75% of the loans for 36 months are for Amount less than 10000  
about 75% of the loans for 60 months are for Amount less than 15000 with a peak at 15000 as they need more time to pay it back

>california has the biggest number of prosper loans then newyork then texas

>most of the 12 months loans is between 2011 and 2013  
there is an increase of the 60 months loans and 36 months loans from 2012  
there is a group of 12 months loans with BorrowerAPR more than 0.35 between 2010-07 till 2011-01 between 2011-07 till 2012-07 there are   some lines of BorrowerAPR maybe there was a fixed values for BorrowerAPR and except that group BorrowerAPR is less than 0.35

>most of the listing categories have 36 months loans more than 60 months loans then 12 months loans is the least  
as we saw before there is increase in the debt consolidation, home improvement and business
