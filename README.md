# Beijing Air Quality Forecasting

This repository contains a Jupyter notebook for forecasting PM2.5 levels in Beijing using a Bidirectional LSTM model, as part of the Kaggle competition "Assignment 1: Time Series Forecasting (May 2025)". The project involves data exploration, preprocessing, model building, and generating predictions for Kaggle submission.

## Project Overview

- **Goal**: Predict PM2.5 levels using RNN-based models.
- **Dataset**: Beijing PM2.5 data from Kaggle.
- **Models Used**: LSTM and Bidirectional LSTM (BiLSTM)
- **Evaluation Metric**: RMSE (Root Mean Squared Error)


## Project Approach

1. **Data Preprocessing**:
   - Handled missing values
   - Normalized features
   - Created lag features
   - One-hot encoded categorical features like `cbwd`

2. **Modeling**:
   - Built and trained LSTM and BiLSTM models
   - Performed hyperparameter tuning (learning rate, batch size, dropout, etc.)
   - Tracked RMSE on training and validation sets

3. **Evaluation**:
   - Compared RMSE across 15 experiments
   - Chose the best model for Kaggle submission

## Setup Instructions

1. **Clone the repo**:
   
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME

# How to Reproduce Results
**Follow the setup instructions**

- Run the entire notebook from top to bottom

- Check the RMSE scores printed after each experiment

- Submit the final predictions
