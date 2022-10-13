# Pyber_Challenge

## Overview of the Analysis

This project analyzes ride sharing data by city type: urban, suburban, and rural. Ridesharing is a service that arranges one-way transportation on short notice. Therefore, this technical analysis delves into basic summary statistics and creates graphs that shed light on the differences in the amount of drivers, rides, as well as their fares based on the type of location they are operating out of. The goal of this analysis is to summarize data so PyBer's management team can make more insightful decisions. 

## Results

In this analysis multiple summary data frames were created to illustrate average fares per week, total rides, as well as a multiple line graph to show total fares by city type. Pandas was imported to utilize the groupby() function in order to create a series of data that has the type of city as the index. Then the sum(), count(), and mean() functions were used to find the average fare per driver based on the city.

### Total Rides 

![Total Rides](https://user-images.githubusercontent.com/112028534/195715331-5b687014-5f2b-48cb-b69b-f7db54630ce1.PNG)

As we can see from the table above, Rural areas have the least amount of rides and urban areas have the most rides. This also correlates with the total number of drivers where rural areas have the least amount of drivers and urban areas have more drivers in order to meet the increase in demand. Since the demand for rides is smaller in rural areas and the amount of supply of available drivers is also smaller, rural drivers can charge more per fare. Whereas Urban drivers have to charge less per fare because there is more competition. 

### Fares per Week

![Fares per week](https://user-images.githubusercontent.com/112028534/195716235-ec957832-2350-4757-971e-1fa2a32e6d0f.PNG)

The table above allocates total fares per week based on the location. It's clear that more fares are to be made out of urban areas. In addition, if there is an increase in fares in general all locations saw an increase in their fares for that week. There are also minimal instances where fares per week in a rural area increased but fares and suburban or rural areas did not. 

### Total Fare by City Type 

![Total Fare by City Type](https://user-images.githubusercontent.com/112028534/195714691-f56e6023-68b6-431d-9739-21c5cea45f3c.png)

The graph above also illustrates the total fees per city type. Again it's clear there are more fares in urban areas. It also appears there is more demand for during the end of February and the beginning of April. This could be due to spring break or holidays.

## Summary

Based on the results it is recommended to the CEO that drivers in rural areas should charge more per drive because the competition is lower. Rural drivers' average fare is around $35. Drivers in urban areas should charge less than rural or suburban areas because there is more competition and their drives are more likely to be shorter in duration. The average fare for an urban driver is around $25. Finally, based on the time of the month, especially around holidays it can be expected that drivers in all areas will have an increase in demand; therefore, more drivers should be made available during those times, and higher fares could be charged if there are not enough drivers to meet the demand. 
