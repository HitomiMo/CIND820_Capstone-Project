# CIND820_Capstone-Project - Airline Passenger Satisfaction

Uploaded files
1. The dataset
2. The data dictionary
3. ipynb file (Updated June 26)

Updated June 26

# Project:
“Investigate passenger satisfaction using Machine Learning Techniques” will investigate 
1) how association rules (unsupervised machine learning model) identify relationships between variables to identify passenger segmentation to improve passenger satisfaction
2) how supervised machine learning models predict the top three most influential variables for passenger satisfaction
3) evaluate the best-performed machine learning model to classify influential predictors

# Initial Results (June 26)

This repository contains the following technical documents. 

1. Data preparation for Supervised Machine Learning
   - Split the dataset
   -- The test set includes some missing values. I am looking for a way to include only complete cases in the test set (how to split a dataset into training and golden standard test set)
   - Imputed median value into missing values
   - Capped outliers
   - Encoding all categorical variables (columns with type: object) to numerical variables
   - Feature Selection to reduce dimensions
   - Applied undersampling, oversampling and SMOTE to address the imbalance in the target class, "Satisfaction"
2. Build models
   - Random Forest: undersampling, oversampling and SMOTE 
   - k-Nearest Neighbours: undersampling, oversampling and SMOTE 
   - XGBoost: undersampling, oversampling and SMOTE 
   - Feature Importance
  
The initial results provide answers to the following research question. 

2) how supervised machine learning models predict the top three most influential variables for passenger satisfaction
   - The top three most influential variables are Online Boarding, In-flight Wifi Service and Class. 

However, the test set is not a golden standard test set. Therefore, the results may be changed after re-running the process. 

# Next
1. Split the dataset into training and golden standard test sets and re-run the process
2. Apply cross-validation
3. Complete classification report
4. Unsupervised Machine Learning (association rules)

