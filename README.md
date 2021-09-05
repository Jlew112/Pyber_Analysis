# Pyber_Analysis
Analyzing Pyber and displaying results in MatPlotLib

## Overview
I was tasked with the goal of creating visualiztions of the ride and driver data for Pyber, a ride sharing app. We have been given a pair of data sets, which were combined into a single dataframe in order to run a practical analysis.

The cities were designated as either Urban, Rural, or Suburban, so we have built graphs in order to show the statistical difference.

## Graphs
First, we created a Bubble scatter plot that shows the Average Fares against the number of rides.
![alt text](https://github.com/Jlew112/Pyber_analysis/blob/main/analysis/Fig1.PNG)
As you can see, there is a clear ride volume advantage in the Urban areas, but that is to be expected given the population.
It would appear that the average fares are generally higher in the rural areas, but thats to be expected given the longer distances that need to be taken.

Second, we created a Box and Whisker plot to show the number of rides in each of the city types.
![alt text](https://github.com/Jlew112/Pyber_analysis/blob/main/analysis/Fig2.PNG)
outside of 1 cities outlier, it would appear that the data given all lies within the reasonable quartiles.

Third, We wanted to check the driver numbers for each city type. Also with a Box and Whisker
![alt text](https://github.com/Jlew112/Pyber_analysis/blob/main/analysis/Fig4.PNG)
Clearly, there are more drivers available and willing to work in the Urban areas, which makes sense given the population and ride volume there.

Next, we broke down the total fares by city type with a pie chart.
![alt text](https://github.com/Jlew112/Pyber_analysis/blob/main/analysis/Fig5.PNG)
- Urban 62.7%
- Suburban 30.5%
- Rural 6.8%
Given the volume of riders available in Urban areas, it would make sense to see the breakdown above.

We also broke down the total rides by city type.
![alt text](https://github.com/Jlew112/Pyber_analysis/blob/main/analysis/Fig6.PNG)
- Urban 68.4%
- Suburban 26.3%
- Rural 5.3%
Its telling that Rural and Suburban cites are able to provide a larger portion of the fares with a smaller number of rides, but as we saw the average fares were higher in those areas, its nice to see some consistency.

Finally, we can see the driver numbers per city type
![alt text](https://github.com/Jlew112/Pyber_analysis/blob/main/analysis/Fig7.PNG)
- Urban 80.9%
- Suburban 16.5%
- Rural 2.6%
Relative to the total rides, there is a clear saturation of drivers in the urban market. Its helpful to be able to see this visually.

## Results and Recommendations
The graphs tell all. As we can see, there is a disparity in the driver to ride ratio in suburban and rural areas. I would recommend advertising to drivers in those areas so that you can capture more of those high fare rides. Since more rides are needed in the Urban areas, advertise to the riders in those areas to try to fix the ride/driver ratio.
