# PyBer Analysis
Module 5 challenge - Deliverable 3.

## Resources
- Data Source: ride_data.csv, city_data.csv
- Software: Python 3.7.13, Conda 4.14.0, Jupyter Notebook, Matplotlib 3.5.1

## Overview of the Analysis

### Purpose
After being hired as a data analyst for PyBer, a ride-sharing company, we were asked by the CEO V. Isualize, to do an exploratory analysis on the relationship between the type of city and number of drivers and riders, as well as the percentage of total fares, riders, and drivers by the type of city. After completing the first assignment we were then tasked with a new analysis to obtain the total rides, total drivers, total fares, average fare per ride, and average fare per driver for each city type. We then created a multi-line graph to visualize the total weekly fares by city type. The analysis will be used to show how the data differed by city type and how these differences can be used by decision-makers at PyBer to possibly improve ride-sharing services. 

## Results

### Differences in ride-sharing data among the different city types

![PyBer Summary Table](https://github.com/DaniliukK95/pyber_analysis/blob/main/analysis/pyber_summary.png)

This table shows the summary data frame created in this analysis. It shows the total rides, total drivers, total fares, average fare per ride, and average fare per driver of each city type. We will be referring to these numbers. 
- The expected differences between the city types based off the definition of each (urban, suburban, rural) is the total number of rides and drivers. We can expect to see urban cities having the greatest number of rides and drivers since the population is bigger. Since rural cities are the smallest in terms of population, it is expected they have the least number of rides and drivers. Looking at the PyBer Summary Table, we can see that rural cities have the least rides and drivers, then suburban has noticeably more, and finally urban cities have the most. Also using pie charts created in the initial analysis, we can clearly see these same numbers visually represented. Rural cities have the smallest percentage and urban cities have the highest percentage. The pie charts represent the total rides and total drivers respectively. 

![% of Total rides by city type](https://github.com/DaniliukK95/pyber_analysis/blob/main/analysis/Fig6.png)
![% of Total drivers by city type](https://github.com/DaniliukK95/pyber_analysis/blob/main/analysis/Fig7.png)

- An interesting difference between the columns of total rides and total drivers is that in urban cities, there are actually more drivers, than the number of rides for the data collected. In rural and suburban cities, the number of drivers is less than the number of rides. 
- Based off the differences we just addressed, it can also be inferred that with a higher population, more business can be generated. Volume can play a huge factor in business. This can be seen in the total fare column of the PyBer Summary Table. Again, the same trend follows with rural cities having the smallest total fares, and urban cities having the highest total fares. The pie chart below can visualize this information much like the previous pie charts.

![% of Total fares by city type](https://github.com/DaniliukK95/pyber_analysis/blob/main/analysis/Fig5.png)

- The differences that aren’t so obvious are on the averages that we calculated in the last two columns. First, we can see that the trend is reversed, where the average fare in both columns actually decreases as the city type increases in population size (rural to urban). There are massive differences between the city types when it comes to the average fare per driver. There is about a $16.00 difference between rural and suburban drivers, and about a $39.00 difference between rural and urban drivers. The rural drivers are getting less volume overall but a higher payout on average. When we look at the average fare per ride column, we can see that this matches the average fare per driver columns trend. As we decrease in the city’s population, the fare per ride increases. The average fare per ride in rural cities is about $10.00 more than urban cities. 
- By looking at the multi-line graph below that shows the total fare by city type per week, we can see that urban areas have about eight times more total fares per week than rural areas, and about two times more total fares per week than suburban areas. 

![PyBer Fare by Weeks Multi-Line](https://github.com/DaniliukK95/pyber_analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary

### Three recommendations to address disparities among the city types
One recommendation that could address the differences in the city types would be to adjust the fare rate in the city types. With the data it is clearly seen that rural cities have the highest average fare rate. This could be a huge influence on the customer to look for other alternative methods to get around like public transportation, other transportation services like private taxi companies, or even investing in their own transportation vehicle. 
The second recommendation I have would be to adjust the drivers available for city types. For example, in the urban cities, we have seen that there are far more drivers than rides in the data. We cannot force people to use the ride-sharing services, but we can affect the number of drivers that are allowed to work for the ride-sharing app. Decreasing the number of drivers in urban areas could help increase the average fare per driver. Research would be needed to see if decreasing the number of drivers would affect the number of rides that are generated. But from the data it seems that there are too many drivers overall in urban areas. 
The final recommendation I have is to focus on any method to increase the use of this app. Whether it’s more advertising, collecting data on why people choose not to or to ride with PyBer, using other marketing methods like a rewards system or subscription to help reduce the fare for those areas with higher fares, etc. By finding a way to increase the number of customers using this app, this will increase the revenue and will allow room to change things like the fare rate, the drivers allowed to be hired, and other future additions like the availability of automated cars.
