# Yes Bank Stock Closing Price Prediction 📈💰
![Yes Bank.png]([https://github.com/meabhaykr/Yes-Bank-Stock-Closing-Price-prediction/blob/main/image/Yes%20Bank%20Stock%20Closing%20Price%20Prediction.png](https://github.com/meabhaykr/Yes-Bank-Stock-Closing-Price-prediction/blob/main/image/Yes%20Bank.png))
## Overview
Welcome to the "Yes Bank Stock Closing Price Prediction" project! In this exciting venture, we'll explore the fascinating world of financial modeling to predict the monthly closing prices of Yes Bank, one of India's prominent financial institutions. This endeavor is particularly noteworthy due to the impact of a significant fraud case involving Rana Kapoor in 2018. Our primary mission is to gauge how such a high-profile event influences stock prices and whether predictive models, including time series models, can help us make sense of the financial landscape.

## The Dataset 📊
Our project is fueled by a comprehensive dataset encompassing monthly stock prices of Yes Bank from its inception. This dataset includes essential metrics like closing prices, opening prices, highest prices, and lowest prices for each month. We believe that this rich historical data provides an ideal backdrop for investigating the impact of the Rana Kapoor case on Yes Bank's stock performance.

You can access the dataset in the "data" folder by [clicking here](https://drive.google.com/file/d/1XmDjz29BCFYRpgTBHFfJlQnPwWElGHqH/view?usp=sharing).

## Objective 🎯
At the heart of our project lies the central goal: predicting the closing price of Yes Bank's stock for each month. We seek to unravel the intricate dynamics of stock prices, considering both the regular ebb and flow of financial markets and the extraordinary influence of the Rana Kapoor incident. By leveraging machine learning models, we aim to provide insights that can inform better financial decision-making.

## Models at Your Service 🤖
In our quest to predict Yes Bank's closing prices, we have enlisted three powerful models:

1. **Ridge Regression:**
   - Type: Linear regression with regularization.
   - Purpose: To strike a balance between model complexity and performance, particularly when dealing with multicollinearity.

2. **Random Forest:**
   - Type: Ensemble learning model based on decision trees.
   - Purpose: To harness the strength of multiple decision trees, each trained on different data subsets, and aggregate their predictions for robust results.

3. **XGBoost Regressor:**
   - Type: Ensemble learning model using gradient boosting.
   - Purpose: To construct a sequential ensemble of decision trees, with error correction through gradient-based optimization, delivering outstanding predictive accuracy.

## Evaluation Metrics 📈
To evaluate the performance of our predictive models, we employ a trio of robust metrics:

1. **RMSE (Root Mean Squared Error):**
   - Use: To assess prediction accuracy by measuring the average magnitude of prediction errors. Lower RMSE indicates a better fit.

2. **Adjusted R2 (Adjusted R-squared):**
   - Use: To balance model complexity with performance and select relevant predictors by adjusting the traditional R-squared for the number of features.

3. **R2 Score (Coefficient of Determination):**
   - Use: To quantify the proportion of variance in the target variable explained by the model. It ranges from 0 to 1, with higher values indicating a better fit.

## How to Get Started 🚀
To embark on your journey of predicting Yes Bank's closing prices, follow these straightforward steps:

1. Open the Jupyter Notebook file named `Yes_Bank_Stock_Price_Prediction.ipynb`.

2. Execute the notebook cell by cell to load and preprocess the data, train the machine learning models, and make predictions.

3. The notebook provides a comprehensive exploration of data analysis, feature engineering, model training, and evaluation.

## Conclusion and Beyond 🌟
In conclusion, our project is driven by a quest for financial insights and predictive accuracy. With the XGBoost Regressor model achieving exceptional results, we're poised for success. 

The future holds exciting possibilities:
- Exploring daily-level stock price data for finer predictions.
- Incorporating additional features, such as holidays, political decisions, events, and volume data.
- Evaluating time series models like ARIMA and LSTM for even more precise stock price predictions.

With the current dataset and features, our model shines brightly. We invite you to dive into this journey of financial discovery. If you have questions or need assistance, don't hesitate to connect with us on [LinkedIn](https://www.linkedin.com/in/meabhaykr/).

May your predictions be sharp, and your financial decisions, well-informed!
