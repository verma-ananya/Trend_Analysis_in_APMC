# Trend_Analysis_in_APMC

## Project Aim
The aim is to understand trends in APMC (Agricultural produce market committee)/mandi price & quantity arrival data for different commodities in Maharashtra.

###  Objective
>*	Test and filter outliers.
>*	Understand price fluctuations accounting the seasonal effect
  >   * Detect seasonality type (multiplicative or additive) for each cluster of APMC and commodities 
  >   * De-seasonalise prices for each commodity and APMC according to the detected seasonality type>
>*	Compare prices in APMC/Mandi with MSP(Minimum Support Price)- raw and deseasonalised
>*	Flag set of APMC/mandis and commodities with highest price fluctuation across different commodities in each relevant season, and year.

### Libraries used
* Python
* Statsmodels
* Matplotlib, Seaborn
* Pandas, Numpy

### Task-1 
**Test and Filter Outliers**
* the output file is saved in 
  * CMO_MSP_Mandi_filtered.csv
  * Monthly_data_cmo_filtered.csv
