# AAPL Stock Data Analysis

## Project Overview

This project performs **data cleaning, analysis, and visualization** on Apple (AAPL) stock market data using Python.

The project analyzes stock prices, trading volume, daily returns, and identifies unusual trading volume days.

##  Objectives

* Load and inspect the AAPL stock dataset
* Clean and prepare the data
* Convert dates into proper datetime format
* Analyze Open, High, Low, Close, and Volume values
* Calculate price difference and daily return
* Visualize trading volume trends
* Detect anomalous trading volume days
* Analyze the distribution of daily returns
* Calculate mean, variance, and standard deviation

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab
* CSV Dataset

##  Dataset

The project uses an **AAPL stock dataset** containing:

* Date
* Open
* High
* Low
* Close
* Volume

The dataset is loaded using Pandas and cleaned before analysis.

##  Data Processing

The following data preparation steps are performed:

1. Convert the `Date` column into datetime format.
2. Convert stock price and volume columns into numeric values.
3. Remove rows containing missing values.
4. Sort the data based on date.
5. Select the required columns for analysis.

##  Analysis Performed

### 1. Price Delta

The difference between the closing price and opening price is calculated:

`Price_Delta = Close - Open`

### 2. Daily Return

The daily return is calculated using:

`Daily Return = ((Close - Open) / Open) × 100`

These calculations help understand the daily movement of the stock price.

### 3. Trading Volume Analysis

A line chart is used to visualize the trading volume trend over time. The project also calculates the average trading volume.

### 4. Anomaly Detection

Unusual trading volume days are detected using:

`Anomaly Limit = Mean Volume + (2 × Standard Deviation)`

Days with trading volume above this limit are identified as anomalous days.

### 5. Daily Return Distribution

A histogram is used to visualize the distribution of daily returns. The project calculates:

* Mean Return
* Variance
* Standard Deviation

##  Visualizations

The project generates:

* Trading Volume Trend
* Trading Volume with Anomaly Limit
* Daily Return Distribution

##  Output

After cleaning and processing, the final dataset is saved as:

`AAPL_cleaned.csv`

The cleaned dataset contains the processed stock data along with the calculated `Price_Delta` and `Daily_Return` columns.

##  How to Run

1. Open the project in **Google Colab** or a Python environment.
2. Upload the AAPL dataset.
3. Run the Python code step by step.
4. View the generated statistics and visualizations.
5. The cleaned dataset will be saved as `AAPL_cleaned.csv`.

##  Project Author

**Mathusoothanan**

---

