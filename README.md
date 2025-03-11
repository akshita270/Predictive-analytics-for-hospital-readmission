# Hospital Readmission Prediction

## Overview

This project aims to predict hospital readmissions using machine learning techniques.  Preventing unnecessary readmissions can improve patient outcomes, reduce healthcare costs, and optimize hospital resource allocation. The project encompasses data exploration, preprocessing, model building, and evaluation.  The goal is to identify patients at high risk of readmission, allowing for targeted interventions and improved care coordination.

## Data Source

The dataset used in this project is `hospital_readmissions.csv`. The dataset contains information about patient demographics, diagnoses, medical history, medications, and hospital utilization. 

The following Python libraries are required to run this project:

*   pandas
*   numpy
*   matplotlib
*   seaborn
*   scikit-learn (sklearn)
*   scipy

  Objectives:¶
Create a report that covers the following:

What is the most common primary diagnosis by age group?
Some doctors believe diabetes might play a central role in readmission. Explore the effect of a diabetes diagnosis on readmission rates.
On what groups of patients should the hospital focus their follow-up efforts to better monitor patients with a high probability of readmission?

  Exploratory Data Analysis (EDA)
The EDA process involves:

Data cleaning and preprocessing: Handling missing values, data type conversions, and renaming columns.

Descriptive statistics: Exploring the distribution of variables and identifying potential patterns.

Visualization: Creating histograms, bar plots, pie charts, and heatmaps to gain insights into the data.

Feature engineering: Creating new features such as 'age_cat' from the 'age' column.

Analyzing the relationship between patient diagnosis (Diabetes vs. Non-Diabetes) and readmission rates.

Modeling
The following machine learning models were used:

Decision Tree Classifier

Random Forest Classifier

The Random Forest Classifier was tuned using GridSearchCV to optimize hyperparameters and improve performance.

Performance Metrics
Accuracy: Achieved a testing accuracy of 61.2% with the tuned Random Forest model.

Precision: The precision score for the tuned Random Forest model is 62.1%.

Recall: The recall score for the tuned Random Forest model is 44.8%.

Future Work
Explore other machine learning models (e.g., Gradient Boosting, Support Vector Machines).

Incorporate additional data features (e.g., socioeconomic factors, lab results, medication adherence).

Address class imbalance using techniques like oversampling or undersampling.

Deploy the model as a web application for real-time readmission risk prediction.

Conduct a more in-depth analysis of the diagnoses and their impact on readmission rates.

