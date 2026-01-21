Sampling Assignment – Credit Card Fraud Dataset
Objective

The objective of this assignment is to understand the importance of sampling techniques in handling highly imbalanced datasets and to analyze how different sampling strategies affect the accuracy of multiple machine learning models.
Dataset

Name: Creditcard_data.csv

Source:
https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv

Description:
The dataset is highly imbalanced, where the target variable Class represents fraudulent and non-fraudulent transactions.

Steps Performed
1. Data Loading

Loaded the dataset using Pandas.

Separated features and target variable (Class).

2. Dataset Balancing

Applied Random Over Sampling to convert the imbalanced dataset into a balanced dataset.

3. Sampling Techniques Applied

Five different sampling techniques were applied on the balanced dataset:

Simple Random Sampling

Stratified Sampling

Systematic Sampling

Cluster Sampling

Bootstrap Sampling

Each sampling technique selects approximately 30% of the balanced dataset.

Machine Learning Models Used

Five different machine learning models were trained and evaluated:

M1: Logistic Regression

M2: Decision Tree Classifier

M3: Random Forest Classifier

M4: Naive Bayes

M5: Support Vector Machine
Output
<img width="1736" height="547" alt="image" src="https://github.com/user-attachments/assets/13cea28f-8a19-4835-a57e-9eec7fbe263c" />
