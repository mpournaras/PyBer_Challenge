# PyBer_Challenge

## Overview:

With this project I was tasked with using Python scripts and Pandas to creat a summary dataframe of the PyBer ridesharing data by city type.

Then using Pandas and MatPlotLib I was tasked with creating a graph showing weekly fares by city type.

We will use this city type data and their differences to back data-driven decisions at PyBer

## Results:

### What can we glean from the data? 

By grouping fares by city type we are able to see quite a few metrics that could be acted upon at Pyber. Below is a summary dataframe for city types followed by a line chart showing fares by type for the first 4 months of 2019. We are able to see a few trends with this data.

Fig 1: Summary Data Frame:

![file](https://github.com/mpournaras/PyBer_Challenge/blob/main/Resources/PyBer_Type_Summary.png)

Fig 2: Fares by City Type for Jan-Apr 2019:

![file](https://github.com/mpournaras/PyBer_Challenge/blob/main/Resources/Pyber_fare_summary.png)

### Total Rides by City Type:

As we can see in figure 1, the total number of rides is heavily skewed to one city type: urban. It is almost 3x the total of suburban rides and 13x the total of rural rides 

### Total Drivers by City Type:

Again, as we can see in figure 1, the total number of drivers is heavily skewed towards urban city types. It is 5x the amount of suburban drivers and about 30x the number of rural drivers. That is an extremely significant grouping.

### Total Fares by City Type:

Once again, the total fares in $USD is skewed towards urban city types. These differences arent as significant but it is not to be ignored. There is a greater picture here that will be addressed in the summary below.

### AVG Fare Per Ride by City Type:

In a slight reversal, depicted in figure 1 we are able to see that the average fare per rides is slightly higher for rural riders. This could be because of longer distances to get to and from city centers.

### AVG Fare Per Driver by City Type:

The biggest surprise here is the average fare per driver being remarkably high for rural drivers. Like the average fare per rider, this could be a combination of fewer rides, and longer rides bringing the average up.

### Fare by Week Per City Type:

In the line graph from figure 2 we are able to see 2 things:
1. The generally higher total urban fares are corroborated in both the summary and the chart. 
2. While they appear to peak in the same areas around March, it is still a larger chunk of the pir to be a driver in urban areas despite its relative volatility,

## Summary:

There are a few business recommendations we can make regarding the fare by city type data provided above.

1) Urban centers are the bread and butter of PyBer. If there is to be a campaign to retain drivers I would focus such efforts primarily on urban drivers. Surge pricing for urban sporting events or a seasonal reduction in fees would be a good start. While relatively easy to replace, highly rated urban drivers are the so-called "VIPs" of PyBer.

2) Provide customer coupons via targeted advertising to rural riders in Januray. For whatever reason ridership is at a low in mid-January. Getting more rural riders connected with drivers could boost revenue and allow those rural drivers to get a few urban customers before returning home. This is a net benefit.

3) Do not spend PyBer funds trying to boost suburban ridership. I believe the drivers are satisfied with above average revenue while riders pay about average fares. These resources would best be spent in recommendations 1 and 2, or saved for other projects.
