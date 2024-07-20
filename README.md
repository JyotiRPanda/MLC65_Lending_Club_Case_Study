# MLC65_Lending_Club_Case_Study
MLC65 IIT Bangalore Lending Club Group EDA Case Study
# Assignment : Lending Club Case Study

Author : Jyoti Panda

Date : 20 July 2024

**Business Problem and Objectives**
_**1 What is the Lending Club?:**_

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

**_2 What is the business problem?_**

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.


When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company>

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the compy
The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest ra
tof default.

LendingClub faces a significant business challenge related to managing default risks effectively while optimizing returns for its investors. The platform facilitates peer-to-peer lending, connecting borrowers with investors, and relies on accurate risk assessments to maintain a sustainable and profitable lending ecosystem. Thus, the CEO wants us to provide insights about which factors are associated with credit risk in Lending Club's operations, and to construct models capable of predicting the probability of default for new applicants and possible losses on its loans in order to establish a credit policy, deciding when to grant a loan or not for an applicant. An important observation is that the CEO wants these models to be easy to understand. Since our company works on the internet, making customers happy and being clear is really important. So, we need to be able to explain why we decide to approve or deny a loan.

_**3 Which are the project objectives and benefits?**_

Identify the factors associated with credit risk in the form of business insights. The company wants to understand the driving factors (or driver variables) behind loan default (loan_status = 'Charged Off'), i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

To be able to identify risky loan applicants, so that such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

We want to showcase the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.


_**4 Which are the important concepts to know in the context of credit risk?**_

Financial institutions, like LendingClub and online lending platforms, make money by lending to people and businesses. When they lend money, they charge interest, which is a significant source of their profits. Managing credit risk well is crucial for these institutions. This means ensuring that borrowers pay back their loans on time to avoid losses.
Credit risk is the possibility that a borrower might not fulfill their financial obligations, leading to a loss for the lender. If a borrower fails to meet the agreed-upon terms, it's called a "default," and it can result in financial losses for the lender. The default definition is associated with a time horizon. For example, if a borrower hasn't paid their debt within 90 days of the due date, they are considered in default.
The "expected loss (EL)" is the average estimated loss that a lender can expect from loans that default. It involves three factors: the probability of default (likelihood of a borrower defaulting), loss given default (portion of the amount the bank is exposed to that can't be recovered in case of default), and exposure at default (potential loss at the time of default, considering the outstanding loan amount and other factors).

_**3. Solution Pipeline**_
The solution pipeline is based on the crisp-dm framework:

Business understanding.
Data understanding.
Data preparation.
EDA - Univariate Analysis
EDA - Bivariate Analysis

_**4. Technologies and Toools Used**_
   
Python (Pandas, Numpy, Matplotlib, Seaborn, Sciki-Learn).
Statistics.
Data cleaning, manipulation, visualization and exploration.

_**5. Project Structure**_
Input: Contains the raw input data and data dictionary.
Notebooks: Contains all jupyter notebooks developed. It is the research environment
Reports: Contains images for storytelling.

6. Credit Risk Insights
Lending Club's current investment portfolio presents the following characteristics:

_**6.1 Personal Indicators:**_

Approximately 12% are defaulters/bad borrowers.
Nearly three out of four loans have a 36-month term.
More than 75% have at least 2 years of professional experience, with over 30% having ten years or more.
Over 90% own a house through a mortgage or pay rent, while only 8.5% own their houses outright.
Nearly 90% have grades ranging from A to D, while grades F and G make up less than 4% of the borrowers.
The reason for taking out 80% of the loans is to either consolidate debt or use them for credit card payments.

Everything pointed out above suggests a conservative profile among applicants: older individuals with financial and professional stability.

**Impact Factors / drivers for loan Default:** 
_Minor Impact_
.Higher loan amount (above 16K)
•Higher installment amount (above 327)
•Lower annual income (below 37K)
•Higher debt to income ratio (above 15%)
•Applicant’s address state (NV, SD, AK, FL, etc.)
•Loan issue month (May, Sep)

_Heavy impact_
•Higher interest rate (above 13%)
•Higher revolving line utilization rate (above 58%)
•Repayment term (5 years)
•Loan grade & sub-grade (D to G)
•Missing employment record
•Loan purpose (small business, renewable energy, educational)
•Derogatory public records (1 or 2)
•Public bankruptcy records (1 or 2)

_Combined impact_
•High loan amount & interest rate for lower income group
•High installment and longer repayment term
•Home ownership (other) and loan purpose (car, moving or small business)
•Residential state and loan purpose
•Income group and loan purpose

Contact me
Linkedin: https://www.linkedin.com/in/jyoti-panda-5005b66a
Github: https://github.com/JyotiRPanda
Gmail: pandajyotir@gmail.com
