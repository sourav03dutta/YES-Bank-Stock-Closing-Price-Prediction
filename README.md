
# YES Bank Stock Closing Price Prediction

THIS PROJECT IS VERIFIED BY - [@ALMABETTER](https://www.almabetter.com/)

![Logo](https://upload.wikimedia.org/wikipedia/commons/d/d1/Yes_Bank_Logo-01.png)

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. The main objective is to predict the stock’s closing price of the month.

We will import NumPy, pandas, matplotlib, seaborn, plotly.express, sklearn models and other librarires in Google Colab then mount the drive. After that we will read csv file from working directory path and assigned it into the data frame.

This dataset has monthly stock prices of the bank since its inception and includes closing, opening, highest, and lowest stock prices of every month.

Date - Date of record

Open - Opening price of the stock in a day

High - High price of the stock in a day

Low - Low price of the stock in a day

Close - Closing price of the stock in a day

The main objective is to predict the stock’s closing price of the month.

In this dataset, there are 185 rows and 5 columns. The dataset contains no duplicate values and null values or missing values. Then checked for unique values, changed date (Month-Year) to proper Date (Year- Month-Day)and after that added three more columns further to describe Date in proper way as 'Year', 'Month', 'Day'.

After Data Wrangling, Exploratory Data Analysis is done to get data visualization and deeper insights of the datasets. Correlation heatmap is plotted to check multicollinearity of the datasets and then plotted Pair plot.

In feature engineering, feature selection is done. Then train test split, Implementation of Supervised regression model with cross validation and hyperparameter tuning.

For further deeper insights time series analysis is also being implemented.

## Conclusion:-

1. We started with data inspection, viewed the data
distribution, checked for correlation and used
averaged features to remove correlation.

2. A simple linear regression model was built and it
was evaluated using accuracy, mean squared error
root mean squared error, r2_score and mean absolute
percentage error.

3. Additional features were engineered by reducing the effect of multi collinearity using
regularization techniques such as ridge, lasso and elastic net regression.

4. The time component was brought in and used averaging techniques like moving average, exponentially weighted moving average and double exponentially weighted moving average to do time-series analysis.

5. Presence of non stationarity was detected, made it stationary by taking lags and difference transformation and built an ARIMA model.




## 🛠 Skills

**Programming Language** :- Python

**Libraries used** :- Pandas, NumPy, Matplotlib, Seaborn, plotly.express, Scipy, Sklearn, Statsmodels, Missingno


## Author

- [@sourav03dutta](https://github.com/sourav03dutta)

