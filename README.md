# Wisconsin-Breast-Cancer-Data

Breast Cancer Wisconsin Diagnostic Dataset Analysis


Overview
-----------
This repository contains the analysis of the Breast Cancer Wisconsin Diagnostic Dataset. The dataset is used to diagnose breast cancer based on several features.
Dataset
---------
The dataset is obtained from the University of California, Irvine (UCI) Machine Learning Repository.
It contains 569 instances, each described by 32 features.

The aim of this analysis is to diagnoses the tumor, the tumor is either malignant (M) or benign (B).

Analysis
---------
Data cleaning: Handling missing values and removing duplicates.
Data preprocessing: Normalizing the data using StandardScaler.
Exploratory data analysis: Visualizing the distribution of features and correlation between them.
Feature selection: Selecting relevant features for diagnosis.


Libraries:

Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn


DAY -2 AFTER MODIFICATION:


Feature Scaling: Uses MinMaxScaler to normalize features.

Train-Test Split: Splits data into training (70%) and testing (30%) sets.

Model Training:

Random Forest Classifier

Decision Tree Classifier

Hyperparameter tuning with GridSearchCV
Feature Importance Analysis: Identifies key features influencing model predictions.

The Model Predicts accuracy score, displays Confusion matrix, classification report using different models like Random Forest Classifier and Decision Tree Classifier.

