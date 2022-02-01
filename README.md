# Time-Series-Analysis
Time Series Analysis using statistical methods like ARMA/ARIMA models and statistical tests like ACF/PACF

## About the dataset
This dataset contains of the list of seats booked of an airplane company over the years 1940 - 1960.
Using statistical tests and techniques on the dataset, we transform the existing data and train it to a model for the future predictions of the seats in the upcoming years.

## Steps Involved

### Data Engineering
First the data must be converted such that we understand the data.
Thus, we convert the string dates into datetime format using pandas and use them as index to access the number of seats purchased on that particular date.

### Converting data into useful form
For time series analysis, the data which mustt be used should be stationary. For this reason, we must check if the data we have is stationary or not. In case the data is not stationary, we must convert the data into stationary data without much of the data information being lost.
For this, we first check if the data is stationary. We find out that the data is not stationary by using the statistical testing.

So, the next step is .........

### Converting the data into stationary form


### Selecting optimal parameters for our model


### Ploting our model results 


### Evaluating our model results

