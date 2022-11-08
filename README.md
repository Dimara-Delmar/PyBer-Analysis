# PyBer Analysis

## Overview

### Purpose
Pyber is a Python-based ridesharing app company that wants us to perform an analysis on two large CSV files using visualizations to describe the rideshare results. The purpose of this analysis is to create a DataFrame of the ride-sharing data based on the three given city types: Urban, Suburban, and Rural. 

## Resources
- Data Source: city_data.csv and ride_data.csv
- Software used: Python 3.9.7, Jupyter Notebook 6.4.12, Matplotlib and Pandas 1.3.5

## Results

The chart below visualizes the summary statistics of the ride-share data by urban, suburban, and rural cities. 

<img width="439" alt="PyBer_summary_df" src="https://user-images.githubusercontent.com/108738297/200502855-565da6db-97f7-4f8f-97d5-f8d39aa54a44.PNG">

The graph below depicts the total fare cost by urban, suburban, and rural cities during the month of January to April. 
 
 ![PyBer_fare_summary](https://user-images.githubusercontent.com/108738297/200502897-fb1f185e-2143-4c08-8207-279de6c9ffa1.png)

Rural cities have the lowest number of drivers (78), lowest number of total rides (125), and the lowest number of total fares ($4,327.93) while having the highest cost of fares per ride ($34.62) and highest average fares per driver ($55.49). 

Urban cities have the highest number of drivers (2,405), highest number of total rides (1,625), and the highest cost of fares per ride ($39,854.38) while having the lowest average fares per driver ($24.53) and lowest average fares per driver ($16.57). 

Unlike the other two results, Suburban cities sit in the middle of the graph with balanced results in every field. When compared to Rural and Urban cities, Suburban cities have no significant factors that fluctuate the data. Driver count (490), total ride count (625) and total fares ($19,356.33) results in middling ride fares ($30.97) and driver fares ($39.50).

## Summary

Looking at this visualization of the data, I might suggest a few changes to make the results more even across the board.

1)	To address the disparities between the rural and urban city fare prices per ride, the CEO of Pyber may want to consider lowering the fare cost in rural cities and slightly raising the cost in Urban cities. There are less people living in rural areas and even fewer people who might be willing to pay for the higher fare prices when compared to the highly populated areas of an urban city there may be more people still willing to pay for higher fare prices. 

2)	Rural cities also have very few drivers, making the fare per driver rate much higher than in both suburban and urban cities. To balance this, it may be beneficial to introduce more drivers in rural cities and sending out less drivers in urban cities.

3)	To further balance the data, I would suggest finding a middle ground between each city type’s ride count, driver count, and fare cost to influence the average ride costs and driver costs in the same way the suburban city results are. Finding that balance between urban and rural communities can improve fare costs, driver costs, and improve income. 
