# Madrid Air Quality Analysis & Forecasting

* This dataset is created in the Madrid’s City Council Open Data website. It contains in a practical format 18 years (2001-2018) of daily and hourly data.

* Reformatted the structure of the dataset using forecast, tidyverse, ggplot2, and xts libraries from R

* Choice of the variables (Particles smaller than ten μm (PM10), Ground-level Ozone (O3), Nitrogen dioxide (NO2)) which are core pollutants based on airqualitynow.eu

* Used the function auto.arima from the forecast library to generate our prediction model, the output returns an ARIMA model with the best set of hyperparameters to fit the data.
