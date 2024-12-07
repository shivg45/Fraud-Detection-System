 # Summary:
# The code implements a machine learning pipeline for detecting fraudulent transactions in a financial dataset. 
# 
# Key Algorithms Used:-
# 1)Label Encoding: This  converts categorical variables (e.g., 'CASH_OUT') into integer labels to make them suitable for the machine learning model.
# 
# 2)Random Under-sampling:- It basically balances the class distribution by undersampling the majority class, preventing the model from being biased towards the dominant class (non-fraud).
# 
# 3)Random Forest Classifier:- An ensemble learning algorithm that builds multiple decision trees and combines them for more accurate predictions. It's robust and works well with both classification and regression tasks.
# 
# 4)StandardScaler:- It scales the features to standardize them, ensuring each feature contributes equally to the model.
# 
# 5)Evaluation Metrics:
# -> Classification Report, Confusion Matrix, and ROC-AUC are used to evaluate how well the model performs in detecting fraudulent transactions.
# 
# 
# Purpose of model:-
# The goal of the code is to develop a machine learning model that can predict fraudulent transactions effectively while handling large-scale data efficiently and dealing with class imbalance. The Random Forest model, along with data preprocessing techniques like encoding and scaling, is used to build an accurate and balanced model for fraud detection.
# 
