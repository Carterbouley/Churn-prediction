

# Churn Prediction

This project is a building block of my personal portfolio. I am currently looking for Data Science opportunities.

### -- Project Status: Completed
## Project Intro/Objective

The purpose of this project is to predict whether a user will Churn (unsubscribe from their telecom provider subscription) or not.
This allows us to analysis which customer traits are likely to churn or not, and optimize telecom service to each of these individuals.
This can help reduce the overall churn rate, improve customer satisfaction and increase profits.

### Methods Used
Inferential Statistics
Machine Learning
Data Visualization
Predictive Modeling

### Technologies
Python
Pandas, jupyter

### Project Description


The source of the data was IBM Watson analytics community.

Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

The data set includes information about:

Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents

I performed various machine learning techniques, dealing with the class imbalances along the way. The results are summarised here:


|Model     |  Accuracy Score   | Area Under Curve   | 
|---------|-----------------|-----------------|
|Logistic Regression (baseline)| 0.7899        | 0.7094
|Logistic Regression (SMOTE) |    0.7483    | 0.7623
|Logistic Regression (RFE)| 0.7415       | 0.7557
|Decision Tree |    0.7682    | 0.7119
|KNN Classification| 0.6970        | 0.7193
|Random Forest |    0.836    | 0.76851
|Naive Bayes| 0.7472       | 0.7609
|SVM classifier Linear |    0.7084    | 0.7477
|SVM classifier RBF |    0.7614    | 0.6452
|XGBoost Classifier |    0.7517    | 0.6739




### Needs of this project

data exploration/descriptive statistics
data processing/cleaning
statistical modeling
writeup/reporting


Feel free to contact me with any questions!
