# Lending Club Loans Data Exploration
## Loan Statuses Demographic Analysis

![Lending_Club_Loans_Analysis](https://user-images.githubusercontent.com/19572673/57266477-155fc700-704a-11e9-88f3-afe81df3606c.PNG)

## Use Case:
### Figuring out specific causes of loan defaults by specific factors to make better long term decisions
## Initial Dataset:
### Loan Dataset
## Software:
### PowerBI
## Basic Steps:
#### Downloaded the dataset. 
#### Categorical slicers include State, Zip, ID, Term, Grade, Sub-Grade, Employer, Employer Length, Home Ownership, Verification Status, Loan Status, Loan Purpose. Numerical slicer includes the 'date range' (where you can slide accordingly)
##### State: 
##### Zip: 
##### ID:
##### Term: 
##### Grade:
##### Sub-Grade:
##### Employer:
##### Employer Length:
##### Home Ownership:
##### Verification Status:
##### Loan Status:
##### Loan Purpose:
##### Date Range:
![Lending_Club_Loans_Analysis_Slicers](https://user-images.githubusercontent.com/19572673/57423158-d4e68180-71e0-11e9-9f81-4caaeed99774.PNG)
#### Tabular reports include by State, Zip, Loan Grade, Loan Sub-Grade Metrics, Employer Length, Home Ownership, Loan Purpose, Loan Status, and by specific ID. 
##### State Metrics
##### Zip Metrics
##### Loan Grade Metrics:
##### Loan Sub-Grade Metrics
##### Employer Length Metrics:
##### Home Ownership Metrics:

![Lending_Club_Loans_Analysis_Reports](https://user-images.githubusercontent.com/19572673/57493298-52b69580-7292-11e9-9f7a-377d8807c6a4.PNG)
#### Calculated measures (KPIs):
##### _Average_Income = sum(LoanData[annual_inc])/count(LoanData[id])
##### _Average_Int_Rate = sum(LoanData[int_rate])/count(LoanData[id])
##### _Average_Loan_Amount = sum(LoanData[loan_amnt])/count(LoanData[id])
##### _Average_DTI_Amount = sum(LoanData[dti])/count(LoanData[id])
![Lending_Club_Loans_Analysis_KPIs](https://user-images.githubusercontent.com/19572673/57493380-9f01d580-7292-11e9-89d4-d564fc659fca.PNG)
