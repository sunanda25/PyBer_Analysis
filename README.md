# PyBer_Analysis
## Overview
A data analyst for the ride-sharing app company, PyBer was given the assignment to perform exploratory data analysis using city and ride information. Using Pandas and Matplotlib library, visualizations for data are shown for:
- Statistics for the number of rides by city type
- Statistics for the number of drivers by city type
- Statistics for the fare by city type
- Percentage of total fares by city type
- Percentage of total rides by city type
- Percentage of total drivers by city type 

After presenting a report with the above visualizations to the company CEO, he was impressed and asked to create a summary DataFrame of the ride-sharing data by city type. A multiple-line graph showing total weekly fares for each city type was also requested.

## Results
### Summary DataFrame of the Ride-Sharing Data by City Type
A summary DataFrame of the ride-sharing data was calculated for Urban, Suburban, Rural city types and are shown as:
- Total Rides
- Total Drivers
- Total Fares
- Average fare per ride
- Average fare per driver

![image](https://user-images.githubusercontent.com/76491891/112694066-16758980-8e58-11eb-89bd-7c268dc6cd2f.png)

#### Differences in Ride-sharing Data for City Types
- There are more rides in Urban areas compared to Suburban and Rural areas. A total of 1,625 rides are recorded in Urban areas whereas only 625 rides in Suburban and 125 rides in Rural areas are recorded.
- The total number of drivers for Urban areas is 30 times higher compared to Rural areas. There are 2,405 drivers in Urban areas whereas only 490 drivers in Suburban and 78 drivers in Rural areas are recorded.
- The Average fare per ride for Rural areas is expensive compared to Urban and Suburban areas. For Rural areas, Average fare per ride is $34.62 whereas for Urban and Suburban areas Average fares per ride are $24.53 and $30.97 respectively.
- The Average fare per driver is 3 times higher in Rural areas compared to Urban areas. For Rural areas, Average fare per driver is $55.49 whereas for Urban and Suburban areas Average fares per driver are $16.57 and $39.50 respectively.

### Multiple-Line Graph Showing Total Weekly Fares for Each City Type
Using the pivot table function in Python, a multiple-line graph is plotted for each city type (Urban, Suburban, Rural) showing weekly fares from Jan 2019 to April 2019.

![image](https://user-images.githubusercontent.com/76491891/112694255-6b190480-8e58-11eb-82ef-e5bebd19f32c.png)

#### Differences in Total Weekly Fares by City Type 
- Total weekly fares for Urban areas are consistently highest followed by Suburban and Rural areas respectively.
- Total weekly fares from Jan-Apr 2019 remained relatively flat for all city types.

## Summary
Following are the 3 recommendations for PyBer CEO:
1.	Decrease the number of drivers in Urban areas. In Suburban and Rural areas, there are more drivers than total rides, whereas Urban areas have less number of drivers than total rides.
2.	Increase the number of drivers in Rural areas to meet the demand of riders. By summarizing the ride-sharing data, the Average fare per ride and average fare per driver is higher in Rural areas which indicate most of the rides are taking place over a longer distance. So, the availability of drivers in rural areas is low.
3.	If fares are determined by peak hours and non-peak hours, there will be an increase in the riders. Minimum fares for non-peak hours can increase the ride count.

