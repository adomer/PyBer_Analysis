# PyBer_Analysis

## Overview of the analysis:
This analysis was done to visualize different fares by the types of city for PyBer. Pandas and Matplotlib were used to create a dataframe, then visualize this dataframe with a line graph. 

## Results:
From the analysis a few things were identified. 
  - Ride sharing increases based on population density as expected. Rural cities had only 8% of the total rides that urban cities had with 125 rides in 2019 compared to urban cities' 1,625 rides. 
  - This higher demand of rides came hand in hand with number of total drivers, as rural cities only had 78 drivers, suburban cities had 490 drivers, and urban cities had 2,405 drivers. 
  - Rural cities had only 3% of the drivers that urban cities had despite having 8% of the total rides which likely is a result of more people in urban settings turning to ridesharing as an alternate means of income. 
  - The fare structure is flipped when calculating average fare per ride or driver, with rural cities drastically leading both suburban and urban cities. This is likely due to a lower availability of drivers, paired with an increased travelling distance to reach desired places in a rural setting vs. an urban setting. 
  - The highest volume of fares seems to occur around March, which is likely a result of tempereatures increasing, leading to people travelling more. 

The analysis and breakout of the fare summary can be seen below.

![DataFrame](https://user-images.githubusercontent.com/64291905/143790624-7b7c3798-9c20-4d69-b342-e0404ee9a2df.PNG)

![Pyber_fare_summary](https://user-images.githubusercontent.com/64291905/143790609-94e9f884-520e-4c87-b466-14514b2c4277.png)

## Summary:
Based on these results I have the following recommendations:
  - Rural cities should be targeted for increasing their amount of drivers. By doing so, average fares per trip would decrease which may lead to an increase in people using PyBer's service. There may be people who opt out of using PyBer due to increased wait times as a result of driver's being preoccupied with other trips. This is reinforced by the average fare per driver exceeding the average fare per ride within rural cities.
  - Suburban cities offer a large market to be tapped into. Suburban cities presented 49% of the fares that the urban cities did in the same time frame, but while operating at 38% of the total rides. This indicates there are either not enough drivers, or people are willing to pay more to travel within the city. Drivers should be increased within suburban areas to match as they have only 20% of the driver availability that urban cities have. This is backed up by the average fare per driver exceeding the average fare per ride within suburban cities.
  - Urban cities may have too many drivers in total. There's a ratio of 1.48 driver to every ride within urban areas, so the CEO should either focus on creating an incentive to push urban drivers to suburban areas, or increase advertising to increase total number of rides within urban areas. This is reflected by urban areas being the only cities to have a lower average fare per driver when compared to the average fare per ride. Money is being lost with the excess amount of drivers compared to the amount of rides.
