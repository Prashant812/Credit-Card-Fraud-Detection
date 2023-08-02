# Credit Card Fraud Detection

In this project, we aim to find fraudulent credit card transactions. Our goal is to develop a machine learning-based fraud detection system. 
Machine learning provides strong new approaches. A dataset of 200,000 completely anonymous transactions is used in this study. 
Every transaction is classified as either fraudulent or not. Take note that the dataset has extremely few instances of fraudulent transactions.
The percentage of fraudulent card transactions is less than 0.1%. This indicates that even in the absence of any fraudulent transactions,
a system that anticipates each transaction to be regular may nevertheless achieve an accuracy of above 99.9%. Techniques for adjustment will be required.

## Data
This Dataset is from Kaggle. This information relates to credit card transaction fraud detection. 
The information was collected in September 2013 by European cardholders using credit cards. The dataset is quite skewed, with frauds making up 0.172% of all transactions 
in the positive class. It only has numeric input variables that have undergone PCA transformation. The original characteristics and further context for the data are not given. 
There are 284,807 cases total in the dataset, of which 492 are false and the remaining 284,315 are real. Test Data and Training Data The training data set consists of 
the previous 198,365 (70%) cases, of which 383 indicate fraudulent transactions and 197,982 actual ones. 
The subsequent 86,442 (30%) transactions make up the test data.

## Workflow
1. Data exploration
2. Data Pre-processing
3. Model Training 

## Model 
Four models are used :-
* Decision Tree Classifier(DTC)
* Random Forest (RFC)
* Xtreame Gradient Boosting (XGBC)
* Deep Neural Network (DNN)

## Imbalanced Data
The data sets that we have used are imbalanced. So, Balanced data set is created for training and comparing to the imbalanced data set.
I have used two method :-
* Undersampling
* Oversampling

## Comparison of Model's Performance:
<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/93676625/195557659-df01c984-8a84-4488-aa6e-a63b92685f5e.png" >
</p>

## Conclusion:
* OverSampled Neural Network performed better.
* Performance of model increased after under sampling and over sampling.
* Confusion Matrix for OverSampled Neural Network :
<p align="center">
  <img width="300" src="https://user-images.githubusercontent.com/93676625/195559088-8a9b0bb5-67c4-44de-81bf-9e75c1e7da3d.png" >
</p>
