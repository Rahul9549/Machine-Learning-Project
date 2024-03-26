## TCS – Stock Price Prediction
--------------------------------------------------------------------------------------------
## Contents

1. Objective
2. Project Structure
3. Data Collection and Details
4. EDA
5. Data Visualization
6. Feature Extraction
7. Model Building and Evaluation
8. Deployment
-------------------------------------------------------------------------------------------   
## 1. Objective

Stock price prediction aims to forecast the future movement of a stock's price based on 
historical data and various factors such as market trends, company performance and investor 
sentiment. The goal is to make informed investment decisions, including buying, selling, or 
holding stocks, with the aim of maximizing profits or minimizing losses. 
                                                                       The objective is to understand the underlying structure in TCS Stock Price data and come up with a suitable forecasting model that can effectively forecast for the next 30 Days.
-------------------------------------------------------------------------------------------  
## 2. Project Structure

1. Business Understanding
2. Data Collection
3. Data Preparation
4. Exploratory Data Analysis
5. Model Evaluation
6. Model Deployment
 -------------------------------------------------------------------------------------------

## 3. Data Collection and Details

1. The Stock Price data for TCS (Tata Consultancy Services) is obtained from Yahoo Finance.
2. The dataset has 5260 Rows and 7 Columns.
3. The date of the data ranges from 2003-01-01 to 2024-02-29.

These are the following columns in the dataset-
1. Date: The date on which the stock data was recorded.
2. Open: The price at which the stock started trading.
3. High: The highest price the stock reached during the trading session.
4. Low: The lowest price the stock reached during the trading session.
5. Close: The final price at which the stock traded at the end of the trading session.
6. Adj Close (Adjusted Close): The closing price of the stock adjusted for any corporate actions that may affect comparability.
7. Volume: The total number of shares traded.
 -------------------------------------------------------------------------------------------
## 4. EDA – Exploratory Data Analysis

Exploratory Data Analysis (EDA) involves analyzing and summarizing the main characteristics 
of a dataset to understand its structure and uncover patterns and relationships. 

1. Loading the Dataset: Start by loading the TCS dataset into your preferred data analysis
   environment, such as Python with pandas, or R.

2.  Data Summary: Use functions like head(), info(), and describe() to get an initial
   overview of the dataset. This includes checking for missing values, understanding the
   data types of each column, and getting summary statistics.

3. Time Series Analysis: Since this is stock price data, it's likely a time series. You can
   use tools like line plots, histograms, and autocorrelation plots to understand the
   distribution, trends, and seasonality in the data.

4. Data Cleaning: Address any missing or erroneous data. This might involve imputing missing
   values, handling outliers, or correcting errors.

5. Feature Engineering: Create new features that might be useful for analysis or prediction.
   For example, you could create moving averages or lag features.
   
6. Statistical Analysis: Perform statistical tests to investigate relationships between
   variables or to test hypotheses.

7. Correlation Analysis: Use correlation matrices or scatter plot matrices to identify
   relationships between variables.
-------------------------------------------------------------------------------------------   
##  5. Data Visualization
For data visualization of the TCS dataset, incorporate various Python libraries such as Matplotlib, Seaborn, and Plotly. Here are some common types of visualizations:

1. Line Plot: Shows the trend of TCS stock prices over time.

2. Histogram: Displays the distribution of TCS stock prices.

3. Box Plot: Visualizes the distribution of TCS stock prices, highlighting the median,
   quartiles, and outliers.

4. Lag Plot: Shows the specific trend indicate that each data point is strongly correlated 
   with its lagged values.

5. ACF & PACF: The pattern in the autocorrelation plot suggests positive autocorrelation at
   small lag values which decreases as lag value increases. For the partial autocorrelation
   plot it suggests the suitability of an autoregressive model with a lag order of 2.
   

## 6. Feature Extraction    


   

   




