# Hourly PM2.5 Concentration Forecasting Using Machine Learning

## Project Overview

This project aims to predict hourly PM2.5 concentrations using historical air pollution measurements and meteorological data.

The project is developed as part of the Applied Machine Learning Capstone and focuses on comparing regression algorithms for one-hour-ahead air quality forecasting.

## Problem Statement

Air pollution is a major environmental and public health concern. PM2.5 refers to fine particulate matter with a diameter of 2.5 micrometers or smaller.

Our objective is to build a regression-based machine learning system that predicts the PM2.5 concentration for the next hour using information available at the current hour.

## Dataset

**Primary Dataset:** Beijing Multi-Site Air Quality Dataset

**Source:** UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/501/beijing+multi+site+air+quality+data

The dataset includes hourly air pollution and meteorological measurements from monitoring stations in Beijing.

### Key Features

- PM2.5 and historical pollution measurements
- Temperature (TEMP)
- Atmospheric pressure (PRES)
- Dew point (DEWP)
- Rainfall (RAIN)
- Wind speed (WSPM)
- Date and time features

## Machine Learning Models

The following regression algorithms are planned:

1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor

The models will be evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

A chronological train/validation/test split will be used to evaluate forecasting performance.

## Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook
- Git and GitHub

## Project Workflow

1. Dataset collection and understanding
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preprocessing
4. Feature engineering
5. Regression model training
6. Model evaluation and comparison
7. Final model selection
8. Report and presentation

## Team Members

**Anant Sharma — Batch 25**

Responsibilities: Dataset understanding, preprocessing, EDA, feature engineering, and Linear Regression.

**Aditya Choudhary — Batch 26**

Responsibilities: Regression model development, validation, model evaluation, and comparison.

Both members will review and understand the complete implementation.

## Project Status

**In Progress**

The repository will be updated as the implementation progresses.

## Future Improvements

- Interactive Streamlit prediction dashboard
- Model explainability and feature importance
- Additional monitoring stations
- Further hyperparameter optimization

## Academic Information

Applied Machine Learning Capstone Project

Project Type: Regression

Dataset: UCI Beijing Multi-Site Air Quality Dataset
