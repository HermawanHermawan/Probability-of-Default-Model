# Probability-of-Default-Model
Modelling Probability of Default (PD Model) by applying Logistic Regression 


## PROJECT DESCRIPTION
This project aims to build a model to rank loan applicants based on their repayment capability. Financial institutions, such as banks or other multi-finance companies, can use such a model to choose the customers who are eligible for the loan. In this manner, the institutions can minimize the potential risk of the lenders not repaying their loans. In financial terminology, this condition is commonly called `Default Event`. 

In addressing the problem, this project applies the `Probability of Default Model`, commonly known as the `PD Model`, to assess the credit risk associated with each borrower. The probability of Default is defined as the borrowers' inability to repay their debt in full or on time. In other words, it is the likelihood that a borrower will default. To model such an occurrence, `Logistic Regression` is used as it gives the binary outcome specifying whether or not a customer has defaulted. 

The data used in this project consists of two parts, namely the training and testing dataset. The training dataset contains 61504 loan applicants with corresponding 24 features for each applicant. As for the testing data, it contains 154761 observations with the same number of features. In each dataset, a 'TARGET' column contains binary values specifying whether a customer has made late payments. In this case, 0 means default while 1 is non-default.  This project will measure the likelihood of an applicant being a good and bad borrower by using all provided information. The target column therefore will be selected as the target column, while the other columns as the independent variables. 
