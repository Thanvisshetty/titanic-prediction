# Titanic EDA + Prediction

## Table of Contents

1. [Introduction](#introduction)
2. [Adding Basic Libraries & Importing the Dataset](#adding-basic-libraries--importing-the-dataset)
3. [Visual EDA and Feature Engineering](#visual-eda-and-feature-engineering)
4. [Imputing Missing Data and Handling Categorical Variables](#imputing-missing-data-and-handling-categorical-variables)
5. [Model Development](#model-development)
6. [Conclusion](#conclusion)
7. [References](#references)

## Introduction

This project analyzes the Titanic dataset using Exploratory Data Analysis (EDA) and builds predictive models to determine passenger survival. The Titanic dataset is a classic dataset in machine learning, containing various features about the passengers and their survival status.

## Adding Basic Libraries & Importing the Dataset

In this section, the necessary libraries for data manipulation, visualization, and machine learning are imported. The Titanic dataset is then loaded into a DataFrame for analysis.

## Visual EDA and Feature Engineering

Visual EDA involves creating various plots and charts to explore relationships and patterns within the data. Key steps include:

- Analyzing the survival rates across different demographics such as gender and class.
- Creating new features through feature engineering, like extracting titles from passenger names to better understand social status.

## Imputing Missing Data and Handling Categorical Variables

This section addresses the handling of missing data and categorical variables:

- Missing Data: Strategies are implemented to impute missing values, such as using the median for age and the mode for embarked locations.
- Categorical Variables: Categorical features are converted into numerical format through techniques like one-hot encoding to prepare the data for modeling.

## Model Development

The modeling process consists of several key steps:

1. Data Splitting: The dataset is divided into training and testing sets to evaluate model performance.
2. Model Training: Various predictive models, such as Logistic Regression and Random Forest, are trained on the training data.
3. Evaluation: The models are evaluated using metrics like accuracy, precision, recall, and confusion matrices to assess their performance.

## Conclusion

This project offers valuable insights into the Titanic dataset and demonstrates the process of building a predictive model for survival prediction. The findings and model performance metrics indicate the potential for further enhancements through hyperparameter tuning and more advanced modeling techniques.

## References

- [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
