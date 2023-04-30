# Loan-Status-Prediction
# About Project
In this Notebook , We are going to solve the Loan Approval Prediction.This is a Classification problem in which we need to classify whether the loan will be approved or not.
# Problem Statement
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Supreme Housing Finance company deals in all home loans. They have a presence across all urban, semi-urban and rural areas. Customers first apply for a home loan after that company validates the customer’s eligibility for a loan. The company wants to automate the loan eligibility process (real-time) based on customer detail provided while filling out the online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others. To automate this process, they have given a problem to identify the customer segments, that are eligible for loan amounts so that they can specifically target these customers.
# Features of our data
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* LoanID = Unique Loan ID
* Gender = Male/ Female
* Married = Applicant married (Y/N)
* Dependents = Number of dependents
* Education = Applicant Education (Graduate/ Under Graduate)
* SelfEmployed = Self-employed (Y/N)
* ApplicantIncome = Applicant income
* CoapplicantIncome = Coapplicant income
* LoanAmount = Loan amount in thousands
* LoanAmountTerm = Term of the loan in months
* CreditHistory = Credit history
* PropertyArea= Urban/ Semi-Urban/ Rural
* LoanStatus = (Target) Loan approved (Y/N)

# Approach
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📍 # Task1 -> Performing Exploratory Data Analysis on the data
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

1. Applied data pre-processing and preparation techniques in order to obtain clean data.
2. Univariate and Bivariate Analysis was done. Here the main interest was to get an understanding as to how the given attributes relate to the 'Loan Approve' status.
3. Inisghts Obtained are as follows:

📌 408(around 69%) people out of 591 got the approval.
📌 80% of applicants in the dataset are male.
📌Around 65% of the applicants in the dataset are married.
📌About 15% of applicants in the dataset are self-employed.
📌About 85% of applicants have repaid their debts.
📌Most of the applicants don’t have dependents.
📌About 78% of the applicants are graduates.
📌Most of the applicants are from semi-urban areas.
📌The proportion of male and female applicants is more or less the same for both approved and unapproved loans.
📌The proportion of married applicants is higher for the approved loans.
📌The proportion of loans getting approved with 0 dependents is more as pompared to the 1 or 2 or 3+ dependents.
📌The loan is getting approved much higher for graduate than Not graduate.
📌The self employed is getting less loan approved as compared to non self employed.
📌The proportion of loans getting approved in semi-urban areas is higher as compared to that in rural or urban areas.
📌The people with a credit history of 1 are more likely to get their loans approved.
📌Credit History is Highly correlated to our target.
📌Education, Self Employed, Applicant Income, Loan Amount, Loan Amount Term has Negative correlation.
📌Gender, Married, Dependents, Coapplicant Income and Property Area are correlated.
📌
📌
📌
