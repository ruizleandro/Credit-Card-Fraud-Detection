# Credit Card Fraud Detection Project

## Project Objective 
The main objective of this project is to build a model that can be capable of detect fraudulent transactions without target labels, using unsupervised machine learning algorithms.

## Models Used
I'll start with two unsupervised machine learning models, mainly because I want to explore anomaly detection with unsupervised learning techniques so the algorithm can be used for detecting new forms of frauds.

For this task I'll use:
* *Principal Component Analysis:* to create a model that can learn and detect forms of fraud without the help of labels.
* *Independent Component Analysis:* so I can compare the different types of component analysis.
* *One-Class Support Vector Machines*: another type of unsupervised anomaly detection model.

## Project Summary
The project is divided in three main sections:

### 1) Exploratory Data Analysis

There are no missing values and the documentation lacks of feature explanation, so I wasn't able to make a very extended exploratory data analysis.

![](https://github.com/ruizleandro/Credit-Card-Fraud-Detection/blob/master/Transactions%20according%20to%20amount.png?raw=true)

Conclusions:
* 1 out of 60 transactions were fraudulent.
* Fraudulent transactions were from a little amount almost in every case (the 50 % were for $9 or less).

### 2) Model Selection

After the training phase for the three models described earlier, these were the results:


### 3) Hyperparameter Tuning and Final Test

The model selected for the final test was
