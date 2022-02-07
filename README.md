# An Analysis of PyBer Rideshare data

## Overview

The purpose of this project was to analyze PyBer's ridesharing data, to gain insights on fare metrics in various cities that Pyber operates in. The analysis includes visualizations to help summarize how the data differs by city type, and how this data can be used to improve decision making at PyBer.

## Results

To help compare ride-sharing data among the different city types, I created this summary:

<img width="613" alt="Pyber_summary_df" src="https://user-images.githubusercontent.com/96550846/152716033-8f0693e3-e3d2-40ca-a1ee-fb6bff7ca97c.png">

The summary highlights several differences among the different city types:
- Rural cities have the least amount of rides and drivers, but the highest average fare price.
- Urban has the highest rides and drivers, and the lowest average fair price.
- Suburban cities fall in the middle in each category.
- Urban cities are the only city type to have more total drivers than total rides.
- The average fare per driver is also the lowest in Urban cities

To see how the total fare fluctuates from week to week for each city type, I created this line chart:

![TotalFarebyCityType](https://user-images.githubusercontent.com/96550846/152716062-0305cd44-3a3e-4507-a787-f70dd5cfa0d1.png)

The urban line was lowest at the start of January, and peaked during late February and early March. It also has several dips and spikes during March. The suburban line was also lowest at the start of January and peaked in late February. The rural line at the bottom has a low point during January and again in February, with its peak at the start of April.

## Summary

This analysis can be used to make business recommendations for PyBer's decision-makers. The first recommendation is to increase the amount of drivers in rural and suburban areas to meet the demand. As supply catches up with demand, this may also help bring the average fare per ride down.

The second recommendation is to decrease the amount of drivers in urban cities. With 2,405 drivers and only 1,625 rides, there is a surplus of drivers. This can also help increase the average fare per driver, as it is currently significantly lower than it is in rural and suburban cities.

The third recommendation is to increase focus and investment in urban cities. Despite having the lowest average fare, urban cities bring in twice as much revenue as suburban, and over 9x more than rural cities. Urban cities contain the most potential to increase profits at PyBer.
