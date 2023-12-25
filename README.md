# Wine-Classification-Project

## Overview 
This repository contains code for classifying wines based on their properties. The classification is performed using various machine learning algorithms on a dataset containing various features related to different types of wines (red or white).
## Dataset
The dataset used for this classification task is sourced from https://www.kaggle.com/code/jserna/predicting-color-of-wines-nn-vs-rf/input. It consists of 6497 samples, each with 12 features and the target variable is **color**, which represents the wine class.: The features include:
- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol
- quality

## Project Walkthrough
This project begins with **data loading**, followed by **Data Visualization** for a comprehensive dataset analysis. The next step involves **Pre-processing**, where the quality feature values and labels are converted to binary values, transforming the problem into a numerical context. The dataset is then split into an 80% training set and a 20% test set, followed by standardization of the data.

Following that, we dive into the training phase, making use of various Machine Learning Algorithms:
- Logistic Regression
- Support Vector Machine (Linear Classifier)
- Support Vector Machine (RBF Classifier)
- KNN (K- Nearest Neighbors)
- Decision Tree
- Random Forest

The final stage involves evaluating each algorithm's performance against others, using accuracy as the primary metric for assessment. 
## Details
More details are contained inside the report PDF file that was joined.
 
