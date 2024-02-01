# Apple Quality Classification

This repository contains Python code for analyzing and building machine learning models for apple quality classification. The dataset used in this project includes various parameters of apples, such as Size, Weight, Sweetness, Crunchiness, Juiciness, Ripeness, and Acidity, with the target variable being the Quality of the apples (good or bad).

## Table of Contents
- [Dataset](#dataset)
- [Data Analysis](#data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Statistical Tests](#statistical-tests)
- [Modeling](#modeling)
- [Results](#results)
- [ROC Curves](#roc-curves)
- [Conclusion](#conclusion)
- [Usage](#usage)

## Dataset

The dataset ([`apple_quality.csv`](https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality)) contains information about apples, including their parameters and quality classification. The columns include Size, Weight, Sweetness, Crunchiness, Juiciness, Ripeness, Acidity, and Quality.

## Data Analysis

The initial analysis involves loading the dataset, checking basic statistics, and handling any data preprocessing steps, such as data type conversions.

## Data Preprocessing

This section covers any necessary data preprocessing steps, such as handling missing values, converting categorical variables, and preparing the dataset for modeling.

## Exploratory Data Analysis (EDA)

EDA involves visualizing the relationships between different features and the target variable. This includes pair plots, box plots, scatter plots, and distribution comparisons.

## Statistical Tests

Statistical tests, such as t-tests, are performed to compare means between different classes within each feature.

## Modeling

Machine learning models are built and trained on the dataset. Various classifiers, including Random Forest, Gradient Boosting, XGBoost, LightGBM, SVM, k-NN, Decision Tree, AdaBoost, Logistic Regression, Gaussian Naive Bayes, MLP Neural Network, Extra Trees, Bagging, and a Voting Classifier, are used.

## Results

The performance metrics of each model, including Accuracy, Precision, Recall, F1 Score, and Confusion Matrix, are displayed.

## ROC Curves

ROC curves are plotted for each model to visualize their performance in terms of True Positive Rate and False Positive Rate.

## Conclusion

A brief conclusion summarizes the findings and the effectiveness of the models.

## Usage

To use this code, clone the repository and run the Python script. Ensure that the required libraries are installed (`pandas`, `scikit-learn`, `xgboost`, `lightgbm`, `matplotlib`, `seaborn`, and `scipy`).
