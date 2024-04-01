trend
seasonality
Residue,error(Noise)

Components of Time Series:
    1) TREND: is a movement to relatively higher or lower values over a long period of time.
    
        uptrend - exibits upper  values
        
        down trend - exibits lower values
        
        when there is no trend - horizontal line or stationary trend
        
    2) SEASONALITY: The repeating patterns or cycles of behaviour over time (fixed intervals)
        Ex: Mangoes sales in summers
    
    3) Noise or Irregularity or Residual: Some random variation that no one can predict
        Ex: floods, Earthquakes

libraries utilized :

import pandas as pd
import numpy as np 
import matplotlib.pyplot as plt
import seaborn as sns
from statsmodels.tsa.seasonal import seasonal_decompose
ad-fuller Test
Dickey Fuller Test
from statsmodels.tsa.stattools import adfuller
from statsmodels.tsa.arima.model import ARIMA
model= ARIMA(train,order=(7,1,7))#random experiment with pdq values

![image](https://github.com/Iqmohan/Time-Series-Forecasting---Air-Passengers/assets/159016465/31bab072-f7b5-481e-995a-c52347c09433)
