# Gasoline-Price-Forecast-R

## In this project, we built time series model to forecast weekly regular gasoline prices in East Coast.
data source :https://www.eia.gov/dnav/pet/pet_pri_gnd_dcus_r10_w.htm

## Analysis:
###  Plotted ACF and PACF to check the auto correlation.
### Used backtest method to compare the mean squareed error(MSE) to assess the accuracy of prediction.
### Appied different window length to find the optimal amount of data to fit each model.
### Implemented Monte Carlo simulations to test the models and computed mean squared error.
##  Found best model (GARCH(2,1)(generalized autoregressive conditional heteroskedasticity))in our study.
