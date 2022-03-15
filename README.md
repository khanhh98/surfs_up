# surfs_up
## Overview of the analysis
### Purpose
  - Create analysis report about temperature trends in order to help W. Avy open a new surf shop in Oahu
  - Getting more insights from the weather data specifically on June and December 
### Analysis and Challenge
  - The Analysis has multiple statistics metrics for June and December data drawn from SQLite
  - The challenge is filtering the right data especially in this case we need to get temperature data from only June and December
### Results
  - The minimum temperature metrics has the huge different which is 64F for June but 56F for December
  - The 25th percentile for June temperature is 73F while December data shows 69F
  - The maximum temp on December is 83F compare to 85F on June
### Summary
  - Aside from the weather data, I also gather rain precipitation for June and December as well
  - From the result metrics, we can see that the temperature tend to be warmer on June. However the weather temperatures on December are not that far away from June temperature with almost the same standard deviation as well as 50th percentile and 25th percentile data point
  - About rain precipitation: base on the data table, we can clearly see that rain is less expected on June than on December. Also, the rain thickness on June is 50% less than on December
  - With all available insight I can draw from the data especially with the weather, I can conclude that there is not much difference for temperature on June and December which suggests that Avy could potentially open the shop all year round
  - We should find the optimal location for the shop by getting queries from weather temperature such as query specific statistic metrics for each station. Once we get that information, we will know which station gets the most sunlight with the least raining precipitation. Hence, Avy can maximize the new venture
