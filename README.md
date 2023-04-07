# Python_master_project_Forecast_Stock_Returns_Using_Firm_Characteristics
The size of Data file is too big so data is fail to be uploaded.
This project follows the paper by Jonathan Lewellen, (2015), “The cross section of expected stock returns”. 
3 models are used to perform 1964-2021 monthly cross-sectional regressions of stock returns and Fama-MacBeth method using characteristics of a firm as the firm’s factor loadings or betas.
Part 1: obtain the time series of each monthly cross-sectional regression estimates(risk premiums) for the entire data set in each model
Part 2: compute the time series averages of the slope estimates and their standard errors. 
Calculate t-test and determine if the slope average is significantly different from zero.
Part 3: perform a prediction of following month’s return using model 3 only with all the characteristics and constant. 
Start with 10 years of the cross-sectional regression outputs using sample from Jan 1970 to Dec 1979. 
Average the monthly risk premium estimates from Jan 1970 to Dec 1979 over the 120 months to form the 10-year averages.
As the 10-year estimation window rolls forward in time to Feb 1970 – Jan 1980, obtain the next stock return forecasts/predictions for Feb 1980, and so on.
Part 4: Analyse the performance of your modeling and backtest the following trading strategy. 
For each month from Jan 1980 to March 2021, if the forecast/predicted return is positive (negative), buy (sell) $1 of that stock. 
Find the annualized trading return rate of such a strategy averaging across all the stocks traded.
Part 5: calculate accuracy rate
Part 6: perform a prediction of following month’s return with significant characteristics. 
