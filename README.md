# Introduction to the Heart Disease Dataset
The Heart Disease dataset is a popular dataset from the UCI Machine Learning Repository. It contains information about individuals, including various medical attributes, and indicates whether they have heart disease.

# Heart Disease Data Analysis

This repository contains a comprehensive analysis of the UCI Heart Disease Dataset. The analysis involves data preprocessing, descriptive statistics, data visualization, and inferential statistics to uncover key insights and relationships in the dataset.

## Table of Contents
- [Dataset Overview](#dataset-overview)
- [Analysis Summary](#analysis-summary)
- [Key Findings](#key-findings)
- [Future Work](#future-work)
- [Installation](#installation)

## Dataset Overview
The dataset used in this project is sourced from the UCI Machine Learning Repository and contains various medical attributes related to heart disease, such as age, sex, cholesterol levels, maximum heart rate achieved, and others. The target variable is binary, indicating the presence or absence of heart disease.

- **Number of instances**:303
- **Number of features**: 14

## Analysis Summary

**Loading the Dataset**:
The dataset is loaded using pandas, and basic information about the data is retrieved.
**Descriptive Statistics**: Key measures of central tendency (mean, median, mode), variability (standard deviation, range), skewness, and kurtosis are calculated.
**Data Visualization**: Histograms, box plots, and a correlation matrix heatmap are created to visually explore the data.
**Inferential Statistics**: An independent t-test is performed to test if there is a significant difference in maximum heart rate achieved (thalach) between patients with and without heart disease.

## Key Findings
Age and Cholesterol are positively correlated with the target variable (heart disease).

Maximum Heart Rate (thalach) shows a significant difference between patients with and without heart disease, as supported by the t-test results.

The dataset displays some skewness in variables like cholesterol and oldpeak, which could indicate the need for transformations in predictive modeling.

## Future Work
**Modeling**:
Applying machine learning models (e.g., logistic regression, decision trees) to predict the presence of heart disease based on the dataset.
**Feature Engineering**:
Additional feature creation or transformation, such as normalizing skewed data, could enhance model performance.
**Exploratory Data Analysis (EDA)**:
Deeper EDA to uncover non-linear relationships between the features and the target variable.


## Installation
To run the analysis, you will need Python 3.x and the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- statsmodels

You can install the required libraries by running:
```bash
pip install -r requirements.txt

