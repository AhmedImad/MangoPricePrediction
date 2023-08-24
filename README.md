# Price Prediction Model for Mango Prices

This repository contains a price prediction model for mango prices. The goal of this project is to develop a predictive model that can accurately estimate the price of mangoes based on various features. The project involves data preprocessing, exploratory data analysis, feature engineering, and model building.

## Table of Contents

- [About the Dataset](#about-the-dataset)
- [Code Explanation](#code-explanation)
- [Techniques Used](#techniques-used)
- [Intention of the Code](#intention-of-the-code)
- [Step-by-Step Explanation](#step-by-step-explanation)

## About the Dataset

The dataset used for this project contains export quality mango prices. It includes features such as the grade of mangoes, the region they come from, and their price per kilogram. The data requires cleaning, preprocessing, and analysis to prepare it for model development.

## Code Explanation

The provided code is an initial attempt to build a price prediction model for mango prices. The code performs the following steps:

1. **Data Loading:** The dataset is loaded from an Excel file located in a Google Drive directory.
2. **Data Preprocessing:** The data is cleaned and missing values in the 'DistrictRegion' column are filled with the mode.
3. **Data Visualization:** Histogram and box plot visualizations are used to understand the distribution of the 'Price' column and identify potential outliers.
4. **Outlier Removal:** Outliers are detected using the Interquartile Range (IQR) method and removed from the dataset.
5. **Feature Engineering:** Unique values for 'grade' and 'DistrictRegion' are extracted to gain insights into the data.
6. **One-Hot Encoding:** Categorical variables are one-hot encoded to prepare the data for model training.
7. **Model Building:** Multiple regression models are trained on the preprocessed dataset to predict mango prices.
8. **Model Evaluation:** The R-squared (R^2) score is used to evaluate the performance of each model.

## Techniques Used

The following techniques and concepts are utilized in this code:

- Data preprocessing and cleaning.
- Exploratory data analysis (EDA) using histograms and box plots.
- Outlier detection and removal using the Interquartile Range (IQR) method.
- Feature engineering to extract unique values from categorical columns.
- One-hot encoding to convert categorical variables into a numerical format.
- Training and evaluating regression models for price prediction.

## Intention of the Code

The intention of this code is to serve as a starting point for building a price prediction model for mango prices. It demonstrates fundamental data preprocessing, visualization, and model building techniques. The code aims to identify potential patterns in the data and assess the predictive capabilities of various regression models.

## Step-by-Step Explanation

1. **Data Loading:** The code begins by loading the mango price dataset from an Excel file located in a Google Drive directory.
2. **Data Preprocessing:** Missing values in the 'DistrictRegion' column are filled using the mode, ensuring data completeness.
3. **Data Visualization:** Visualizations are created to understand the distribution and potential outliers in the 'Price' column.
4. **Outlier Removal:** The Interquartile Range (IQR) method is employed to detect and remove outliers from the dataset.
5. **Feature Engineering:** Unique values for 'grade' and 'DistrictRegion' are extracted to gain insights into these categorical variables.
6. **One-Hot Encoding:** Categorical variables are encoded into a numerical format using one-hot encoding to prepare for model training.
7. **Model Building:** Multiple regression models are trained on the preprocessed data, including linear regression, decision trees, and more.
8. **Model Evaluation:** The R-squared (R^2) score is calculated to assess the performance of each trained model in predicting mango prices.

