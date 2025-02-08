Background & Motivation 
Chronic Kidney Disease (CKD) poses a substantial healthcare burden globally due to its rising prevalence, potential progression to end-stage renal disease, and poor prognosis. Unhealthy dietary habits and inadequate water intake contribute significantly to CKD. With kidneys being crucial for survival, early prediction is essential. 

This study utilizes machine learning techniques, specifically logistic regression, to predict CKD status using clinical data. The methodology involves data preprocessing, handling missing values, aggregation, and feature extraction. Early diagnosis aids in potential rectification, and the motivation is to predict renal disease by analyzing key indicators using three machine learning classification approaches, ultimately selecting the one with the highest accuracy rate.

Problem Statement
Machine learning models present the capability to analyses vast healthcare datasets, unveiling intricate patterns and identifying elusive risk factors that traditional methods may overlook. These algorithms are adept at predicting an individual's risk of developing Chronic Kidney Disease (Chronic kidney disease) by scrutinizing health records and lifestyle factors. Predictive features include blood pressure, cholesterol levels, smoking habits, age, and medical history. Additionally, machine learning models can broaden their analysis to encompass additional variables such as genetic factors and lifestyle choices, providing a comprehensive approach to assessing and predicting Disease risk.

Data Cleaning & Preprocessing
Checking for the null values and duplicate values in the data and processing them suitable methods 
Encoding the data using one hot encoding for the categorical data
Encoding the dependent variable using label encoder

Data splitting
Splitting the data into train sets and test sets in 70:30 ratio by importing the required libraries for model training and evaluation

Logistic Regression
Logistic regression is like making a smart guess when you have to choose between just two options, like 'yes' or 'no.' It helps you figure out the chances of something happening or not happening. 


Conclusion
The study concludes that logistic regression is a highly accurate method for predicting chronic kidney disease, with a precision of 78.75% and an accuracy of 79%. Notably, these models outperform those of prior research, indicating increased reliability. Cross-validation measurements confirm logistic regression's superior performance in predicting CKD compared to other methods. Future research can extend this work by developing a web application incorporating these algorithms and utilizing a larger dataset, enhancing outcomes and enabling healthcare practitioners to anticipate kidney issues more accurately and efficiently. The aim is to improve the framework's reliability, encourage early treatment for chronic renal disease, and promote positive lifestyle changes.



