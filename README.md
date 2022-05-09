# PyBer_Analysis
## Project Overview
The purpose of this ananlysis is to create a summary DataFrame of the ride sharing data by city type using Python and knowledge of Pandas.  From this information we then use Pandas and Matplotlib to provide a graph to vizualize the total weekly fares for each city type. 
## Results 

![Pyber_df](https://user-images.githubusercontent.com/103154070/167339971-58a48d1a-f001-4774-a4ae-3bdb36864266.png)

Based on the DataFrame we created to analyze the outcomes of the ride sharing data by city type we have come to a few conclusions.
#1. Urban cities had the highest number of drivers and rides provided, however the average fare made per driver was the lowest amoungst the other city types.
#2. Rural cities had the least amount of drivers and rides, however the driver's were averaging $55.49 per fare.
#3. In suburban cities fares had an average of $30.97, which lay in the middle ground when compared to other city types.
### Summary

![PyBer_fare_summary](https://user-images.githubusercontent.com/103154070/167339989-aa4a4ea7-2fee-478f-a9f1-73321dcd60f0.png)

Based on the graph data we can see the total fare by city type from January to April of 2019. In the timespan, the total fares per city type remained linear with Urban cities with the highest, Suburban citites in the middle and Rural cities with the least.  Between March and April there were some noticable fluctuations on the total fare per driver.  I would recommend taking a look into any factors that may have contributed to this.  Do we know if there were any special occations/events occurring when there were peaks in total fares per driver? Since the placement of the city types remains consistent, I would recommend creating a DataFrame that would also include the average number of miles per fare.  I would also recommend increasing the amount per fare in rural areas to accommodate for the lower amount of drivers that are available. 
