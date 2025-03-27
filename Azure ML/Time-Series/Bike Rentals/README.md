# Project Title

Bike Rental Demand Forecasting with Time Series Analysis using AZURE ML

## Description
This project aims to predict daily bike rental demand using time series forecasting techniques. Leveraging Azure's Automated Machine Learning (AutoML) tool, the project explores how machine learning models can accurately forecast rental demand over a 14-day horizon. The data is sourced from bike rental records, and key configurations such as k-fold cross-validation, lag features, and forecast horizon tuning are applied for better prediction accuracy.

##FEATURES 

Time Series Forecasting: Predicting bike rentals based on past daily demand.

Azure Auto ML Integration: Automating model selection, hyperparameter tuning, and featurization through Azure's AutoML tool.

Cross-Validation: Implementing k-fold cross-validation for robust performance evaluation.

Forecast Horizon: Configuring a two-week (14-day) forecast window for practical rental planning.

Data Preprocessing: Ignoring redundant columns like "casual" and "registered" to prevent data leakage.

Model Performance Analysis: Generating and visualizing child jobs and model comparisons from Azure ML Studio.

## TECHNOLOGY USED

Azure Machine Learning (AutoML) – for automated model generation.

Azure Blob Storage – for cloud-based data management.

k-Fold Cross-Validation – to ensure generalization of the model.
