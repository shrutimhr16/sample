# Project Name
Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Team](#team)

## General Information
### Problem Statement
Lending Club is a consumer finance marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.

It specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.

In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

The core objective of the excercise is to help the company minimise the credit loss. There are two potential sources of credit loss are:

Applicant likely to repay the loan, such an applicant will bring in profit to the company with interest rates.** Rejecting such applicants will result in loss of business**.
Applicant not likely to repay the loan, i.e. and will potentially default, then approving the loan may lead to a financial loss* for the company

### Objectives
The goal is to *identify these risky loan applicants*, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA using the given [dataset](./data/loan.csv), is the aim of this case study.

If one is able to *identify these risky loan applicants*, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, **the company wants to understand the driving factors (or driver variables)** behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

### Data Set

> The data set is a csv file with the loan data for the Lending Club.

<!-- You can include any other section that is pertinent to your problem -->


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Major Driving factor which can be used to predict the chance of defaulting and avoiding credit loss:
interest_rate
annual_income
Debt to income ratio (DTI)
Grade
Verification Status
Loan amount
Pub_rec_bankruptcies
Home ownership
Purpose
Emp Length

From exploratory data analysis we can conclude that, there is more probability of defaulting when:
1. Borrowers who are taking loan for the ‘60 months’ tenure.
2. Borrowers having Public Recorded Bankruptcy.
3. Borrowers whose loan status is ‘Verified’ and they take high amount of loan with 60 months tenure.
4. Borrowers who are having home ownership as ‘Rent’.
5. Borrowers whose annual income is low i.e. (0-20000).
6. Borrowers who takes loan amount in the range 0 to 14000.
7. Borrowers who receive interest at the rate of 15-20%.
8. Borrower who takes loan for the purpose of small business or debt consolidation.
9. Borrower with least grades and sub_grades like E,F,G which indicates high risk.
10. Borrower with very high Debt to Income value.
11. Borrower with working experience 10+ years.
12. Borrowers who does not belong to large urban cities like CA, NY etc.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python - version 3.7.6
NumPy - version 1.18.1
Pandas - version 1.2.3
Matplotlib - version 3.1.3
Seaborn - version 0.10.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by @shrutimhr16 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->