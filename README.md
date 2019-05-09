# Lending_Club_Loans_Data
## Loan Statuses Demographic Analysis

## Use Case:
### Figuring out specific causes of loan defaults by specific factors to make better long term decisions
## Initial Dataset:
### Loan Dataset
## Software:
### PowerBI
## Basic Steps:
#### Downloaded the dataset. 
#### Slicers include State, Zip, ID, Term, Grade, Sub-Grade, Employer, Employer Length, Home Ownership, Verification Status, Loan Status, and Loan Purpose.
#### Tabular reports include by State, Zip, Loan Grade, Loan Sub-Grade Metrics, Employer Length, Home Ownership, Loan Purpose, Loan Status, and by specific ID. 
#### Calculated measures (KPIs):
##### _Average_Income = sum(LoanData[annual_inc])/count(LoanData[id])
##### _Average_Int_Rate = sum(LoanData[int_rate])/count(LoanData[id])
##### _Average_Loan_Amount = sum(LoanData[loan_amnt])/count(LoanData[id])
##### _Average_DTI_Amount = sum(LoanData[dti])/count(LoanData[id])

![Lending_Club_Loans_Analysis](https://user-images.githubusercontent.com/19572673/57266477-155fc700-704a-11e9-88f3-afe81df3606c.PNG)
