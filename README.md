# Dataset Exploration: prosperLoanData
## by (Andrew Muhoro)

## Project Overview
> This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process.

1. Part I : Exploratory Data Visualization: This part will require using Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables.

2. Part II : Explanatory Data Visualization: In this section, will require producing a short presentation that illustrates interesting properties, trends, and relationships that discovered in the Loan Data from Prosper. The primary method of conveying findings will be through transforming exploratory visualizations from the first part into polished, explanatory visualizations.

## Goal 
Of interest in this phase is to have a look at the basic structure of the loans given. This means having a look at the amounts given, interests and fees, time and the state of the borrowers, etc.

This will mean having a look at features like: CreditGrade, Term, LoanStatus, BorrowerState, EmploymentStatus, LP_InterestandFees,LoanOriginalAmount,LoanOriginationDate, amongst others.

## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. See the data dictionary attached to understand the dataset's variables.

> To note is the fact that the loan grading system that was assigned at the time the listing went live was only applicable for listings pre-2009 period and only populated those listings that were made pre-2009. However, majority of the loans are post-2009 as compared to those in pre-2009 period. This means that majority of the loans have 'No Grade" and I believe this has a huge effect of any analysis on the loans that involves the 'CreditGrade'. This is something to keep in mind.


## Summary of Findings

In the exploration I found that of the loans taken majority of them were below $20,000 while interests and fees charged on loans were mostly $4,000 and below. 2013 had the most loans taken while 2005 had the least, the data captured time periods between 2005 and 2014. Majority of the loans taken had a 36-months terms while the least were in a 12-months terms respectivelly. 

Looking at the borrowers, majority of them were employed while the least were retired. The group with an income range of $25,000 to $49,999 took the most loans while that in the range $50,000 to $74,999 took the least number of loans. Also to note, majority own a home. However statistically speaking, the difference between the two(those who own and those who do not own a home) is neglible by less than 1%. In terms of borrowers' occupations, majority of the borrowers were classified as others while the smallest group was students.

According to the data majority of the loans were current at the time of the data capturing. Also, being employed gave the borrower a higher chance of getting larger loan amounts. Loans that fell in the Credit-Grade groups of HR, E and NC had the lowest montly loan payments. Completed and Current loans had the majority of loans with low risks respectively.

According to the data, being employed and having a verified income gave you a better chance at accessing higher loan amounts. That said, the lower the loan's BorrowerRate and BorrowerAPR, the better the ProsperScore meaning the lower the risk associated with the loan. Also, Completed and Current Loans had the highest low-risk status compared to the other categories which were majority in the 'Past Due..' categories. Loans that were categorized in the CreditGrade groups of HR, E and NC had the lowest montly payments on average while those in A and AA paid more.


## Key Insights for Presentation

> For the presentation, my focus is on the relationships between the loan variables and how they affect each other. I start by looking at how employment status affects the loan amount given to the borrowers by ploting a scatter plot chart of these two variables.

> From here I continue introducing more variables. First I look at how the proper score which is a rating for how risky a loan is, relates with the monthly loan payments and loan status using a scatter plot. I investigate further how still the prosper score relates with the BorrowerAPR and BorrowRate, did this using a scatter plot. Finally using a box plot, I check whether the credit grade for a loan has an effect on the monthly loan payments.