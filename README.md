# Heart-Disease-Prediction-Using-Machine-Learning

# Project Overview
This project, "Heart Disease Prediction Using Machine Learning," develops a sophisticated web-based application designed to predict heart disease. It harnesses the power of machine learning, processed through SQL data normalization and Python's Flask and pickle libraries, to deliver a real-time diagnostic tool deployed as an accessible webpage.

# Data Preparation
## Data Sources
heart.csv: This file contains comprehensive data on various clinical parameters that are indicative of heart disease. The dataset was thoroughly analyzed and processed to train the machine learning model used in this application.
## Data Normalization
SQL Normalization: The data from heart.csv was normalized using SQL queries to ensure uniformity and consistency. This step involved scaling numerical data and encoding categorical variables to prepare them for effective machine learning model training.

## Model Serialization
Pickle: After training, the machine learning model was serialized using Python's pickle module. This method allows the model to be saved and later reloaded efficiently, maintaining the integrity of its parameters for deployment in the Flask application.

# Exploratory Data Analysis (EDA)
## Overview
Exploratory Data Analysis was conducted to understand the underlying patterns, spot anomalies, and gain actionable insights from the heart.csv data, which could influence the model training process. This phase was crucial to ensure the machine learning model was trained on clean and relevant data.

## Techniques Used
Statistical Summaries: Initial analysis began with generating statistical summaries that provided insights into the data's central tendencies and variability.
Visualization: Key techniques included:
Histograms to understand distributions,
Box plots to detect outliers,
Scatter plots to explore potential relationships between variables,
Correlation matrices to examine how variables interrelate.
Data Cleaning: Involved addressing missing values, correcting errors, and standardizing formats.
Feature Engineering: Developed new features from existing variables to enhance the model’s predictive accuracy.

## Impact of EDA
These analyses informed the preprocessing and modeling strategies, aiding in the selection of suitable machine learning techniques and in the fine-tuning of model parameters. Anomalies and patterns identified during this phase were crucial for crafting a robust predictive model.

## Web Application Development
## Flask Framework
Flask App: Built using Flask, this framework supports robust web application development, including features like routing, request handling, and template rendering.
## Features
Home Page: Allows users to input their health metrics.
Prediction Mechanism: Utilizes the trained model to predict heart disease likelihood based on user inputs and displays the results on the webpage.
## Deployment
Web Deployment: Deployed as a webpage, this application allows global access for real-time predictions, demonstrating its utility as a preventive tool in healthcare.

# Conclusion
The "Heart Disease Prediction Using Machine Learning" project illustrates the integration of data science and web technology to create impactful, user-friendly tools for healthcare. By leveraging data normalization, machine learning, and web application development, this project provides a scalable and effective solution for medical diagnostics and preventive health management.
