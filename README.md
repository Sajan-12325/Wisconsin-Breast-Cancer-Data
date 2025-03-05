# Wisconsin-Breast-Cancer-Data

Breast Cancer Wisconsin Diagnostic Dataset Analysis


Overview
-----------
This repository contains the analysis of the Breast Cancer Wisconsin Diagnostic Dataset. The dataset is used to diagnose breast cancer based on several features.

Dataset
---------
The dataset is obtained from the University of California, Irvine (UCI) Machine Learning Repository.
It contains 569 instances and 32 features, including tumor measurements derived from fine needle aspiration biopsies.

The primary objective is to develop predictive models for accurate breast cancer diagnosis.

Data Preprocessing and Exploratory Data Analysis
---------
Data cleaning: Handling missing values and removing duplicates.
Data preprocessing: Converted categorical labels (benign and malignant) into numerical values (1 for malignant, 0 for benign).

MinMaxScaler was used to normalize features, ensuring equal weight for all variables.

Exploratory data analysis: Visualizing the distribution of features and correlation between them.



Train-Test Split: Splits data into training (70%) and testing (30%) sets. Also performing cross validation to improve the model performance and to avoid overfitting

Model Training:

I have used three different models to correctly classify the diagnosis Random Forest Classifier Decision Tree Classifier and also utilized Convolution Neural Network. 

Then tested those models on unseen data Identifies key features influencing model predictions.

The Model Predicts accuracy score, displays Confusion matrix, classification report.

To optimize the Decision Tree Classifier, GridSearchCV was used to find the best hyperparameters and improve model performance.

Random Forest is an ensemble learning method that improves accuracy and reduces overfitting. Also selected top 10 features to fit the model and test  to know how it works on the unseen data.

A fully connected neural network was implemented for binary classification.
Input Layer: 30 neurons (one for each feature).
Hidden Layers: Two dense layers with 30 neurons each, using ReLU activation.
Output Layer: A single neuron with sigmoid activation for binary classification.


Model	        Accuracy Score
Decision Tree		85.0%
Random Forest		92.5%
Neural Network (CNN)	94.1%





