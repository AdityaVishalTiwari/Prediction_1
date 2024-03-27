Real Estate Price Prediction Model

This repository contains code for a real estate price prediction model, which is developed in two main stages: data preprocessing and model training/testing. The model aims to predict real estate prices based on various features such as square footage, location, Baths, Bedrooms, Balcony, and Availability.

Stage 1: Data Preprocessing
In this stage, the focus is on preparing the data for model training. The following steps are performed:

1) Maintaining Pipeline: Establishing a systematic pipeline to streamline data processing tasks.
2) Data Analysis: Utilizing NumPy for data analysis tasks.
3) Data Visualization: Using Matplotlib and Seaborn to create informative graphs and heatmaps for data exploration.
4) Data Cleaning: Removing empty values and filling missing values with mean values.
5) Feature Engineering: Processing features like square footage, size, and location. This involves handling string formats, identifying
6)  outliers, and encoding categorical variables.
7) Preparing Good Data: Ensuring the dataset is well-prepared for model training by addressing data quality issues and enhancing feature representation.

Stage 2: Model Training and Testing
This stage involves training and evaluating different regression models for predicting real estate prices. The steps include:

1) Train-Test Split: Splitting the dataset into training and testing sets.
2) Feature Scaling: Scaling features to a uniform range to improve model performance.
3) Model Training: Training various regression models including Linear Regression, Support Vector Machine, Random Forest Regressor, and XGBoost.
4) Model Evaluation: Comparing model performance using scores and Root Mean Squared Error (RMSE) values.
5) Hyperparameter Tuning: Fine-tuning model parameters to optimize performance.
6) Model Testing: Evaluating the best-performing model on the testing set.
7) Saving and Loading Model: Saving the trained model for future use and loading it when needed.
