# StockPrice-Prediction-
# Microsoft Stock Price Prediction

## Overview

This project performs an analysis and predictive modeling of Microsoft (MSFT) stock price data. The dataset contains OHLC (Open, High, Low, Close) stock price information from March 13, 1986, to February 4, 2025.

## Dataset

Source: Microsoft stock market data.

Time Period: 1986-03-13 to 2025-02-04.

Data Format: CSV containing OHLC prices and other relevant trading data.

Missing Data Handling: Stock market closes on weekends and holidays, leading to missing values on those days.

## Technologies Used

Python Libraries:

numpy

pandas

matplotlib

seaborn

sklearn

xgboost

## Machine Learning Models Used:

Logistic Regression

Support Vector Machine (SVM)

XGBoost Classifier

Installation & Setup

## Clone this repository:

git clone https://github.com/your-username/your-repo.git

Navigate to the project directory:

cd your-repo

Install the required dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook:

jupyter notebook

## Usage

Data Loading: The dataset is read from a CSV file.

Data Preprocessing: Missing values are handled, and data is scaled where necessary.

Exploratory Data Analysis (EDA): Visualization of stock price trends using matplotlib and seaborn.

Model Training: Training different machine learning models (Logistic Regression, SVM, XGBoost) for predicting stock price movements.

Model Evaluation: Using accuracy scores and other metrics to assess model performance.

## Results

The trained models help predict stock price trends and behavior.

XGBoost performed better than traditional models like Logistic Regression.

Feature importance analysis provides insights into factors influencing stock price fluctuations.
