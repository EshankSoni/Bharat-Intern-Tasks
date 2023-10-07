# Bharat-Intern-Tasks
# Task 1- Titanic Classification Project
This repository contains my work for Task 1 of the Data Science Internship at Bharat Intern. In this task, I have performed data analysis and visualization on the Titanic dataset and developed a machine learning model for survival prediction.

# Project Overview:
The Titanic Classification project aims to predict whether a passenger on the Titanic survived or not based on various features such as age, gender, class, and more. This project is a classic example of binary classification in the field of machine learning.

# Task Description:
**Data Analysis:** I started by exploring and analyzing the Titanic dataset to gain insights into the available data. This analysis included:

- Data exploration to understand the structure of the dataset.
- handling missing values and outliers.
- Descriptive statistics to summarize key statistics about the dataset.
- Feature engineering to create new features or transform existing ones for modeling.

**Data Visualization:** I created informative visualizations to better understand the data. This involved:

- Gender distribution using count plots and a pie chart.
- Passenger class (Pclass) distribution and gender distribution within each class.
- Kernel Density Estimation (KDE) plot for passenger ages.
- Survival outcomes distribution and insights by various factors (Parch, SibSp, Embarked).
- Additional visualizations including a histogram and boxplot for dataset overview and outlier detection.
- Pairplot for comprehensive variable relationships.
- Checking the target variable with count plots for survival outcomes.

**Machine Learning Models:** I built the following machine learning models to predict the survival of Titanic passengers:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

**Model Evaluation:**
- Created a summary table with the accuracy scores of each model.
- Visualized the results in a barplot to compare the performance of different algorithms.
- The Random Forest classifier performed exceptionally well, followed closely by the Decision Tree model and K-Nearest Neighbors.

---------------------------------------

# Task 2 - Stock Prediction

This repository contains my work for Task 2 of the Data Science Internship at Bharat Intern. In this task, I have worked on stock prediction using time series data for tech giants such as Apple, Amazon, Google, and Microsoft. The project includes data analysis, visualization, and the development of a machine learning model to predict stock prices.

## Project Overview
The Stock Prediction project focuses on forecasting the closing stock prices of tech giants. It involves the analysis of historical stock data, visualization of stock trends, volatility analysis, moving averages, correlation analysis, risk assessment, and the application of LSTM (Long Short-Term Memory) for predicting future stock prices.

## Key Objectives
1. **Historical Stock Trends:** Analyzing historical stock price changes and visualizing market dynamics.
2. **Volatility Analysis:** Quantifying daily stock price fluctuations to understand average daily volatility.
3. **Moving Averages:** Using moving averages to identify underlying trends in stock price data.
4. **Correlation Insights:** Investigating correlations among tech giants' stock movements to uncover relationships.
5. **Risk Assessment:** Evaluating investment risk associated with each company's stock.
6. **Future Predictions:** Utilizing LSTM for forecasting Apple's closing stock prices and providing predictive insights.

## Data Acquisition
The project begins with obtaining stock data from Yahoo Finance using the 'yfinance' library. Data for tech giants, including Apple, Amazon, Google, and Microsoft, is collected and analyzed.

## Observing Data Characteristics
The dataset is examined, revealing its numerical nature with dates serving as the data index. Weekend data points are absent from the dataset.

## Descriptive Statistical Insights
Descriptive statistics, including measures of central tendency and dispersion, are calculated for numeric and object series within the dataset.

## Closing Price
The closing price, a critical benchmark for tracking stock performance, is visualized with historical views for each tech giant.

## Volume of Sales
Daily sales volume, which is essential for technical analysis, is plotted to observe trends in trading volume.

## Moving Averages
Moving averages (10 and 20 days) are computed to identify trends in stock prices. Visualizations help in understanding the moving average trends.

## Daily Return Analysis
Daily stock return analysis is conducted, revealing insights into daily changes in stock prices. Histograms and KDE plots are used for visualization.

## Correlation Analysis
Correlation between the closing prices of different tech giants is calculated and visualized using seaborn heatmaps. Positive correlations among technology companies are observed.

## Risk Assessment
Risk assessment is performed by comparing the expected return with the standard deviation of daily returns. The relationship between risk and return is visualized.

## Predicting the Closing Price of Apple Inc
An LSTM model is built to predict the closing stock price of Apple Inc. The dataset is preprocessed, and the model is trained and evaluated. Predicted stock prices are compared to actual prices, and the root mean squared error (RMSE) is calculated. The results are visualized to assess the model's performance.

This project provides valuable insights into stock market analysis, including trends, risk assessment, and predictive modeling, offering a comprehensive view of the stock market's complexities.


