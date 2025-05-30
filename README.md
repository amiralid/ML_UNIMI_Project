# Tree Predictors for Binary Classification - Mushroom Dataset

This project focuses on building **Decision Tree** and **Random Forest** classifiers from scratch to perform binary classification on a mushroom dataset. The primary objective is to distinguish between edible and poisonous mushrooms based on a set of categorical and numerical features.

## Project Overview

Mushroom classification addressed by:

- Implementing custom **Decision Tree** and **Random Forest** algorithms.
- Preprocessing and encoding a mushroom dataset with categorical features.
- Performing **K-Fold Cross-Validation** for robust evaluation.
- Conducting **Hyperparameter Tuning** using an in-house Grid Search.
- Analyzing model performance based on key metrics like Accuracy, Precision, Recall, F1 Score, Specificity, and AUC.
- Interpreting model decisions through **Feature Importance** analysis.

## Dataset

- **Source**: Secondary Mushroom Dataset
- **Size**: 61,069 samples
- **Features**: Categorical and numerical features describing physical mushroom traits
- **Target**: Class (`edible` or `poisonous`)

## Methods

- **Data Cleaning**: Removal of columns with >50% missing values and duplicates.
- **Encoding**: Label encoding for categorical features.
- **Modeling**:
  - Custom Decision Tree with support for Gini, Entropy, and Misclassification Error.
  - Random Forest built from bootstrapped Decision Trees with random feature selection.
- **Evaluation**: 5-Fold Cross-Validation.
- **Hyperparameter Tuning**: Manual grid search on depth, split criteria, number of estimators, and feature subset strategies.

## Author

Amirali Davary — May 2025
---
