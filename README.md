# Trend_Analysis_in_APMC

Trend Analysis in Agriculture sector using:
* Time Series Analysis 
* Statistics 
* Decomposition of Time-Series data 
* Data Visualization.

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
* the output files is saved in 
  * CMO_MSP_Mandi_filtered.csv
  * Monthly_data_cmo_filtered.csv
![1](https://user-images.githubusercontent.com/25191363/52253138-235b5a00-292c-11e9-8024-6413a3709065.PNG)
![2](https://user-images.githubusercontent.com/25191363/52253168-484fcd00-292c-11e9-95a5-9f8fc9ea74c4.PNG)

**Outliers in the commodities**

![3](https://user-images.githubusercontent.com/25191363/52253183-5d2c6080-292c-11e9-96e9-1fd3ef77249e.PNG)

### Task-2
**Account Seasonalibility**
* the output files are saved in
  * seasonal_data_analysis.csv
  * seasonality_type.csv
  * deseasonalize_data.csv

**Seasonality type**

![2 1](https://user-images.githubusercontent.com/25191363/52253261-de83f300-292c-11e9-8633-0e388aed8d49.PNG)

**Deseasonalise Prices** 

![2 2](https://user-images.githubusercontent.com/25191363/52253289-fe1b1b80-292c-11e9-8f43-8606beadfc44.PNG)

### Task-3
**Comparing the prices of MSP with raw and deseasonalise prices of the APMC and Commodities cluster**

![4](https://user-images.githubusercontent.com/25191363/52253317-30c51400-292d-11e9-9758-256f2a7f2446.PNG)

### Task-4
**Flag set of APMC and Commodity clusters with highest fluctuations**
* The output file is saved in
  * maximum_fluctuation.csv
  
![5](https://user-images.githubusercontent.com/25191363/52253361-6ec23800-292d-11e9-941f-20c69d4a0339.PNG)
![6](https://user-images.githubusercontent.com/25191363/52253366-71249200-292d-11e9-94a8-1c4ce1e6bf98.PNG)
