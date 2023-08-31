# Security-in-E-transaction
Problem:
The online fraud detection problem includes modelling past transactions with the knowledge of ones that turned 
out to be fraud.


In this project, we have used a Kaggle provided dataset of simulated mobile based 
payment transactions. We analyze this data by categorizing it with respect to different 
types of transactions it contains. The dataset contains five categories of transactions labeled 
as CASH IN, CASH OUT, DEBIT, TRANSFER and PAYMENT.
This dataset consists of both numerical and categorical features like transaction type, 
amount transferred, account numbers of sender and recipient accounts. In our experiments 
we use the following features to train our models. 
1) Transaction type 
2) Transaction amount
3) Sender account balance before transaction 
4) Sender account balance after transaction 
5) Recipient account balance before transaction 
6) Recipient account balance after transaction 
The dataset consists of around 800 transactions out of which 39 transactions are labeled as 
fraud. Total amount is 97.01M. Logistic regression are likely to perform very well on such 
a dataset
