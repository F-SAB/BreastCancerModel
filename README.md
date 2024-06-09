# Breast Cancer Wisconsin (Diagnostic) Model

This repository contains machine learning models trained on the Breast Cancer Wisconsin (Diagnostic) dataset.

## Models

### Model v1 (SVM)
The first model is trained using the Support Vector Machine (SVM) algorithm. SVM is a powerful classification technique that finds the optimal hyperplane which maximizes the margin between different classes. In this case, it is used to classify whether a tumor is malignant or benign based on 30 features extracted from the digitized image of a fine needle aspirate (FNA) of a breast mass.

### Model v2 (Logistic Regression)
The Logistic Regression model is a linear model used for binary classification. It is trained to classify whether a tumor is malignant or benign based on the same 30 features. Logistic Regression estimates the probability that an instance belongs to a particular class and assigns it to the class with the highest probability.

## Files

- `wdbc.data`: The dataset file.
- `F-SAB_model_v1.pkl`: The trained SVM model.
- `F-SAB_model_v2.pkl`: The trained Logistic Regression model.
- `100906105_v1.ipynb`: Script to train the SVM model.
- `100906105_model_v2.ipynb`: Script to train the Logistic Regression model.

## Instructions

### Clone the Repository

```sh
git clone https://github.com/F-SAB/BreastCancerModel.git
cd BreastCancerModel
