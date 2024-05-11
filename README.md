# ML-project

# California Housing Prices Prediction

## Project Overview:
This project aims to predict housing prices in various districts in California using machine learning techniques. The dataset used for this project is the California Housing dataset, which is frequently used in machine learning and statistics for analyzing housing market trends and making predictions about housing prices.

## Dataset Overview:
The dataset contains information on various housing districts in California.

## Features:
Geographic information such as longitude and latitude coordinates, allowing for spatial analysis.

Housing characteristics like median age, total rooms, total bedrooms, population, and households, providing insights into the demographics and living conditions of different districts.

Median income of households, a crucial socio-economic factor influencing housing prices.

Ocean proximity, which could impact housing demand and value.

## Target:
Median house value, serving as the primary target for predictive modeling. This metric is crucial for homeowners, real estate agents, investors, and policymakers in understanding property values and making informed decisions.

## Project Steps:

#### 1. Data Loading and Exploration:
Loaded the dataset and displayed information about its structure.
Visualized histograms of numerical columns to understand their distributions.
#### 2. Data Preprocessing:
Created a new categorical attribute income_cat based on the median_income for stratified sampling.
Split the dataset into training and testing sets using both train_test_split and StratifiedShuffleSplit methods.
Removed the income_cat column from various subsets of the dataset.
#### 3. Feature Engineering:
Calculated additional features based on correlation analysis: population_per_household, bedrooms_per_room, rooms_per_household.
#### 4. Data Preparation:
Preprocessed the data using pipelines, including scaling numerical features and encoding categorical features.
#### 5. Model Training:
Trained three different models: Linear Regression, Random Forest Regression, and Support Vector Machine (SVM).
Evaluated each model's performance using Mean Squared Error (MSE) and visualized actual vs. predicted values.
#### 6. Model Evaluation:
Fine-tuned the Random Forest Regression and SVM models using Randomized Search Cross Validation.
Calculated and compared the MSE for each model on the test set.

## Additional Information:
This project was developed as a part of university coursework. It involves implementing various machine learning techniques to analyze and predict housing prices in California based on the provided dataset.
