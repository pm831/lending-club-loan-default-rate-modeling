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
Python (Jupyter Notebook), PowerBI, Tableau

### Techniques:

SGD Logistic Regression

Random Forest 

K nearest neighbors

### Data Curation Process:

Data Preparation/Data Visualization

Python (Jupyter Notebook) Visualization:

Loan Amount 

![output_36_0](https://user-images.githubusercontent.com/19572673/86076193-b46a2e00-ba57-11ea-96b3-4602878865b6.png)

![output_36_1](https://user-images.githubusercontent.com/19572673/86076194-b46a2e00-ba57-11ea-9832-ae3f73075ede.png)

Term

![output_40_0](https://user-images.githubusercontent.com/19572673/86076195-b46a2e00-ba57-11ea-853e-6d71e4dfd3c2.png)

![output_40_1](https://user-images.githubusercontent.com/19572673/86076196-b502c480-ba57-11ea-967d-d5e37c23048f.png)

Interest Rate

![output_44_0](https://user-images.githubusercontent.com/19572673/86076197-b502c480-ba57-11ea-9977-6472aa8a41bc.png)

![output_44_1](https://user-images.githubusercontent.com/19572673/86076198-b502c480-ba57-11ea-8e67-8158d16b6322.png)

Installment

![output_52_0](https://user-images.githubusercontent.com/19572673/86076199-b502c480-ba57-11ea-96e2-51aefc68e6b6.png)

![output_52_1](https://user-images.githubusercontent.com/19572673/86076200-b59b5b00-ba57-11ea-835b-61e7706cbbf5.png)

Sub-Grade

![output_56_0](https://user-images.githubusercontent.com/19572673/86076201-b59b5b00-ba57-11ea-8190-db948985b739.png)

![output_56_1](https://user-images.githubusercontent.com/19572673/86076202-b59b5b00-ba57-11ea-9f3a-19cad37ee99c.png)

Grade

![output_57_0](https://user-images.githubusercontent.com/19572673/86076203-b59b5b00-ba57-11ea-9dda-7821231f6836.png)

![output_57_1](https://user-images.githubusercontent.com/19572673/86076204-b633f180-ba57-11ea-9316-8617f924453f.png)

Employer Length

![output_69_0](https://user-images.githubusercontent.com/19572673/86076205-b633f180-ba57-11ea-898d-e035b23d7020.png)

![output_69_1](https://user-images.githubusercontent.com/19572673/86076206-b633f180-ba57-11ea-8bc4-872b95e10523.png)

Home Ownership

![output_73_0](https://user-images.githubusercontent.com/19572673/86076207-b6cc8800-ba57-11ea-99fa-8d70e7dbfcb3.png)

![output_73_1](https://user-images.githubusercontent.com/19572673/86076208-b6cc8800-ba57-11ea-9f7e-7a9314be3570.png)

Annual Income

![output_78_0](https://user-images.githubusercontent.com/19572673/86076210-b7651e80-ba57-11ea-82d5-cfb5ea3f368a.png)

![output_78_1](https://user-images.githubusercontent.com/19572673/86076211-b7651e80-ba57-11ea-85f4-b6b3a5d8396c.png)

Verification Status

![output_81_0](https://user-images.githubusercontent.com/19572673/86076212-b7651e80-ba57-11ea-9288-5442206f3d7e.png)

![output_81_1](https://user-images.githubusercontent.com/19572673/86076213-b7fdb500-ba57-11ea-9f8d-5e2c500d71fa.png)

Debt to Income

![output_92_1](https://user-images.githubusercontent.com/19572673/86076214-b7fdb500-ba57-11ea-9b9c-0088fd3e7892.png)

Number of Open Credit Lines

![output_97_0](https://user-images.githubusercontent.com/19572673/86076215-b7fdb500-ba57-11ea-90ad-13970c1cbd41.png)

![output_97_1](https://user-images.githubusercontent.com/19572673/86076217-b8964b80-ba57-11ea-9768-7b59196a0d1d.png)

Length of the earliest Credit Line (Months to today)

![output_104_0](https://user-images.githubusercontent.com/19572673/86076218-b8964b80-ba57-11ea-8a5b-43e22b5abd74.png)

![output_104_1](https://user-images.githubusercontent.com/19572673/86076219-b8964b80-ba57-11ea-89cd-a85fc800d80a.png)

FICO

![output_109_0](https://user-images.githubusercontent.com/19572673/86076220-b92ee200-ba57-11ea-9765-93e3ca32cd5e.png)

![output_109_1](https://user-images.githubusercontent.com/19572673/86076222-b92ee200-ba57-11ea-8141-19a343876c1f.png)


![output_110_0](https://user-images.githubusercontent.com/19572673/86076223-b92ee200-ba57-11ea-9496-a789657d7c31.png)



![output_116_1](https://user-images.githubusercontent.com/19572673/86076224-b92ee200-ba57-11ea-9d1a-126ff4756e57.png)



![output_117_1](https://user-images.githubusercontent.com/19572673/86076226-b9c77880-ba57-11ea-81f9-e4337ee6c1d0.png)



![output_119_1](https://user-images.githubusercontent.com/19572673/86076227-b9c77880-ba57-11ea-99b0-3e481ff94bb7.png)



![output_123_0](https://user-images.githubusercontent.com/19572673/86076228-ba600f00-ba57-11ea-9fbd-1b045596a60f.png)

![output_123_1](https://user-images.githubusercontent.com/19572673/86076229-ba600f00-ba57-11ea-8ff7-790d7cfabb9d.png)



![output_127_0](https://user-images.githubusercontent.com/19572673/86076230-ba600f00-ba57-11ea-82f5-0774bb218caa.png)

![output_127_1](https://user-images.githubusercontent.com/19572673/86076231-ba600f00-ba57-11ea-8fb1-18f11bff1dab.png)



![output_129_0](https://user-images.githubusercontent.com/19572673/86076232-baf8a580-ba57-11ea-8065-ba37a662e6f6.png)

![output_129_1](https://user-images.githubusercontent.com/19572673/86076233-baf8a580-ba57-11ea-8a22-8dbeb1d236fa.png)



![output_133_0](https://user-images.githubusercontent.com/19572673/86076234-baf8a580-ba57-11ea-856a-0320d95aaafa.png)

![output_133_1](https://user-images.githubusercontent.com/19572673/86076236-baf8a580-ba57-11ea-809e-fcfe4fa5588f.png)



![output_135_0](https://user-images.githubusercontent.com/19572673/86076237-baf8a580-ba57-11ea-8d90-1f82e6747b01.png)

![output_135_1](https://user-images.githubusercontent.com/19572673/86076238-bb913c00-ba57-11ea-9578-bc2755bee33c.png)



![output_138_0](https://user-images.githubusercontent.com/19572673/86076239-bb913c00-ba57-11ea-871e-6163a64b25c1.png)

![output_138_1](https://user-images.githubusercontent.com/19572673/86076241-bb913c00-ba57-11ea-816c-2ef8f26f100d.png)



![output_140_0](https://user-images.githubusercontent.com/19572673/86076242-bb913c00-ba57-11ea-84a7-f95f9ee37e19.png)

![output_140_1](https://user-images.githubusercontent.com/19572673/86076243-bc29d280-ba57-11ea-90ab-0b19a7148013.png)



![output_144_0](https://user-images.githubusercontent.com/19572673/86076244-bc29d280-ba57-11ea-9d63-0ebff7ebd1c6.png)

![output_144_1](https://user-images.githubusercontent.com/19572673/86076245-bc29d280-ba57-11ea-8c48-39f4360fab15.png)



![output_146_0](https://user-images.githubusercontent.com/19572673/86076246-bcc26900-ba57-11ea-8069-99ee0f652d92.png)

![output_146_1](https://user-images.githubusercontent.com/19572673/86076248-bcc26900-ba57-11ea-9e78-0e7dd16baa70.png)



![output_148_0](https://user-images.githubusercontent.com/19572673/86076249-bd5aff80-ba57-11ea-86dc-224487caf563.png)

![output_148_1](https://user-images.githubusercontent.com/19572673/86076250-bd5aff80-ba57-11ea-95ef-ccfda29b3d44.png)



![output_150_0](https://user-images.githubusercontent.com/19572673/86076251-bd5aff80-ba57-11ea-9076-2d4aea15e29a.png)

![output_150_1](https://user-images.githubusercontent.com/19572673/86076253-bd5aff80-ba57-11ea-847f-d75bb932aceb.png)



![output_152_0](https://user-images.githubusercontent.com/19572673/86076254-bd5aff80-ba57-11ea-8cd5-56e5f83be394.png)

![output_152_1](https://user-images.githubusercontent.com/19572673/86076255-bdf39600-ba57-11ea-92e3-39598a07525f.png)



![output_162_0](https://user-images.githubusercontent.com/19572673/86076256-bdf39600-ba57-11ea-80b5-cacf57d95528.png)



![output_184_1](https://user-images.githubusercontent.com/19572673/86076257-bdf39600-ba57-11ea-8ca5-3a4c2984938d.png)



![output_201_0](https://user-images.githubusercontent.com/19572673/86076259-be8c2c80-ba57-11ea-8d12-31a5cee8bec3.png)



![output_234_0](https://user-images.githubusercontent.com/19572673/86076260-be8c2c80-ba57-11ea-8e5c-6ee06774663a.png)




![output_249_1](https://user-images.githubusercontent.com/19572673/86076262-be8c2c80-ba57-11ea-8287-de3426980d3b.png)



![output_251_1](https://user-images.githubusercontent.com/19572673/86076263-bf24c300-ba57-11ea-9b1b-ae7f12a06963.png)

![output_252_1](https://user-images.githubusercontent.com/19572673/86076264-bf24c300-ba57-11ea-94e3-f5da5f1265c0.png)



![output_253_1](https://user-images.githubusercontent.com/19572673/86076266-bf24c300-ba57-11ea-8600-48f0b775cd36.png)



PowerBI Data Visualization (subsample of data):

![Lending_Club_Loans_Analysis](https://user-images.githubusercontent.com/19572673/57266477-155fc700-704a-11e9-88f3-afe81df3606c.PNG)

Downloaded the dataset. 

Categorical slicers include State, Zip, ID, Term, Grade, Sub-Grade, Employer, Employer Length, Home Ownership, Verification Status, Loan Status, Loan Purpose. Numerical slicer includes the 'date range' (where you can slide accordingly)

![Lending_Club_Loans_Analysis_Slicers](https://user-images.githubusercontent.com/19572673/57423158-d4e68180-71e0-11e9-9f81-4caaeed99774.PNG)

Tabular reports include by State, Zip, Loan Grade, Loan Sub-Grade Metrics, Employer Length, Home Ownership, Loan Purpose, Loan Status, and by specific ID. 

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
