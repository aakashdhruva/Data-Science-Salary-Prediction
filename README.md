# Data Science Salary Prediction

This project aims to predict data science salaries using various machine learning algorithms. The notebook walks through the entire data science pipeline, from data cleaning to model evaluation.

## Table of Contents

1. [Data Cleaning](#data-cleaning)
2. [Outliers Cleaning](#outliers-cleaning)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
4. [One Hot Encoding](#one-hot-encoding)
5. [Model Building](#model-building)
6. [Grid Search](#grid-search)
7. [Different Models Trained](#different-models-trained)
8. [XGBoost and KNN](#xgboost-and-knn)
9. [Linear Regression, Ridge, and Random Forest](#linear-regression-ridge-and-random-forest)

## Data Cleaning

The initial step involves preprocessing the dataset to ensure it is in the right format for subsequent analyses and model training.

## Outliers Cleaning

In this section, techniques and methods are employed to identify and handle outliers in the data, ensuring a more robust model performance.

## Exploratory Data Analysis

This section dives deep into visualizations and statistics to better understand the data's characteristics, distributions, and relationships.

## One Hot Encoding

Categorical data in the dataset is transformed into a format that can be better utilized by machine learning algorithms through one-hot encoding.

## Model Building

Here, various machine learning models are employed to predict data science salaries. The performance and accuracy of these models are gauged based on different metrics.

## Grid Search

Grid search is used to fine-tune models, ensuring the best hyperparameters are chosen for optimal model performance.

## Different Models Trained

This section provides insights into the different machine learning models trained, comparing their performances and drawing conclusions about their applicability to the problem at hand.

## XGBoost and KNN

Both XGBoost and K-Nearest Neighbors algorithms are explored in this section, with training, evaluation, and performance metrics detailed.

## Linear Regression, Ridge, and Random Forest

The training and evaluation of Linear Regression, Ridge Regression, and Random Forest models are presented in this section, with insights into their performances and applicability to the dataset.

---

## Getting Started

To run the notebook and reproduce the results:
1. Ensure you have all the required libraries installed. At the beginning of the notebook, there's a cell that imports all necessary libraries.
2. Make sure the dataset (`df_countries_2.csv`) is in the same directory as the notebook or provide the correct path.
3. Run the notebook cells in sequence to avoid dependency issues.

---

## Future Work

- Explore additional features that could enhance the model's performance.
- Experiment with ensemble methods to combine the strengths of different models.
- Deploy the model as a web application for real-time salary predictions.
