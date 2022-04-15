# Time-Series-101

Below are instructions to implement in in your local system using a separate development environment using the [Conda](http://conda.pydata.org/docs/index.html) package management system which comes bundled with the Anaconda Python distribution provided by Continuum Analytics.

### Step 1:
[Fork and clone](https://github.com/siddharthksah/Time-Series-101) a copy of this repository on to your local machine.

### Step 2:
Create a `conda` environment called `time-series` and install all the necessary dependencies, the environment.yml file is uploaded in the repo for ease:

    $ conda env create --file environment.yml
    
### Step 3:
Install the extra dependencies, it is not required but helps in making sure the jupyter notebook is running in the right conda env:

    $ conda install nb_conda

### Step 4:
Activate the `time-series' environment:

    $ source activate time-series

To confirm that everything has installed correctly, type

    $ which pip

at the terminal prompt. You should see something like the following:

    $ ~/anaconda/envs/time-series/bin/pip

which indicates that you are using the version of `pip` that is installed inside the `time-series` Conda environment and not the system-wide version of `pip` that you would normally use to install Python packages.

### Step 5:
Change into your local copy of the this repo:

    $ cd Time-Series-101

### Step 6:
Start the notebook:

    $ jupyter notebook
    
A guide on time series analysis

1. Introduction to date and time
1.1 Importing time series data
1.2 Cleaning and preparing time series data
1.3 Visualizing the datasets
1.4 Timestamps and Periods
1.5 Using date_range
1.6 Using to_datetime
1.7 Shifting and lags
1.8 Resampling
2. Finance and Statistics
2.1 Percent change
2.2 Stock returns
2.3 Absolute change in successive rows
2.4 Comaring two or more time series
2.5 Window functions
2.6 OHLC charts
2.7 Candlestick charts
2.8 Autocorrelation and Partial Autocorrelation
3. Time series decomposition and Random Walks
3.1 Trends, Seasonality and Noise
3.2 White Noise
3.3 Random Walk
3.4 Stationarity
4. Modelling using statsmodels
4.1 AR models
4.2 MA models
4.3 ARMA models
4.4 ARIMA models
4.5 VAR models
4.6 State space methods
4.6.1 SARIMA models
4.6.2 Unobserved components
4.6.3 Dynamic Factor models

Facebook's Prophet Time Series Library --

Hourly Time Series Forecasting using Facebook's Prophet
Data
EDA
Train/Test Split
Simple Prophet Model
Compare Forecast to Actuals
Look at first month of predictions
Single Week of Predictions
Error Metrics
Adding Holidays
Error Metrics with Holidays Added
Compare Models Just for Holiday Dates
Error of all Holidays
Identify Error by holiday
Plot Error of Each Forecast
Data Cleaning


Based on this [Kaggle Notebook](https://www.kaggle.com/code/thebrownviking20/everything-you-can-do-with-a-time-series/notebook) and [this](https://www.kaggle.com/code/robikscube/time-series-forecasting-with-prophet/data)
