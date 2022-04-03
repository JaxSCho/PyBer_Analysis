# PyBer Analysis
## Overview of Project
### Purpose

Using Pyber's rideshare data from January to early May of 2019, we created informative visualizations for the CEO, V. Isualize, with Omar's help. This report will summarize how the ride-sharing data differs by city type (i.e., urban, suburban, and rural), particularly the total weekly fares over time for each city type. Based on the results, decision-makers at PyBer can be better informed and help improve access to ride-sharing services and determine affordability for underserved neighborhoods in various city types. 
## Results

The following analysis presents the differences in ride-sharing data among the different city types.
### Ride-Sharing Summary By City Type

To generate a summary DataFrame of PyBer's rideshare data from January to early May of 2019 by city type, we used [Pandas in Python via Jupyter Notebook](/PyBer_Challenge.ipynb). Figure 1 displays the total number of rides, the total number of drivers, the total fares, and the average fare per ride and driver by city type.

![image](https://user-images.githubusercontent.com/99936542/161407148-fc9c8e3c-62c8-40bd-bd2c-6683fed1cb1d.png)

<b>Fig.1 - Ride-sharing Summary By City type </b>

From this summary, it is evident that urban cities represent the most significant volume of rides and drivers, resulting in higher total fares for rides when compared to suburban and rural cities. The total number of rides and drivers seem to be highly correlated to the population density of a city type (i.e., urban areas have a higher concentration of individuals when compared to suburban or rural areas).
- The total number of rides in urban cities is about 3 and 13 times greater than in suburban and rural cities, respectively. 
- The total number of drivers in urban cities is about 5 to 31 times greater than suburban and rural cities, respectively.
- The total fare of rides in urban cities is about 2 to 9 times more than in suburban and rural cities, respectively.

Despite urban cities having the largest share of the total number of rides, drivers, and fares compared to suburban and rural cities, the average fare per ride and driver are considerably higher in suburban and rural areas compared to urban areas.
- The average fare for rides in rural cities is about $10 and $4 more per ride than in urban and suburban cities, respectively.
- The average fare for rides in rural cities is about $39 and $16 more per driver than in urban and suburban cities, respectively.

 The higher average fare per ride and driver in rural areas could result from ride distance and driver demand. Places of interest in rural cities may be more spread out, leading to longer trips. The relative demand for drivers (i.e., lower supply of drivers in rural areas compared to other city types) may push riders to accept higher fares. Conversely, shorter trips and a greater supply of drivers in urban areas may explain the lower average fares per ride and driver.

### Total Fares By City Type

We also examined the total weekly fares by city type for the first four months (January - April) of 2019 (See Figure 2). An apparent observation is that there is no overlap in total fares among the city types. Overall, urban cities invariably had the highest total fares, ranging from $1,661.68 to $2,470.93, followed by suburban cities, which ranged from $721.60 to $1412.74). Overall, rural cities had the lowest total fares, ranging from $175.14 to $501.24.

All city types experienced a peak increase in total fares during the third week of February 2019. Urban cities, in particular, had multiple peaks in total fares during March 2019; other city types did not experience such drastic fluctuations. By April 2019, total fares trended upward in suburban cities while the other city types encountered the inverse. 

![PyBer_fare_summary](/Analysis/PyBer_fare_summary.png)

<b>Fig.2 - Total Fares by City Type</b>

## Summary

Based on the results, below are three business recommendations to the CEO for addressing any disparities among the city types.

1. **Focused recruitment of suburban and rural drivers** - On average, suburban and rural riders pay considerably higher fares than urban riders (about $7 to $10 more per ride). Therefore, PyBer would be more affordable for underserved neighborhoods in urban cities vs. suburban or rural cities. Increasing the number (i.e., supply) of drivers can improve access to PyBer ride-sharing services and lower the distribution of rides per driver, lowering fares.

2. **Increase fares in urban cities** - Overall, urban riders and drivers are interested in ride-sharing services since the urban cities by far provide the largest share of rides, drivers, and fares in PyBer. Therefore, increasing fares can benefit urban drivers (i.e., increase the average fare per driver) and provide additional revenue channeling into ventures where ride-sharing services can be more accessible and economical for underserved neighborhoods.

3. **Understanding the context of peaks in weekly fares** - All city types experienced a peak increase in total fares during the third week of February 2019. Therefore, further inspection of data relevant to when particular events occurred (i.e., holidays, marketing efforts, etc.) that coincide with peaks in weekly fares may reveal similar characteristics where total fares can be maximized. 
 
## Resources
- Data Sources: city_data.csv, ride_data.csv
- Software: Python 3.7.6, Jupyter Notebook 6.4.5