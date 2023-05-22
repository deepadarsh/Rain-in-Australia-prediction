# Rain in Australia Dataset Analysis

This repository contains a Python script that performs an analysis on the Rain in Australia dataset. The script explores the dataset, performs data cleaning and preprocessing, and conducts various data analyses to gain insights into the weather patterns in Australia.

## Dataset

The dataset used for this analysis is the "weatherAUS.csv" file from the Weather Dataset Rattle Package. It contains historical weather data collected from numerous weather stations across Australia.

## Dependencies

To run the script, you need to have the following dependencies installed:

- numpy
- pandas
- seaborn
- matplotlib
- sklearn
- category_encoders

You can install these dependencies using pip:

pip install numpy pandas seaborn matplotlib scikit-learn category-encoders

## Analysis Steps

The script performs the following analysis steps:

1. Importing dependencies and reading the dataset.
2. Exploring the dataset's shape, summary statistics, and information.
3. Conducting univariate analysis on the target variable "RainTomorrow".
4. Performing bivariate analysis on categorical variables.
5. Handling missing values and preprocessing the data.
6. Conducting multivariate analysis to understand variable correlations.
7. Splitting the data into training and testing sets.
8. Handling missing values and outliers in the training set.
9. Encoding categorical variables and preparing the training data.
10. Performing machine learning analysis using various models.

Feel free to modify the script or extend the analysis as per your requirements.

## Results

The analysis provides insights into the relationship between different weather variables and the occurrence of rain in Australia. It helps understand the factors that contribute to rainfall and provides a foundation for building predictive models to forecast rain.
