---
title: "Predicting Bank Churn Rate"
excerpt: "This project aims to analyze the trend in tweets related to the recession from October 2022 to December 2022, with a focus on identifying instances of layoffs. The study will use data from tweets during this time period to understand the current state of the recession and any potential impacts on employment.<br/>"
reading_order: 12
---

- [Github Code Repository](https://github.com/akankshasharmadid/Bank-Churn-Rate/)
- [Demo of the Application](https://akankshasharmadid-bank-churn-rate-application-0ncp5z.streamlit.app/)

This project aims to predict if the existing customer is going to stay with the bank or not.It is beneficial for banks to know what leads a client towards the decision to leave he company



## Table of contents
- [Bank Churn Rate](#Bank-Churn-Rate)
- [Table of contents](#table-of-contents)
- [Dataset](#dataset)
- [Methods Used](#methods-used)
- [Technologies](#technologies)
- [Required Packages](#required-packages)
- [Authors](#authors)



## Dataset
[(Back to top)](#table-of-contents)


Dataset is taken from Kaggle : https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers
- RowNumber: Corresponds to the record (row) number and has no effect on the output.
- CustomerId: Contains random values and has no effect on customer leaving the bank.
- Surname: The surname of a customer has no impact on their decision to leave the bank.
- CreditScore: Can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
- Country: A customer’s location can affect their decision to leave the bank.
- Gender: It’s interesting to explore whether gender plays a role in a customer leaving the bank.
- Age: This is certainly relevant, since older customers are less likely to leave their bank than younger ones.
- Tenure: Refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
- Balance: Also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
- NumOfProducts: Refers to the number of products that a customer has purchased through the bank.
- HasCrCard: Denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
- IsActiveMember: Active customers are less likely to leave the bank.
- EstimatedSalary: As with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
- Exited: Whether or not the customer left the bank.

This dataset can be used to predict whether a customer is likely to leave the bank or not based on the various features provided. The columns can be used for exploratory data analysis and predictive modeling.


## Methods Used
[(Back to top)](#table-of-contents)

* Data Visualization    
* Data Imputation
* Data Preprocessing
* SMOTE



## Technologies
[(Back to top)](#table-of-contents)

* Python
* Jupyter Notebooks
* StreamLit

## Required Packages
[(Back to top)](#table-of-contents)

* Streamlit
* LazyPredict

