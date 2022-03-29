# PyBer_Analysis
## Overview
The purpose of this analysis is to generate ride-sharing data for Urban, Suburban, and Rural city types. This data can potentially be used to make business decisions on how to price rides, allocate drivers, and / or determine hiring needs. Additionally, the fare by city type over the course of a year will help to determine rates during high and low seasons.

## Results
### Total Rides
The total number of rides increases as the population density increases. ie ride count follows: Urban > Suburban > Rural.

### Total Drivers
The total number of drivers increases as the population density increases. ie driver count follows: Urban > Suburban > Rural.

### Total Fares
The total accumulated fare amount increases as the population density increases. ie total accumulated fare follows: Urban > Suburban > Rural.

### Average Fare per Ride
Conversely, the average fare per ride decreases as the population density increases. ie average fare per ride follows: Urban < Suburban < Rural.

### Average Fare per Driver
The average fare per driver decreases as the population density increases. ie average fare per driver follows: Urban < Suburban < Rural.

### Chronological Fare Comparison
For each of the city types, there does not appear to be a high or low season that appreciably stands out.

### Results Summary
The figures below illustrates the data presented above.

![Ride_summary](Pyber_ride_summary_data.png)

![Monthly_summary](Pyber_fare_summary.png)

## Project Summary
Leveraging the data above, the following recommendations are made:
1. If the goal is to mitigate disparities between the city types, the Urban and Suburban rates should be brought up to the level of the Rural rates.
2. Another method to address this would be to hire more drivers for the less populated cities -- this would increase driver supply and lower the demand on each driver, lowering prices.
3. To improve job satisfication, stop hiring in Urban areas until the total drivers to total rides ratio drops below 1. This will increase the rides per driver and increase wages.
