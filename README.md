# Lending Club Case Study
> Understand the factors which Influence loan Charged Off for a financial company.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Understanding](#business-understanding)
* [Business Objectives](#business-objectives)
* [Dataset](#dataset) 
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->
## Problem Statement
For a consumer finance company understand the driving factors (or driver variables) behind loan default | loan charged off.

## Business Understanding
Business Understanding
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Business Objectives
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

## Dataset
Download the dataset from below. It contains the complete loan data for all loans issued through the time period 2007 t0 2011.
[loan.zip](https://github.com/wadhokarshruti/LendingClubCaseStudy/files/12859975/loan.zip)

You can access the data dictionary which describes the meaning of these variables from the provided link below:
[Data_Dictionary.xlsx](https://github.com/wadhokarshruti/LendingClubCaseStudy/files/12859987/Data_Dictionary.xlsx)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- People who thought to repay loan by 36 months defaulted more than the ones who took it for 60 months
  ![image](https://github.com/wadhokarshruti/LendingClubCaseStudy/assets/16097864/b331f6b8-fcdc-43c4-8812-2b7a9f767f2f)

- People who were on rent seems to have defaulted the most while those who owned home were comparatively less in % .
  ![image](https://github.com/wadhokarshruti/LendingClubCaseStudy/assets/16097864/184151a6-927d-4d1c-8f96-ee712993db85)

- Loan seekers, whose purpose was det consolidation defaulted to the max
  ![image](https://github.com/wadhokarshruti/LendingClubCaseStudy/assets/16097864/b8bd3b1f-3f2e-4833-abff-e19a90c80e9a)

- From Histogram we can see max people who took loan of amount ranging from 5k-10k charged off
  ![image](https://github.com/wadhokarshruti/LendingClubCaseStudy/assets/16097864/67f2e231-c662-449c-a8ce-e615e8a52235)

- Applicants’ probability of defaulting is high if he/she is from California state
  ![image](https://github.com/wadhokarshruti/LendingClubCaseStudy/assets/16097864/cd5024c2-91a9-40ce-b0b2-e41d89167f8e)

## Technologies Used
- pandas 1.5.3
- klib 1.1.2

## Acknowledgements
Give credit here.
- Geeksforgeeks
- Upgrad EDA lectures
- Python for data Analysis - By Wes McKinney
- Data analysis using python - Udemy


## Contact
Created by [@wadhokarshruti] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
