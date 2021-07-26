# Financial-History-Analysis-to-Predict-likelihood-of-E-Signing

**Business Case:**



E-Signing is the phase before the Loan application is sent to the Financial Team for approval. Loan applications are received from:
a) Bank Website b) Advertisement c) Peer to Peer Lending Marketplace

We will analyze the loan applications coming from Peer to Peer Marketplaces to determin the quality of customers being sent and how likely are they going to e-sign the application form in Application.

**Files:**


****Exploratory Data Analysis:****

In this file you can find the Initial Data Analysis of the Client Sample Data. The analysis done are:


1) Loading Data
2) Checking the Data description
3) Cleaning the data
4) Plotting Data for pattern evaluation
5) Plotting distribution of the Numerical Columns
6) Checking the correlation of Numerical features with Target Variable
7) Checking correlation within features

Based on the above, we will evaluate the important features that can be used for Model Building


****Data Pre Processing:****

This file contains all the necessary transformations done to features before Model Building. 


1) Dropping unnecessary columns
2) Using One Hot Encoding for categorical feature
3) Splitting data into Train and Test
4) Scale the data
5) Store scaled into separate CSV files for Model building



****Model Building:****


This files consists of various classification algorithms used to train model using scaled data. Capture performance of each and every trained model and compare the performance. Select the best performing model for Hyper Parameter optimization.

1) Logisitic Regression
2) Support Vector Classifier
3) Random Forest Classifier
4) Use K Fold Cross validation on each model
5) Evalute Precision, Recall, F1 Score and Accuracy of each algorithm


****Best Model Finder****


This file contains optimizing the best model found using all possible hyperparameters and find the parameters generating a low bias and low variance model considering the Precision, Recall, F1 Score and Accuracy of the algorithm using GridSearchCV
