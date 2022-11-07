# PyBer_Analysis

## Overview of the Analysis

Using Pandas libraries, the Jupyter Notebook, and Matplotlib, a variety of visualizations will be created that showcase the relationship between the type of city and the number of drivers and riders, as well as the percentage of total fares, riders, and drivers by type of city. This will provide insight on how to improve access to ridesharing services and determine affordability for underserved neighborhoods.

### Project Deliverables

- Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.
- Determine the mean, median, and mode for the following:
    -The total number of rides for each city type.
    -The average fares for each city type.
    -The total number of drivers for each city type.
-Create box-and-whisker plots that visualize each of the following to determine if there are any outliers:
    -The number of rides for each city type.
    -The fares for each city type.
    -The number of drivers for each city type.
-Create a pie chart that visualizes each of the following data for each city type:
    -The percent of total fares.
    -The percent of total rides.
    -The percent of total drivers.
-Create a multiple-line graph that shows the total weekly fares for each city type

## Results

![Summary DataFrame](https://github.com/doliver231/PyBer_Analysis/blob/main/analysis/summary_dataframe.png)

It is clear that urban cities tend to have the most rides and drivers with the cheapest fares per ride and per driver. Suburban cities fall second with higher fares per rides and per driver, but with much less total rides and drivers. Rural cities, which are known to have lower population sizes compared to urban and surburban, are showing the highest average fares per ride and per driver. 

![Total Fare by City Type - Multiline Chart](https://github.com/doliver231/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

Rural cities showed a consistent trend of fares amounts in the time range of January to end of April. Beginning at $187.92 and ending at $191.85, there were few fluctuationsm with notable peaks at the end of Feburary and beginning of April. Both urban and suburban cities displayed similar spiked peaks around the end of February , just like rural cities. Suburban cities fluctuated the most within these four months, starting at $721.60 at the beginning of the year and ending at $1169.04. Urban cities remained with the highest fares in this time period, fluctuating the most in the month of March.

![Bubble Chart](https://github.com/doliver231/PyBer_Analysis/blob/main/analysis/Fig1.png)

There is a negative correlation between the average fares and the total number of rides taken. As we noted earlier in the summary DataFrame, the higher the average fare, the less total number of rides per city. Rural cities tend to showcase the highest average fares and the least number of rides. Urban cities, with higher populations as depicted with the bubble sizes, have the most number of rides and the cheapest average fares. 

![Box and Whisker](https://github.com/doliver231/PyBer_Analysis/blob/main/analysis/Fig2.png)
![% Total Fares - Pie Chart](https://github.com/doliver231/PyBer_Analysis/blob/main/analysis/Fig5.png)
![% Total Rides - Pie Chart](https://github.com/doliver231/PyBer_Analysis/blob/main/analysis/Fig6.png)
![% Total Drivers - Pie Chart](https://github.com/doliver231/PyBer_Analysis/blob/main/analysis/Fig7.png)

When we compare each city type against percentage of total fares, total rides, and total drivers, Urban cities always have the majority of the percentage, as we can see in the pie charts. Suburban cities show the second majority, and rural cities all show less than 10% of every total category.

## Summary

The analysis done on PyBer ridesharing data has been very insightful and can potentially spark changes on how the company allocates its resources. It is clear that PyBer ridesharing is more widely utilized in city types of higher populations, specifically urban areas. Urban areas tend to provide very little parking options for those that use their own vehicles for transportation and they also tend to host more traffic jams. This increases the necessity of public transportation and ridesharing, hence why PyBer receives so much revenue from these city types. Rural and suburban areas have much less population sizes compared to urban areas.

The cost for using PyBer services in rural cities are much greater than the fares of suburban and urban cities. This discourages riders to use the services as a form of common transportation, and makes it almost like a last resort option. Traveling in rural areas is different that other city types, where the distance between destinations are longer, and the amount of drivers are more scarce. This is an important point PyBer needs to take into account. Due to the high number of drivers in urban and suburban areas, the ridesharing trips cost less and are more available to public. Possibly during those weeks of peaking fares for each city type, Pyber can provide what is necessary to maximize revenue, whether it is hiring more drivers, providing more access ridesharing points, and/or adjusting the costs of the rides.
