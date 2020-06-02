# Kaggle Competition: Titanic

Link to the competition: https://www.kaggle.com/c/titanic

### Version History
* V22 - Added Keras Tune
* V23 - Added Boxplots
* V24 - Added Pipelines for Classifiers
* V25 - Added Learning Curves
* V26 - New Model Stacking
* V27 - Added Model Building Function
* V32 - Updated Model Building Function
* V34 - Added History
* V36 - Added CatBoost and LightGBM algorithms

## Introduction
Welcome to my first ever Machine Learning project!
In this notebook we'll do some easy data visualizations and feature engineering before applying different machine learning algorithms like Logistic Regression, Random Forest, Support Vector Machines and more. We're also using a Neural Network using Keras and Tensorflow with a Keras-Tuner for hyperparameter optimization. For better understanding of the dataset and algorithms we'll use a PCA and ROC-Curves.

## History
RMS Titanic was a British passenger liner operated by the White Star Line that sank in the North Atlantic Ocean in the early morning hours of 15 April 1912, after striking an iceberg during her maiden voyage from Southampton to New York City. Of the estimated 2,224 passengers and crew aboard, more than 1,500 died, making the sinking one of modern history's deadliest peacetime commercial marine disasters. RMS Titanic was the largest ship afloat at the time she entered service and was the second of three Olympic-class ocean liners operated by the White Star Line. She was built by the Harland and Wolff shipyard in Belfast.

## Goal
It is our job to predict if a passenger survived the sinking of the Titanic or not. For each person in the test set, we must predict a 0 or 1 value for the variable. Our score is the percentage of passengers we correctly predict.
