# Statistical-Analysis-and-Forecasting-of-Solar-Energy
Aim is to analyse solar energy for two study regions of Rajasthan. If possible, we may like to forecast solar energy for next week or even for next month.

Obtain the hourly data for two solar parks in Rajasthan for 10 years.

The data is merged in order of years for their corresponding solar parks.

Look at various terms such as DHI, DNI, GHI, dew point, temperature, pressure, relative humididty, wind speed, etc. Understand which terms/parameters are relevant to solar energy.

We have used GHI data of solar park Rajasthan-1 for time-series analysis.

Data is cleaned and only the relevant features are kept.

Performed several graphical plots or compute various descriptive statistics to understand the DHI, DNI, and GHI data, their correlation, etc.

Performed Auto-Regressive (AR), Moving-Average (MA), Auto-Regressive-Moving-Average (ARMA), Auto-Regressive-Integrated-Moving-Average (ARIMA), and Seasonal-Auto-Regressive-Integrated-Moving-Average (SARIMA) statistical methods on the GHI data for daily/weekly forecasting.

Files Description:-
1) Merging: the hourly data has been merged in order of years
2) ar: Auto-Regressiion applied on merged data
3) dailyarima: ARIMA applied on daily data for 10 years (obtained by converting hourly to daily data)
4) weeklyarima: ARIMA applied on weekly data for 10 years (obtained by converting hourly to weekly data)
5) sarima: SARIMA applied on weekly data for 10 years (obtained by converting hourly to weekly data)
