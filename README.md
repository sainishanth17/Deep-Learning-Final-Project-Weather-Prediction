# Time series project

The goal of this repository is to develop a model for temperature prediction using both classical and modern tools. The classical models including Auto Regression (AR) and Auto Regression Integrated Moving Average (ARIMA) are common for time series modeling. The Long Short Term Memory (LSTM) is a modern tool to deal with time-series data.

The data is available from the ```Keras website Example``` in the time series section [here](https://keras.io/examples/timeseries/) and users can easily download it through url connection specified in the code P01_01_Data part of this repository.

In the EDA part, the data is analyzed to answer the question of whether the temperature data set is stationary or not. This is important from classical modeling (AR and ARIMA) point of view.

Using the LSTM model, the user would be able to analyze the temperature time series data for any number of timestamps in the future while still considering the lags information. Also, the LSTM model or any ML algorithm is able to consider more than one-time series data at the same time for analysis, unlike the classical methods (mostly univariate approch).





## AR and ARIMA modelsl - short term forcasting
<p align="center">
  <img width="2000" src="Figures/AR_GIF.gif" >
  <img width="2000" src="Figures/GIF.gif" >
</p>


<!--
<p align="center">
  <img width="2000" src="Figures/P02_01_EDA_fixing_mean_stationary_windo_[500, 2000, 5000]_T_(degC).png" >
 <img width="2000" src="Figures/P02_01_EDA_fixing_std_stationary_HIST_windo_[500, 2000, 5000]_p_(mbar).png" >
</p>


<p align="center">
  <img width="2000" src="Figures/P02_01_EDA_fixing__stdstationary_windo_[500, 2000, 5000]_T_(degC).png" >
</p>
-->

## AR models at four different lag times - short term forcasting
<p align="center">
  <img width="2000" src="Figures/P03_02_AR_GIF.gif" >
</p>


AR and ARIMA models typically are well for short-term forecasting. The auto regression part of these models
converge to the mean of data for long-term forecasting.


## LSTM model - short term forcasting

<p align="center">
  <img width="2000" src="Figures/P03_02_LSTM_GIF.gif" >
</p>


## LSTM Temperature forecast for 12 hours ahead - Long term forcasting 
<p align="left">
  <img width="500" src="Figures/P03_03_LSTM_Multivariate_LSTM12HoursAhead.png" >
</p>



activate env : [env](https://www.youtube.com/watch?v=8AhIs6yI6Sc&t=324s)
