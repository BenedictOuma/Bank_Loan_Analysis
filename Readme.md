# Bank Loan Analysis Project

This project aimed to analyze bank loan application data using Power BI to uncover key factors that influence whether a loan is approved or denied. Through interactive dashboards and data visualizations, the project provides insights that can assist financial institutions in assessing risk and making informed lending decisions.

---

## Dataset Overview

The dataset includes the following fields:

- Loan ID – Unique identifier for each loan application  
- Customer ID – Unique identifier for each loan applicant  
- Loan Status – Whether the loan application was denied or accepted
- Current Loan Amount – Amount requested in the loan  
- Term – Duration of the loan (Short/Long)  
- Credit Score – Applicant's credit rating  
- Annual Income – Applicant's yearly earnings  
- Years in current job – Duration in current employment  
- Home Ownership – Housing status: Rent, Own, Mortgage  
- Monthly Debt – Ongoing debt expenses  
- Years of Credit History – Length of credit history  
- Number of Open Accounts – Total open lines of credit  
- Number of Credit Problems – Issues with prior credit lines  
- Current Credit Balance – Total credit usage  
- Maximum Open Credit – Highest credit available  
- Bankruptcies – Number of bankruptcies filed  
- Tax Liens – Number of tax liens filed

---

## Project Objectives

The main objectives of this analysis were to:

1. *Determine whether higher credit scores lead to more approvals.*  
2. *Show home ownership affect loan status.*  
3. *Show the connection between bankruptcies or tax liens and loan rejections.*

---

## Methodology

Using Power BI, data was cleaned and visualized through:
- Bar charts and pie charts to show approval ratios across groups
- Filters and slicers to compare categories like home ownership and credit scores
- Conditional formatting to highlight high-risk patterns

---

## Findings & Insights

### 1 Credit Score & Loan Status
- *Higher credit scores* do not guarantee am increase in approval chances.
- Other factors such as *annual income*, *home ownership*, and *employment duration* also play critical roles in loan decisions.

### 2️ Home Ownership & Loan Decisions
- *Home ownership* alone does not guarantee approval.
- *Mortgage holders* form the largest group, but have nearly equal approval and denial rates — possibly due to ongoing debt.
- Those who *own their homes outright* have a *slightly higher approval rate*, likely due to reduced housing expenses.
- *Renters* have the *lowest approval rate*, possibly indicating higher financial risk or fewer assets.

### 3️ Bankruptcy, Tax Liens & Approval Rates
- Applicants with *0 bankruptcies* surprisingly have *more denials* than those with 1.
- Denial rates increase with *additional bankruptcies*, suggesting higher financial instability.
- Those with *0 tax liens* also face *more denials* than those with a single lien.
- Combined analysis shows denial rates generally decrease in this order of bankruptcy-tax lien pairs:  
  0-0, 0-1, 2-0, 1-0, 2-1, 1-1.
