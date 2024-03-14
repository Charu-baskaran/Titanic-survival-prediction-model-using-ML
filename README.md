# Titanic Survival Prediction Model using Machine Learning

## Overview

This repository contains code for a machine learning model that predicts the survival of passengers aboard the Titanic. The model utilizes logistic regression and achieves an accuracy of 83%, making it reliable for determining whether passengers will survive or not.

## Dataset

The dataset used in this project is the famous Titanic dataset, which contains information about passengers such as age, gender, class, and whether they survived or not. The dataset is available in CSV format and is included in the repository .

## Data Processing

1. Handling Missing Values: 
   - Missing values in the dataset are addressed by replacing them with the mean value of the respective feature.
   - Null values are removed from the dataset to ensure data integrity.

2. Visualization:
   - Histograms, seaborn plots (sns), box plots, and count plots are used to visualize various aspects of the dataset such as age distribution, class distribution, survival counts, etc.


## Training Data Preparation

1. Converting to Categorical Data:
   - Certain features such as 'Sex' and 'Embarked' are converted to categorical data to facilitate model training.

2. Deleting Unwanted Columns:
   - Columns that are deemed irrelevant for predicting survival, such as 'PassengerId', 'Sex','Pclass','Embarked', and 'Ticket', are removed from the dataset.

## Model Training

Logistic regression is employed to train the model using the preprocessed training data.

## Results

The trained model achieves an accuracy of 83%, indicating its effectiveness in predicting passenger survival on the Titanic.



