# COVID19
Forecasting daily COVID-19 new cases in Qatar

As an example, let’s look at a time series of the daily COVID-19 cases in Qatar.

We will be using Prophet. Prophet is open source software released by Facebook’s Core Data Science team.

Prophet is a forecasting procedure implemented in R and Python. It is fast and provides completely automated forecasts that can be tuned by hand by data scientists and analysts.

Prophet follows the sklearn model API. We create an instance of the Prophet class and then call its fit and predict methods.

The input to Prophet is always a dataframe with two columns: ds and y. The ds (datestamp) column should be of a format expected by Pandas, ideally YYYY-MM-DD for a date or YYYY-MM-DD HH:MM:SS for a timestamp. The y column must be numeric, and represents the measurement we wish to forecast.

