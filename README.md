# CIND820 - Big Data Analytics Project

## Overview
The purpose of this study is to evaluate the impact of weather conditions on bike share usage in Toronto and predict bikeshare demand. 
In this repository you will find:
1. Code Files - A set of technical reports in JupyterNotebook (IPYNB) format:
    i. Combining Datasets & Data Cleaning,
    ii. EDA (Exploratory Data Analysis),
    iii. Model Evaluation (Trial 1)
    iv. Model Evaulation (Trial 2-3-4)
    
2. Data - Links to downloaded data, raw data & cleaned data in CVS format:
    i. Raw Data Download Links,
    ii. Toronto City Centre Hourly Weather Data (2018),
    iii. Cleaned bikeshare + weather data
3. Documents - A compilation of technical and written reports in HTML and PDF format:
    i. Code files in html format

## 1. Data
Bike Share Toronto Ridership Data (2018) is from Toronto Parking Authority, published on https://open.toronto.ca/dataset/bike-share-toronto-ridership-data/. The dataset consists of data for more than 1.9 million bikeshare trips, with 9 features.
Toronto City Centre Hourly Weather Data (2018) is from Government of Canada, and can be downloaded from https://www.kaggle.com/jasonzxho/toronto-city-centre-hourly-weather-data-20172020?select=Weather+2018. The dataset consists of 8760 instances of hourly weather data, with 28 features.

## 2. Data Cleaning
Data cleaning involved formating the datatypes of features appropriately, checking for duplcate and null values, imputing null values, modifying and simplifying categorical data, and preliminary feature selection and engineering. The datasets were combined and transformed for model building.

## 3. Exploratory Data Analysis
Exploratory Data Analysis was performed on each dataset using charts, histograms, correlation heatmaps, boxplots, and lineplots to identify relationships between variables and patterns in bike share usage. 

## 4. Model Evaluation
Three machine learning algorithms were used to create a model to predict bikeshare demand. These algorithms include Linear Regression, Random Forest Regression, and Gradient Boosting Regression. Models were trained and tested using cross validation. Evaluation metrics used include RSME, negative MAE, R2, and run time. To improve the performance, feature selection and collinearity were addressed, hyperparameter tuning was applied.

