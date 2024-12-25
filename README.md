# Lending Club Case Study
> This study aims to analyze how real-world business problems are addressed through Exploratory Data Analysis (EDA). Additionally, it provides insights into risk analytics within the banking and financial services sector, highlighting how data is utilized to mitigate the risk of financial loss during customer lending.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Project Information
- We are collaborating with a consumer finance company that specializes in providing various types of loans to urban customers. When a loan application is received, the company must decide whether to approve the loan based on the applicant's profile. This decision involves two primary risks:

#### Loss of Business: 
- If the applicant is likely to repay the loan but the loan is not approved, it results in a missed business opportunity.
#### Financial Loss: 
- If the applicant is likely to default on the loan, approving it may lead to a financial loss for the company.
### Project Background
- Lending Club, the largest online loan marketplace, facilitates personal loans, business loans, and financing for medical procedures. Its fast online platform allows borrowers to access loans at lower interest rates conveniently.
### Business Problem
- Lending loans to 'risky' applicants is a significant source of financial loss, commonly referred to as credit loss. In this scenario, customers labeled as "charged-off" are identified as defaulters. The company aims to identify the key factors or variables that strongly indicate loan default. Understanding these driver variables will enable the company to improve its risk assessment and optimize its loan portfolio.
### Dataset
- The dataset is provided as a .csv file containing comprehensive loan data.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Applicants whose homeownership status is listed as "MORTGAGE" are more prone to default.
- Higher interest rates are a significant contributing factor to loan defaults.
- Borrowers those with over 10 years of work experience are at a higher risk of defaulting.
- The primary factors influencing the likelihood of loan default include grades, verification status, annual income, debt-to-income ratio (DTI), and public records.
  

### Driving factors:
- High Interest Rates Correlate with Higher Charge-Off Risk:** Loans with higher interest rates, especially in the 10-15% range, show significantly higher charge off rates, indicating a greater lending risk.
- Large Loan Amounts and Longer Terms Increase Risk:** Larger loans, often with longer terms (e.g., 60 months), have higher default rates due to increased exposure and potentially higher interest rates.
- High DTI and More Open Accounts are Associated with Higher Default Risk:** Borrowers with high DTI (10-20) and a large number of open accounts (2-20) tend to default more frequently, highlighting the need for careful assessment of financial behavior.
- Income Verification Plays a Key Role:** Unverified income loans have higher charge off rates, but verified income loans have larger loan amounts, suggesting potential issues with verification methods.
- Loan Purpose and Borrower Profile Impact Default Rates:** Small businesses and borrowers with higher-grade loans (e.g., Grade B & C) and larger loan amounts are at higher risk of default, while debt consolidation, although common, does not have the highest charge off rate.

### Recommendations
-  Adjust Interest Rates: Offer tiered rates based on risk profiles; avoid excessively high rates.
- Limit Loan Amounts and Terms: Cap loans for high-risk borrowers and prefer shorter terms.
- Strict DTI and Account Limits: Set stricter DTI and account limits for eligibility.
- Better Income Verification: Use robust income checks (pay stubs, tax returns) and automate processes.
- Reevaluate Loan Purposes: Scrutinize small business loans and adjust for higher-risk categories.
- Assess Purpose Carefully: Set stricter criteria small business, debt consolidation loans.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.13.0
- Pandas - version 2.2.1
- NumPy - version 2.2.1
- Matplotlib - version 3.10
- Seaborn - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by Upgrad AI & ML Programme.


## Contact
Created by @amarkumar021 and @MayurSurkutla - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
