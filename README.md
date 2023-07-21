# CIND820_Capstone-Project - Airline Passenger Satisfaction

Uploaded files
1. The dataset
2. The data dictionary
3. ipynb file (Updated June 26)
4. Technical report includes EDA and Initial Results (Uploaded June 26)
5. Technical reports (EDA, Supervised ML with overfitted and updated version, Unsupervised ML) (Uploaded July 19 and 20)
6. PDF report (Supervised ML (updated version) and Unsupervised ML) (Uploaded July20)

Last Update: July 20

# Project
“Investigate passenger satisfaction using Machine Learning Techniques” will investigate 
1) how supervised machine learning models predict the top three most influential variables for passenger satisfaction (feature selection)
2) evaluate the best-performed machine learning model to classify influential predictors
3) how association rules (unsupervised machine learning model) identify relationships between variables to identify passenger segmentation

# Final Results (July 20)

This repository contains the following technical documents. 

# Supervised Machine Learning
1. Data preparation for Supervised Machine Learning
   - Converted categorical variables 
   - Removed missing values
   - Created one-hot-key for categorical variables
   - Handled outliers
   - Feature Selection to reduce dimensions
   - Split the dataset
   - Applied undersampling, oversampling and SMOTE to address the imbalance in the target class, "Satisfaction"
2. Build models
   1 Check the score
   - Random Forest: undersampling, oversampling and SMOTE 
   - k-Nearest Neighbours: undersampling, oversampling and SMOTE 
   - XGBoost: undersampling, oversampling and SMOTE
   2
   - Hyperparameter tuning by using GridSearchCV
   - Compared performance of three models
   3
   - Feature Importance on the best-performed model
   - Categorized continuous variables
   - Converted categorical variables into dummy or indicator variables
   4. Apply model
   - Apriori algorithm
   5. Evaluate the output
   - Checked confidence and support
     
# Unsupervised Machine Learning (Association rule) 
1. Data preparation for Association rule
   - Removed missing values
  
The final results provide answers to the following research questions. 

1) how supervised machine learning models predict the top three most influential variables for passenger satisfaction (feature selection)
   -> The top three important factors are 1) Class (Business), 2) Online Boarding and 3) Type of Travel (Business)
   
2) evaluate the best-performed machine learning model to classify influential predictors
   -> Random Forest (Accuracy on training:0.93, Accuracy on test:0.93, F1:0.92) but there was no significant difference among given models. 
   
3) how association rules (unsupervised machine learning model) identify relationships between variables to identify passenger segmentation
   -> Passengers who are Type of Travel (Business) and Customer Type (Returning) are likely to evaluate their overall experience as Satisfied.
   -> Passengers who are Class (Economy), did not get or had a hard time in online boarding, and did not get good In-flight Wi-fi services are likely to evaluate their overall experience as Neutral or Dissatisfied.



