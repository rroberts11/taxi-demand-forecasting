# taxi-demand-forecasting

# Table of Contents
About

Problem Solved

Key Technologies

Features

Technologies

Installation

Usage

Contact

## About
taxi-demand-forecasting is a time series analysis project focused on predicting taxi demand using real-world data. The goal is to analyze temporal patterns, engineer meaningful features, and apply machine learning and statistical models to forecast short-term demand.

## Problem Solved
This project helps address the challenge of predicting ride demand in urban settings, which is crucial for optimizing fleet availability and improving service efficiency. Accurate demand forecasting can assist in resource allocation for ride-hailing and taxi services.

## Key Technologies
pandas: For data manipulation and time indexing

numpy: For numerical operations

matplotlib/seaborn: For data visualization

scikit-learn: For machine learning models and evaluation

statsmodels: For SARIMA time series modeling

## Features
Loads and preprocesses time series taxi request data

Creates time-based features like hour, weekday, and holiday flags

Uses Random Forest and Gradient Boosting for regression

Implements SARIMA for seasonal trend modeling

Compares model performance using RMSE

Visualizes trends, stationarity tests, and forecasts

## Technologies
This project is built with:
Python 3.10+: Primary language for analysis and modeling

pandas: For time series data handling and feature engineering

NumPy: For numerical processing

Matplotlib & Seaborn: For visualizing data and trends

Scikit-learn: For machine learning modeling and metrics

Statsmodels: For SARIMA-based time series forecasting

## Installation
## Prerequisites
Python 3.10+

pip (Python package installer)

## Steps to Install
### Clone the repository:
bash
Copy
Edit
git clone https://github.com/rroberts11/taxi-demand-forecasting.git
Navigate to the project directory:
bash
Copy
Edit
cd taxi-demand-forecasting
(Optional) Create and activate a virtual environment:
bash
Copy
Edit
python -m venv env
### macOS/Linux
source env/bin/activate  
### Windows
env\Scripts\activate
Install the required dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Usage
To explore and run the forecasting models:

### Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook taxi_demand_forecasting.ipynb
Follow through the notebook to see data preprocessing, modeling, and evaluation steps in action.

## Contact
Name: Ryan Roberts
Email: rroberts.ds@gmail.com
GitHub: https://github.com/rroberts11
LinkedIn: https://www.linkedin.com/in/ryan-roberts-51775b147

