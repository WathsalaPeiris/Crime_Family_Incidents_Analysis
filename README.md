# Crime_Family_Incidents_Analysis
The purpose of this analysis to find out if Covid-19 had an impact on Family Incidents in Victoria.\
Technical skills: Python, Pandas, Matplotlib, Jupyter notebook

Content:\
1. Number of Family Incidents within the period from Jan-18 to Dec-22\
  1.1 Cleaning Family Incidents data
  1.2 Analysing Family Incidents data
    1.2.1 Family Incidents Analysis - Part 1 - Depicting Overall Trend
    1.2.2 Family Incidents Analysis - Part 2 - Depicting Seasonal Pattern 
    1.2.3 Family Incidents Analysis - Part 3 - Performing two sided t-test for two populations
      1.2.3.1 Define the two population
      1.2.3.2 Remove Trend Component from the time series - Applying Linear regression
      1.2.3.3 Apply Augmented Dickey Fuller Test to find out if the detrended time series has a stochastic trend
      1.2.3.4 Eliminating stochastic trend - First Differencing method
      1.2.3.5 Apply Augmented Dickey Fuller Test to find out if the detrended and differenced time series is stationary
      1.2.3.6 Check if data supports normality assumption
      1.2.3.7 Perform two sided independent t-test
  1.3 Conclusion on Family Incidents Analysis

References:

Crime Statistics Agency 2022, Data Tables Family Incidents Visualisation Year Ending September 2022, accessed 7 January 2022, https://www.crimestatistics.vic.gov.au/crime-statistics/latest-victorian-crime-data/download-data.
