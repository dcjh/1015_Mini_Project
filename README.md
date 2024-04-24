# NTU Y1S2 SC1015 Project: Data Analysis for More Targeted Marketing to Improve Sales

## About

### Table of Contents

1. [Data Cleaning & Extraction](#data-cleaning--extraction)
2. [Exploratory Data Analysis](#exploratory-data-analysis)
3. [Machine Learning](#machine-learning)
4. [Conclusion](#conclusion)

### Contributors

- Darrick
- Siaw Xuan
- Felis

## Dataset

Customer Personality Analysis Dataset: [Link to Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

## Problem Statement

What are the different types of products different customers are most likely to buy?

Customer personality analysis helps a business modify its marketing efforts based on its target customers from different customer segments. By analyzing which customer segment is most likely to buy a specific product, we aim to make marketing efforts more targeted to boost sales.

## Data Cleaning & Extraction

Cleaning the dataset involved:
- Dropping null and duplicate values.
- Handling outlier values for better fitting and enhanced accuracy.

## Exploratory Data Analysis

### Predictor Variables

- Income
- Places (of purchase)
- Age + Education
- Marital Status + Kidhome (number of kids at home) + Teenhome (number of teenagers at home)

### Response Variables

- Meats
- Wines
- Fish
- Sweets
- Gold
- Fruits

### Univariate Analysis

- **Income**: Statistically significant relationship with the response variables.
- **Places**: Statistically significant relationship with the response variables.

### Multivariate Analysis

- **Age and Education**: Statistically insignificant relationship with the response variables.
- **Marital Status, Kidhome, Teenhome**: Statistically insignificant relationship with the response variables.

## Machine Learning

We employed the following models using the SciKit-Learn libraries:

1. **K-Nearest Neighbours (KNN)**
   - A non-parametric algorithm for classification and regression problems using feature similarity.

2. **Random Forest Regression**
   - Ensemble learning technique combining predictions from multiple decision trees.

3. **Gradient Boosting Regression**
   - Boosting technique iteratively improving model predictions.

## Conclusion

The most accurate machine learning model for predictions was [mention the model here].

## References

- [SciKit-Learn Documentation](https://scikit-learn.org/stable/)
- [Random Forest Regression Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
