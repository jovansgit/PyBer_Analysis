# PyBer_Analysis

Overview of the analysis:
The goal of this project is to perform exploratory analysis on large csv files with data from January to early May of 2019 for a ridesharing company named PyBer.  We wanted to create charts which showcase the relationship between type of city, the number of drivers/riders, as well as the % of total fares.  It's important for us to help Pyber improve their access to ride sharing services and as well as analyze ride sharing affordability in underserved areas.  We will present our findings to the CEO of PyBer.  We will perform our analyis using our Python skills in addition to our knowledge of Pandas and Matplotlib.


In our analysis we will present a summary DataFrame by city type as well as a multiple-line chart of total fares for each city type.



Results:
We see that the type of city has a direct correclation to the average fare per ride as well as the average fare per driver.

Urban city's have the lowest average fare per rider with $24.53, followed by suburban cities with $30.97, while Rural are last in our analysis with $34.62.  What's interesting is that Urban cities are the only type where the average fare per ride is more that the average fare per driver.

For the average fare per driver we see that Urban cities are the lowest with $16.57, followed by Suburban cities with $39.50, followed by Rural cities which have $55.49.


The Total Rides, Total Drivers, and Total Fares all show the same correclation as Urban cities have the most followed by Suburban and then Rural areas.

What's interesting is that Urban cities have nearly 800 more total drivers than rides. With Rural and Suburban areas we see that they have more rides than drivers.


![PyBer_Summary](/PyBer_Analysis/analysis/PyBer_Summary_df.png)



![PyBer_fare_summary](/PyBer_Analysis/analysis/PyBer_fare_summary.png)



Summary:
We have a few business recommendations we would like to address regarding some disparities among the city types. 
  
  We recommend putting a focus on collecting more data for our dataset such as the satisfaction score or riders/drivers by city type and the miles per trip as it appears drivers in urban areas make signigicantly less per trip. 
  
  We recommend increasing marketing for riders in Urban Areas as we have the drivers to service those customers and it is the only area where we are charging more for the rides on average than we are paying the drivers.
  
  We need to explore if an increase in Total Drivers would decrease the average fare per driver as it appears to have some correlation.  If it is not possible to decrease the average fare per driver focusing on rural and suburban areas may not be sustanable unless we increase the average fare per ride in these areas.
  




