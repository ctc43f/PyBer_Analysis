# PyBer_Analysis

## Overview of Project
The CEO of Pyber has asked us to conduct some exploratory data analysis on rideshare data from three different geographical perspectives, summarize the information into a table that can provide some high-level insights, and visualize the data to help assist with decision making.  Specifically, the CEO wishes to improve access to its ridesharing services and determine affordability for underserved neighborhoods.


### Purpose:
- Aggregate the raw data files into some high-level summary statistics
- Visualize the data to provide insightful visualizations that can help with senior management decision making


## Summary Statistics

Using the provided data of rideshares completed in the first four months of 2019, we get the below set of summary statistics by geography:

![Image 1: Summary DataFrane](/analysis/summary_df.png)

We can see from this chart a few interesting takeaways:
1. Demand outpaces supply in rural and suburban areas.  The number of rides is higher than number of drivers in both cases, which implies many drivers had multiple trips.
2. Average fare per ride is not significantly different among the three categories.  It's hard to say why this is: whereas the distances per ride are likely longer for rural trips, which would normally generate higher costs, the demand is lower overall and would offer a lower rate accordingly.  
3. Urban areas generate the most profit for Pyber, assuming either the revenue generates is per-ride or percentage of fare.  Whereas the CEO might want to serve all areas, there might be less opportunity as you move further away from the city.


## Visualization of Fares by Geography Over Time

The CEO also asked us to provide some useful visualizations with the same data that might help her make decisions on how to increase performance and also to better serve areas.

![Image 2: Total Fare By City Type](/analysis/Fig1.png)

We get some additional insight looking at the data over time:
1. The total fares for urban, suburban, and rural are always ranked in the same order, regardless of time of year (at least for the four months in question).  If we saw the lines cross one another at certain times, it implies there is opportunity for surge or peak pricing within that given geography and time.
2. There is some weekly cyclicality through the week.  For example, the line "wobbles" for Urban in March, implying that demand peaks on the same day of each week and then tapers off, building back up the following week.  Assuming the company doesn't adjust pricing currently for day of week, there might be opportunity for flexible pricing through the week.
3. We can see that there is some shared demand in approximately the third week of February; all three lines spike up at the same period of time.  Assuming this is something like a local sporting event, Valentine's Day, etc. the company could try different marketing campaigns or tactics to boost ridership when the demand is there.


## Recommendations

The below are recommendations based on the analysis and points made above.  I also provided some of the assumptions on which these recommendations are based.
1. Understand the late February demand spike across all three geographies and find ways to capitalize on it.  We know that, regardless of location, demand was increased.  Understanding what happened on that date, the team could then identify similar events coming up and plan accordingly.  For Urban areas, there is adequate capacity to serve more riders.  The marketing team could focus on partnering with local companies somehow evolved with the event to encourage attendees to use Pyber in lieu of driving or other forms of transportation.  For suburban and rural areas, the team could focus on increasing drivers by offering new drivers some sort of bonus or possibly offering urban drives incentive to serve those in urban or suburban areas.
2. Conduct further analysis on the urban and suburban areas to determine if there is latent demand not being served.  It is hard to say if these areas are underserved.  While there is more ridership than drivers in the rural area, it isn't clear if additional drivers would capture that demand or if the total revenues and ridership would stay about the same.
3. Consider offering non-profit rides within the Urban area to serve the community.  Assuming that the CEO and company are able to reduce profitability for charitable reasons (example: a publicly traded company might have a harder time givng things away).  You can see there is adequate supply in the urban environment and assume the size of the geography is more compact than a rural area.  Pyber could elect, during offpeak times, to take a lower or no cut of the fare.  This would allow drivers to still make the same money, while the price of $24.53 could be significantly lowered and capture more ridership for lower-income individuals.  The other benefit is that, by offering this, it encourages more people to download the Pyber app and makes it more likely, both because of having the app and using the service for the first time, that they might participate in profitable rides at some point in the future.
