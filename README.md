# PyBer Analysis
## Overview
### Purpose
As a new data analyst at PyBer, python-based ride sharing app company, I was first tasked with performing an exploratory analysis on a large data file. The purpose of this project was to determined relationships between city types and the number of drivers and riders as well as the percent of total fares and drivers and riders per each city. After running the analyses, I then created various charts and graphs to tell the story of the data. After the initial analysis myself and co-worker Omar were tasked with running the current analysis to provide insight into ride-sharing data based on city type. In this report specifically we will be looking at drivers, riders, and fares are influenced by the type of city whether that be Rural, Suburban, or Urban. These findings can then be used by corporate to improve accessibility in areas that need it more and determine the affordability of the PyBer service. 
## Results
As seen in the summary DataFrame below the Urban city type surpassed all others in total rides, drivers, and fares. However due to an abundance of customers and drivers they also saw the lowest average fare for drivers and riders totaling $24.53 and $16.57.  

The second highest rates were seen in the Suburban city type with approximately 1,000 less riders and 2,000 less drivers than in the Urban sphere. However due to this lack of resources that inversely drives the price up for average fare per driver and rider up to $39.50 and $30.97. 

The city type that saw the lowest totals in rides, drivers, and fares was the rural type totaling a miniscule fraction of the other city types with only 125 total rides and 78 drivers. Again, as we saw in the Suburban city type this lack of resources created an even greater surge in the average fare per ride and driver. With the highest rates of $34.62 per ride and $55.49 per driver. 

![summary_df.png](https://github.com/CristinaCod/PyBer_Analysis/blob/main/analysis/summary_df.png)

The graph below presents a better illustration in the disparities of total fares based on city types. With the Urban totals lined in yellow we can see as expected they had the highest total fares from January through April. Below that we can see Suburban outlined in Red and Rural outlined in Blue. For all city types there also appeared to be a spike right at the end of February on the same day where almost all city types saw their highest fares from the months of January through April. 

![pyber_fare_summary.png](https://github.com/CristinaCod/PyBer_Analysis/blob/main/analysis/PyBer_Fare_Summary.png)

## Summary
### Recommendations
Based on the findings of this analysis it is clear that the Rural city type would benefit greatly from additional resources. Perhaps incentivizing drivers with higher pay rates or benefits would encourage more drivers to sign up and more drivers means more opportunity for more riders and thus higher total fares. 

Additionally, perhaps the reason the Rural city type has such low number is due to the fact that people living are unaware of this service open to them. This could be rectified through better advertising targeted towards the specific people living in this area and their direct needs. 

Another business recommendation would be for PyBer to treat it’s drivers as if this is their main source of income. PyBer could pay a livable wage so that individuals can do this as their full-time job. When you think of taxi drivers in New York City most times that is their full-time job and they can support themselves through those means because there is such a high demand, they will always have an income. However, when you think of other ride-sharing companies those drivers just do this work on the side to make some extra cash on top of a regular full-time job. If PyBer treated its drivers as full-time employees and paid them as such they could ensure always having a sufficient amount of drivers. 
