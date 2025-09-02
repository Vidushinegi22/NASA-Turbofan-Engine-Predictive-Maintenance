# NASA-Turbofan-Engine-Predictive-Maintenance

# Predictive Maintenance for Aircraft Engines Using NASA Turbofan Data

Predict the Remaining Useful Life (RUL) of aircraft engines using NASA’s CMAPSS (Turbofan) dataset. Employ machine learning for predictive maintenance to reduce costs and prevent failures.

# Overview

This project applies predictive maintenance to aircraft engines, specifically focusing on forecasting the Remaining Useful Life (RUL) of turbofan engines using NASA’s publicly available simulation data.

# Problem Statement

Aim: Accurately estimate how much time (or operational life) remains before a turbofan engine might fail using sensor data analysis and machine learning models.

# Dataset

Utilizes the NASA Turbofan Engine Degradation Simulation Data (CMAPSS), providing time-series sensor readings for multiple engines under varying operational conditions.

# Project Workflow
# 1. Data Loading & Preprocessing

1.Load multiple engine datasets.

2.Clean the data by removing unnecessary attributes.

3.Handle missing values appropriately.

4.Calculate and assign the RUL label for each engine based on its operational lifecycle.

# 2. Feature Engineering

1.Compute rolling statistics (means) and exponential moving averages to capture short- and long-term sensor trends.

2.Transform and scale features to improve model reliability.

# 3. Modeling

1.Use XGBoost, a high-performing gradient boosting algorithm, to train regression models for RUL prediction.

2.Apply hyperparameter tuning to enhance accuracy.

# 4. Evaluation

1.Evaluate model performance using Root Mean Squared Error (RMSE).

2.Analyze and visualize feature importance to identify key sensors influencing predictions.

# Key Features

1.Rolling means & exponential moving averages for robust trend capture.

2.XGBoost regression for effective RUL prediction.

3.Feature importance visualization to highlight sensor contributions.

# Results

1.Achieved an RMSE of approximately 36.88 on the validation set.

2.Identified critical sensors contributing most to predictive performance.

# Installation & Usage

1.Clone the repository:

git clone https://github.com/Vidushinegi22/NASA-Turbofan-Engine-Predictive-Maintenance.git


2.Install dependencies (e.g., pandas, xgboost, matplotlib, numpy).

3.Run the Jupyter notebook to explore data loading, feature engineering, modeling, and evaluation pipelines.
