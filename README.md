# CreditCard_fraud Project <br>


## For **reproduce**:
- Data file need to be download from kaggle
- Output file contain the F1 Score of the project

![image](output/Output_F1_score.png)

## Overview
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, Kaggle cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.


The **GOALS** of this project are to:
- Use different classification model including Naive Bayes, Logistic Regression, Decision Tree and Random Forest to detect fraud.
- Learn the metric for the credit card fraud
- Need to obtain high recall and precision in this case, because False Negative will be a big matter here.
- Use F1 score as metric in this project

**Tools:**
- Python

# 
Project from Kaggle, feature pre-scaled data from Europ credit card transaction





