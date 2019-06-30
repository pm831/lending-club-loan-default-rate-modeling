# Lending Club Loans Data Exploration
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

##### State: All States displayed
##### Zip: Only first 3 digits of Zip displayed use to confidentiality purposes
##### ID: Unique ID assigned to each transaction
##### Term: 
![Lending_Club_loansterms](https://user-images.githubusercontent.com/19572673/60403203-3cc5a280-9b68-11e9-94b8-878471b4bd05.PNG)
##### Grade:
![Lending_Club_loansgrade](https://user-images.githubusercontent.com/19572673/60403198-3cc5a280-9b68-11e9-850a-23aa8412bcd7.PNG)
##### Sub-Grade:
![Lending_Club_loanssubgrades](https://user-images.githubusercontent.com/19572673/60403202-3cc5a280-9b68-11e9-9416-26eb85565789.PNG)
##### Employer: Unique Name of Employer
##### Employer Length:
![Lending_Club_loansEL](https://user-images.githubusercontent.com/19572673/60403197-3cc5a280-9b68-11e9-9e50-0ee6248fc9ef.PNG)
##### Home Ownership:
![lending_club_loansHO](https://user-images.githubusercontent.com/19572673/60403199-3cc5a280-9b68-11e9-9a7a-53dc6c11df51.PNG)
##### Verification Status:
![lending_club_loansVS](https://user-images.githubusercontent.com/19572673/60403204-3cc5a280-9b68-11e9-8dfd-3ca16760d293.PNG)
##### Loan Status:
![lending_club_loansls](https://user-images.githubusercontent.com/19572673/60403200-3cc5a280-9b68-11e9-863d-3dec2097c545.PNG)
##### Loan Purpose:
![lending_club_loanspurpose](https://user-images.githubusercontent.com/19572673/60403201-3cc5a280-9b68-11e9-8e63-c018555cd65e.PNG)
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
##### Average Income = sum(LoanData[annual_inc])/count(LoanData[id])
![Lending_Club_Loans_Analysis_Income_KPI](https://user-images.githubusercontent.com/19572673/57495391-e80a5780-729b-11e9-8950-bbe980a85caa.PNG)
##### Average Int Rate = sum(LoanData[int_rate])/count(LoanData[id])
![Lending_Club_Loans_Analysis_IR_KPI](https://user-images.githubusercontent.com/19572673/57495392-e80a5780-729b-11e9-8faa-6d9f3846a57a.PNG)
##### Average Loan Amount = sum(LoanData[loan_amnt])/count(LoanData[id])
![Lending_Club_Loans_Analysis_LA_KPI](https://user-images.githubusercontent.com/19572673/57495393-e80a5780-729b-11e9-8843-381847bd0adf.PNG)
##### Average DTI Amount = sum(LoanData[dti])/count(LoanData[id])
![Lending_Club_Loans_Analysis_DTI_KPI](https://user-images.githubusercontent.com/19572673/57495390-e80a5780-729b-11e9-849d-0b7c20444de8.PNG)
##### Loan Status Distribution
![Lending_Club_Loans_Analysis_Loan_Status](https://user-images.githubusercontent.com/19572673/57498385-ada7b700-72a9-11e9-8edd-2769be9153d1.PNG)
##### Loan Grade Distribution
![Lending_CLub_Loans_Analysis_Loan_Grade](https://user-images.githubusercontent.com/19572673/57498384-ada7b700-72a9-11e9-8188-53db4fefd16e.PNG)
##### Employer Length Distribution
![Lending_Club_Loans_Analysis_EL](https://user-images.githubusercontent.com/19572673/57498383-ada7b700-72a9-11e9-9c19-5ce61d21168d.PNG)
##### Home Ownership Distribution
![Lending_Club_Home_Ownership](https://user-images.githubusercontent.com/19572673/57498382-ada7b700-72a9-11e9-957f-6f2523d9f6c1.PNG)
#### Loan Purpose
![Lending_Club_Loan_Purpose](https://user-images.githubusercontent.com/19572673/60401056-14c74680-9b4a-11e9-9298-f67a17c114ba.PNG)
#### Word Cloud
![Lending_Club_Monthly_Trend](https://user-images.githubusercontent.com/19572673/60401067-3e806d80-9b4a-11e9-8927-4ce829cac2b8.PNG)
#### Monthly Trend
![Lending_Club_WordCloud](https://user-images.githubusercontent.com/19572673/60401068-3e806d80-9b4a-11e9-8cae-e2063cb9aa2e.PNG)

