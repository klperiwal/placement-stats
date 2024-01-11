# Placement-Status

## Overview:
This Jupyter Notebook aims to predict the placement status of students based on various features using different machine learning models. The dataset includes information about students, such as academic performance, internships, and other relevant factors.

<br>

## Models Used:
The following ML models were employed for placement prediction:

### K-Nearest Neighbors (KNN)-
Hyperparameter settings: n_neighbors, weights.
### Decision Tree-
Hyperparameter settings: criterion, max_depth, min_samples_split.
### Random Forest-
Hyperparameter settings: n_estimators, max_depth, min_samples_split.
### Gaussian Naive Bayes-
No hyperparameters to tune for Gaussian Naive Bayes.

<br>

## Requirements:
Make sure to have the following libraries installed:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

<br>

## Results:

### - Model 1 (KNN):
- Accuracy: 87.37%
- Confusion Matrix:
[[243,  16],
 [ 56, 279]]


### - Model 2 (Decision Tree):
- Accuracy: 87.37%
- Confusion Matrix: 
[[235, 24],
 [51, 284]]


### - Model 3 (Random Forest):
- Accuracy: 87.87%
- Confusion Matrix:
[[243,  16],
  [ 56, 279]]

  
### - Model 4 (Gaussian Naive Bayes):
- Accuracy: 82.65%
- Confusion Matrix:
[[223,  36],
  [ 67, 268]]
