# Lending Club Loan Default Rate Modeling
### Pujan Malavia

![Lending_Club_logo](https://user-images.githubusercontent.com/19572673/62312068-3f633280-b45b-11e9-98b8-91894e557d60.png)

### Abstract:

Year after year, there are millions of people who default on their loans which causes high risk to the lending partner. Many wonder, what makes a customer default on a loan? Is it their income, debt to income ratio, or it something more behaviorial that causes this trend? In this project, we will explore potential indicator variables that play a large role in terms of customers defaulting on their loans. 

### Industry:
Financial Services/Internet

## Company Information:
LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform. The company claims that $15.98 billion in loans had been originated through its platform up to December 31, 2015.

LendingClub enables borrowers to create unsecured personal loans between $1,000 and $40,000. The standard loan period is three years. Investors can search and browse the loan listings on LendingClub website and select loans that they want to invest in based on the information supplied about the borrower, amount of loan, loan grade, and loan purpose. Investors make money from interest. LendingClub makes money by charging borrowers an origination fee and investors a service fee.

LendingClub also makes traditional direct to consumer loans, including automobile refinance transactions, through WebBank, an FDIC-insured, state-chartered industrial bank that is headquartered in Salt Lake City Utah. The loans are not funded by investors but are assigned to other financial institutions.

The company raised $1 billion in what became the largest technology IPO of 2014 in the United States. Though viewed as a pioneer in the fintech industry and one of the largest such firms, LendingClub experienced problems in early 2016, with difficulties in attracting investors, a scandal over some of the firm's loans and concerns by the board over CEO Renaud Laplanche's disclosures leading to a large drop in its share price and Laplanche's resignation.

https://www.lendingclub.com/

https://en.wikipedia.org/wiki/LendingClub

### Use Case:
Figuring out specific causes of loan defaults by specific factors to make better long term decisions

### Initial Dataset:
Loan Dataset

### Software:
PowerBI

![Lending_Club_Loans_Analysis](https://user-images.githubusercontent.com/19572673/57266477-155fc700-704a-11e9-88f3-afe81df3606c.PNG)

### Basic Steps:

Downloaded the dataset. 

Categorical slicers include State, Zip, ID, Term, Grade, Sub-Grade, Employer, Employer Length, Home Ownership, Verification Status, Loan Status, Loan Purpose. Numerical slicer includes the 'date range' (where you can slide accordingly)

State: All States displayed

Zip: Only first 3 digits of Zip displayed use to confidentiality purposes

ID: Unique ID assigned to each transaction

Term: 

Grade:

Sub-Grade:

![Lending_Club_loanssubgrades](https://user-images.githubusercontent.com/19572673/60403202-3cc5a280-9b68-11e9-9416-26eb85565789.PNG)

Employer: Unique Name of Employer

Employer Length:

Home Ownership:

Verification Status:

Loan Status:

Loan Purpose:

Date Range:

![Lending_Club_Loans_Analysis_Slicers](https://user-images.githubusercontent.com/19572673/57423158-d4e68180-71e0-11e9-9f81-4caaeed99774.PNG)

Tabular reports include by State, Zip, Loan Grade, Loan Sub-Grade Metrics, Employer Length, Home Ownership, Loan Purpose, Loan Status, and by specific ID. 

State Metrics:

Zip Metrics:

Loan Grade Metrics:

Loan Sub-Grade Metrics:

Employer Length Metrics:

Home Ownership Metrics:

![Lending_Club_Loans_Analysis_Reports](https://user-images.githubusercontent.com/19572673/57493298-52b69580-7292-11e9-9f7a-377d8807c6a4.PNG)

Calculated measures (KPIs):

Average Income = sum(LoanData[annual_inc])/count(LoanData[id])

![Lending_Club_Loans_Analysis_Income_KPI](https://user-images.githubusercontent.com/19572673/57495391-e80a5780-729b-11e9-8950-bbe980a85caa.PNG)

Average Int Rate = sum(LoanData[int_rate])/count(LoanData[id])

![Lending_Club_Loans_Analysis_IR_KPI](https://user-images.githubusercontent.com/19572673/57495392-e80a5780-729b-11e9-8faa-6d9f3846a57a.PNG)

Average Loan Amount = sum(LoanData[loan_amnt])/count(LoanData[id])

![Lending_Club_Loans_Analysis_LA_KPI](https://user-images.githubusercontent.com/19572673/57495393-e80a5780-729b-11e9-8843-381847bd0adf.PNG)

Average DTI Amount = sum(LoanData[dti])/count(LoanData[id])

![Lending_Club_Loans_Analysis_DTI_KPI](https://user-images.githubusercontent.com/19572673/57495390-e80a5780-729b-11e9-849d-0b7c20444de8.PNG)

Loan Status Distribution

![Lending_Club_Loans_Analysis_Loan_Status](https://user-images.githubusercontent.com/19572673/57498385-ada7b700-72a9-11e9-8edd-2769be9153d1.PNG)

Loan Grade Distribution

![Lending_CLub_Loans_Analysis_Loan_Grade](https://user-images.githubusercontent.com/19572673/57498384-ada7b700-72a9-11e9-8188-53db4fefd16e.PNG)

Employer Length Distribution

![Lending_Club_Loans_Analysis_EL](https://user-images.githubusercontent.com/19572673/57498383-ada7b700-72a9-11e9-9c19-5ce61d21168d.PNG)

Home Ownership Distribution

![Lending_Club_Home_Ownership](https://user-images.githubusercontent.com/19572673/57498382-ada7b700-72a9-11e9-957f-6f2523d9f6c1.PNG)

Loan Purpose

![Lending_Club_Loan_Purpose](https://user-images.githubusercontent.com/19572673/60401056-14c74680-9b4a-11e9-9298-f67a17c114ba.PNG)

Word Cloud

![Lending_Club_Monthly_Trend](https://user-images.githubusercontent.com/19572673/60401067-3e806d80-9b4a-11e9-8927-4ce829cac2b8.PNG)

Monthly Trend

![Lending_Club_WordCloud](https://user-images.githubusercontent.com/19572673/60401068-3e806d80-9b4a-11e9-8cae-e2063cb9aa2e.PNG)

### Communication of Results to Business Partner:
To a business partner, I would explain that the SGD Logistic Regression (all else equal) is an efficient and easy to use algorithm which delivers high performance and accuracy as compared to other algorithms.

### Future Work:
Continue to do hyperparameter tuning of the model and creating new features/removing old features to help increase the prediction accuracy of the model

Try other types of models to see if the accuracy rate improves

More data visualization/patterns within the dataset (external sources) that can lead to more insights and decision-making from a business perspective
