# Credit Card Fraud Detection

## Importing Libraries
**Importing Libraries**</br>
* numpy
* pandas
* matplotlib
* sklearn
* LogisticRegression
* DecisionTreeClassifier
* KNeighborsClassifier
* RandomForestClassifier
* XGBClassifier
#### Model Evaluation Metrics
* Accuracy Score
* Confusion Matrix
* F1 Score
## Dataset
The dataset that can be downloaded from this Kaggle link https://www.kaggle.com/mlg-ulb/creditcardfraud
## Introduction
Fraud detection is a set of activities that are taken to prevent money or property from being obtained through false pretenses.
Credit card fraud is increasing considerably with the development of modern technology and the global superhighways of communication. Credit card fraud costs consumers and the financial company billions of dollars annually, and fraudsters continuously try to find new rules and tactics to commit illegal actions. Thus, fraud detection systems have become essential for banks and financial institution, to minimize their losses. However, there is a lack of published literature on credit card fraud detection techniques, due to the unavailable credit card transactions dataset for researchers. </br>
Fraud is a major problem for the whole credit card industry that grows bigger with the increasing popularity of electronic money transfers. 
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## Content
The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.


Identify fraudulent credit card transactions.
Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification. 

## Model Development
we will building six different types of classification model
*   Decision Tree
*   K_Nearest Neighbors (KNN)
*   Logistic Regression
*   Support Vector Machine (SVM)
*   Random Forest
*   XGBoost

## Acknowledgements
The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. More details on current and past projects on related topics are available on https://www.researchgate.net/project/Fraud-detection-5 and the page of the DefeatFraud project.
