# ✈️ AWS-Sagemaker-Flight-Price-Prediction



## ⏺️ Project Overview
This project aims to predict the prices of flights based on several features such as departure time, arrival time, source, destination, and other flight-specific details. The model is trained using XGBoost on AWS SageMaker, leveraging its powerful cloud-based machine learning capabilities for model training, hyperparameter tuning, and deployment.


## 〰️ Problem Statement
Airline pricing is dynamic and influenced by multiple factors. Being able to predict flight prices in advance helps travelers make more informed decisions. This project builds a machine learning model to predict flight prices based on available data and attributes related to the flights.


## 〰️ Dataset
The dataset used in this project contains various attributes related to flights such as:

- Airline: The airline operating the flight.
- Source: The origin airport.
- Destination: The destination airport.
- Total_Stops: Number of stops the flight has.
- Date_of_Journey: Date on which the journey is scheduled.
- Price: The target variable, i.e., the flight price.
 
The dataset is split into train, validation, and test sets for model training, tuning, and evaluation.



## 〰️ Introduction to AWS SageMaker

Overview of SageMaker, S3, EC2 & IAM features and capabilities.

Setting up AWS environment and SageMaker instance.


## 〰️ Data Cleaning

Data Cleaning using Numpy and Pandas best practices


## 〰️ Exploratory Data Analysis

- Understanding the workflow of systematically analyzing datasets
- Understanding the various plots, statistical measures and hypothesis tests to analyze datasets
- Exploring a custom EDA module for convenience and significantly reduce complexity of analyzing datasets
- Performing in-depth analysis of various kinds of numeric, categorical and date-time variables
- Leveraging statistical measures, hypothesis tests, and univariate, bivariate and multivariate plots

 
## 〰️ Feature Engineering and Data Preprocessing

- Understanding feature engineering teachniques for different types of variables
- Creating scikit-learn compatible custom classes and functions
- Using advanced scikit-learn features for feature engineering and data preprocessing such as:
  - Pipeline
  - Feature Union
  - Function Transformer
  - Column Transformer
   
## 〰️ Model Training and Deployment

- Training and Tuning a machine learning model on SageMaker
- Using S3 buckets for storage and EC2 for computing purposes
- Creating a web application from scratch and deploying over cloud using Streamlit
