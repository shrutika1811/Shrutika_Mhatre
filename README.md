# Project Name
> You work for a consumer finance company which specialises in lending various types of loans to urban customers.
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
The data given contains information about past loan applicants and whether they ‘defaulted’ or not. 
The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.



## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#contact)

## General Information
- Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters’.
The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.

- dataset that is being used - loan.csv

## Conclusions
- Most loans are requested for amounts ranging between 0 to 5000.
- Most loans funded also fall within the range of 0 to 5000. 
- Borrowers typically prefer a loan term of 2 years over 5 years.
- Majority of loan applicants are living on rent
- Most of the applicants have annual income in the range 40k to 80k
- Significantly large amount of loan applicants are not verified
- 2011 has proved to be the year in which most loans are taken
- Of the given data most of the applicants have successfully Fully Paid Off the loan
- Debt consolidation is the primary reason for borrowing, indicating many are using loans to pay off existing debts.
- CA was the state with the maximum number of loan applicants
- Applicants with debt to income ratio between 12% to 15% are mostly taking the loan

- The higher the loan amount, the higher the chances of being charged off.
- The majority of borrowers have fully repaid their loans. These borrowers preferred the loan term of 2 years.
- People who have higher interest rates are at higher risk of being charged off .
- The applicants with home ownership as “OTHER” are at a higher risk of being charged off. 
- Applicants with over 10 years of employment are more likely to get charged off.
- Applicants with income source verified are less likely to get charged off
- Applicants with grade B are at higher risk of being charged off, next in line being grade C and grade D. 
- The proportion of Charged Off Applicants peaked in the year 2007
- Applicants seeking loans for small businesses are at higher risk of being charged off
- NE State records the highest proportion of charged-off applicants whereas states IL, IN, and ME have seen no charged-off applicants from 2007 to 2011.
- People with high DTI are more prone to charge-offs’.



## Technologies Used
- numpy 
- pandas 
- matplotlib.pyplot 
- seaborn(0.13.0)


## Contact
Created by [@shrutika1811] - feel free to contact me!
mail - mhatreshrutika5@gmail.com
