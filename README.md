COVID-19 Mortality Prediction Project
Overview
This repository contains the code and resources for a predictive modeling project focused on predicting COVID-19 mortality using machine learning techniques. The study explores the performance of three different models: Decision Tree, Random Forest, and Support Vector Machine (SVM). Two distinct sets of features are employed: the first set derived from previous research, and a new set obtained through Recursive Feature Elimination (RFE).

Datasets
Large Dataset:

Contains information from 375 patients
Includes 40 relevant features
Small Dataset:

Comprises data from 110 patients
Utilizes a reduced set of 3 features
Models
Decision Tree:

Implemented to understand the inherent structure of the data.
Random Forest:

Chosen as the best-performing model based on experimental results.
Support Vector Machine (SVM):

Employed for its effectiveness in classification tasks.
Feature Sets
Original Feature Set:

Extracted from prior literature.
New Feature Set (RFE):

Identified through Recursive Feature Elimination.
Results
The study demonstrates that the Random Forest model outperforms other models in predicting COVID-19 mortality. Confidence intervals analysis reveals a performance increase with the new feature set, though the difference is not deemed statistically significant.

Repository Contents
Code: Python scripts and Jupyter Notebooks for implementing models and conducting analyses.
Datasets: Both the large and small datasets used in the study.
Results: Outputs, visualizations, and performance metrics obtained from the models.
Documentation: Additional resources, such as the paper summarizing the findings.
