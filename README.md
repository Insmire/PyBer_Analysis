# PyBer_Analysis

<!-- Overview of the analysis: Explain the purpose of the new analysis. -->
## Overview
The purpose of this project is to utilize information from company PyBer's 2019 ride-sharing data to analyze the correlation between city type and the following variables:
1. total rides
2. total drivers
3. averagefare per ride
4. average fare per driver

## Resources
#### Data Source:
city_data.csv, ride_data.csv
#### Software: 
Python 3.7, Anaconda 4.11.0, Jupyter Notebook, Pandas 1.3.5, Matplotlib 3.5.0

<!-- Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. -->
## Results
- Total rides
  - Rural: 125 rides; suburban: 625 rides; urban: 1,625 rides.
  - Rural cities have the lowest number of rides while urban cities have the highest number of rides.
- Total drivers
  - Rural: 78 drivers; suburban: 490 drivers; urban: 2,405 drivers.
  - Rural cities hold the least amount of drivers while urban cities hold the most drivers.
- Total fares
  - Rural: $4,327.93; suburban: $19,356.33; urban: $39,854.38.
  - Rural cities earn the least in total fares every week from January through April 2019 and by the year's end.
- Average fare per ride
  - Rural: $34.62; suburban: $30.97; urban: $24.53.
  - Urban cities earn the least in average fare per ride.
- Average fare per driver
  - Rural: $55.49; suburban: $39.50; urban: $16.57.
  - Rural cities earn the most for average fare per driver.
  - Suburban cities hold intermediate values across various variables including average fare per driver.

A summary dataframe is shown below.
![pyber_summary_df](https://user-images.githubusercontent.com/96349090/152734724-5c068e30-4888-46b0-aee2-63c8bdea2bc3.png)

A multiple-line chart of total fare per week by city type during January through April 2019 is shown below.
![Fig8](https://user-images.githubusercontent.com/96349090/152735529-ca94e07d-5ec8-4f56-bb12-459d0e0217b1.png)

<!-- Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types. -->
## Summary
Based on the results, some potential business recommendations are as follows:
1. Assuming market competition drives down average fare per ride and per driver, PyBer may benefit from lowering fare prices while hiring additional drivers in urban and/or suburban cities to increase yearly rides and therefore yearly sum of fares.
2. The low amount of total rides and total drivers in rural cities may suggest low market demand of rides, low supply of drivers, or a combination of both. If demand of ride was in fact high, then PyBer may be interested in hiring more drivers. If demand was low then the company may require less drivers. 
3. The high average fare per ride and per driver in rural cities may be due to low supply of drivers, high fare price from lower market competition, longer ride time due to longer travel distance, etc. Thus even though rural cities earned the most in average fare per ride and per driver, they earned the least in weekly total fare from January through April and the least by the year's end. Further research would be required to determine the best action forward.
4. Compounding variables may exist that strongly correlate with the variables of interest or become variables of interest. Further research is highly recommended to discover or examine details in market trends.
