# EDA on Lending Club Case Study

## Problem Statement

You work for a consumer finance company which is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures etc. to urban customers. Like most other Lending companies, approving loans of risky applicants (who are likely to default the loan) can lead to credit loss (financial loss) for the company. The aim of the case study is to do EDA on the data set provided and find out the driving factors (driver variables) which are strong indicators of loan default. The company can utilize the understanding (insights) for portfolio and risk assessment.

## Objective
Use EDA to understand how consumer attributes and loan attributes influence the tendency of loan default so that the company can minimize the risk of losing money while lending to customers (i.e. cut down the amount of credit loss).

## Constraints
When a person applies for a loan, there are two types of decisions that could be taken by the company:
1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
	- Fully paid: Applicant has fully paid the loan (the principal & the interest rate)
	- Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
	- Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


## Summary
Following files have been included as part of solution:
1. README.md file sharing the Problem Description.
2. deepen_kumar_sahoo.ipynb file performing EDA on the dataset.
3. DeepenKumarSahoo.pdf sharing the Analysis and Conclusions of the EDA performed.