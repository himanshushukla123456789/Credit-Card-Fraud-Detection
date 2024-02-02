# Credit-Card-Fraud-Detection
Credit Card Fraud Detection
In the banking industry, detecting credit card fraud using machine learning is not just a trend; it is a necessity for the banks, as they need to put proactive monitoring and fraud prevention mechanisms in place. Machine learning helps these institutions reduce time-consuming manual reviews, costly chargebacks and fees, and denial of legitimate transactions.

 

Suppose you are part of the analytics team working on a fraud detection model and its cost-benefit analysis. You need to develop a machine learning model to detect fraudulent transactions based on the historical transactional data of customers with a pool of merchants. You can learn more about transactional data and the creation of historical variables from the link attached here. You may find this helpful in the capstone project while building the fraud detection model. Based on your understanding of the model, you have to analyse the business impact of these fraudulent transactions and recommend the optimal ways that the bank can adopt to mitigate the fraud risks.

 

Understanding and Defining Fraud

Credit card fraud is any dishonest act or behaviour to obtain information without the proper authorisation of the account holder for financial gain. Among the different ways of committing fraud, skimming is the most common one. Skimming is a method used for duplicating information located on the magnetic stripe of the card.  Apart from this, other ways of making fraudulent transactions are as follows:

Manipulation or alteration of genuine cards
Creation of counterfeit cards
Stolen or lost credit cards
Fraudulent telemarketing
 

Data Understanding

This is a simulated data set taken from the Kaggle website and contains both legitimate and fraudulent transactions. You can download the data set using this link.

 

The data set contains credit card transactions of around 1,000 cardholders with a pool of 800 merchants from 1 Jan 2019 to 31 Dec 2020. It contains a total of 18,52,394 transactions, out of which 9,651 are fraudulent transactions. The data set is highly imbalanced, with the positive class (frauds) accounting for 0.52% of the total transactions. Now, since the data set is highly imbalanced, it needs to be handled before model building. The feature 'amt' represents the transaction amount. The feature 'is_fraud' represents class labelling and takes the value 1 the transaction is a fraudulent transaction and 0, otherwise.

 

Since the data set is huge, it will be difficult for you to work on it offline. You are advised to download the raw dataset in your Google Drive and use Google Colab to write your Python code. Create a separate folder in your Google Drive to save any code/CSV files (processed data) and the colab notebooks that you create during this project.

 

Google Colab notebooks are almost the same as Jupyter notebooks in terms of UI and functionalities. However, there are few things that you need to be equipped with before you start working on Colab and hence, we have provided a short document to ease this process. Refer to the attachment below that guides you through how to work with Google Colab.
