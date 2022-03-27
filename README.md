# Citibike Trip Sharing

## Overview

The goal of this analysis was to determine whether a bikesharing program is a prudent business venture in Des Moines using data collected from New York's Citi Bike program.

## Results

The Tableau story containing all visualizations can be found [here](https://public.tableau.com/app/profile/jake.muller1125/viz/Bikesharing_16483998616430/CitibikeTripData?publish=yes).

### [Figure 1](https://public.tableau.com/shared/YQ9GZGT3H?:display_count=n&:origin=viz_share_link) - Checkout Time

This figure shows that the majority of trips taken using Citi Bikes are under 40 minutes, with the biggest concentration of trips hovering around 10-15 minutes.

### [Figure 2](https://public.tableau.com/shared/DTWMNSRHX?:display_count=n&:origin=viz_share_link) - Checkout Time by Gender

The distribution of ride times appears very similar when comparing male and female riders, with the maxima both occuring around 10-15 minutes. The main difference is that there are roughly 4 times as many male riders as female riders. The number of riders of unknown gender is significant but shows a pattern similar enough to both male and female that knowing the gender of all unknown riders would do little to change the overall pattern other than possibly slightly increasing the trip time with the greatest number of riders.

### [Figure 3](https://public.tableau.com/shared/8K6Y6T3SC?:display_count=n&:origin=viz_share_link) - Trips by Weekday per Hour

The main takeaways from this figure are the concentration of rides ending in the 8 AM - 9 AM and 5 PM - 7 PM windows. This coincides with typical work commute hours, indicating that the Citi Bike program in New York is being used by people commuting to and from work. The distribution on the weekends is much more spread out, likely due to leisure being the main usage.

### [Figure 4](https://public.tableau.com/shared/9K7PM76J4?:display_count=n&:origin=viz_share_link) - Trips by Gender (Weekday per Hour)

This figure shows similar trends to Figure 4 (peak usage during commute times on weekdays, no strong peak on weekends) in both genders while reinforcing the greater number of male riders.

### [Figure 5](https://public.tableau.com/shared/76M8B98N3?:display_count=n&:origin=viz_share_link) - User Trips by Gender by Weekday

Figure 5 shows that the majority of riders are subscribers, especially on weekdays. If a person was to regularly use Citi Bike to commute to and from work, it would make sense for them to subscribe and presumably pay a lower price per trip. There is a very low number of unknown riders that are subscribers, likely due to subcriptions tracking stats about each rider, including gender.

### [Figure 6](https://public.tableau.com/shared/CNDTXX2SF?:display_count=n&:origin=viz_share_link) and [Figure 7](https://public.tableau.com/shared/W9ZDJ85ZW?:display_count=n&:origin=viz_share_link) - Top Starting and Ending Locations

These two figures show the top starting and ending locations, respectively, for all Citi Bike trips in New York City. Manhattan holds a very strong majority of all rides, while the outer boroughs have a smaller number of rides. Since the outer boroughs are slightly more spread out spatially and friendly to commuting via car, there is less demand for bike sharing in these areas. Manhattan, however, is a prime location for bike sharing due to its compact nature and the difficulty of driving in the area.

## Summary

All in all, the Citi Bike program appears to be both practical and profitable in New York City given its scale and demographics. However, the same may not ring true for a smaller city like Des Moines. The majority of rides in New York City are, presumably, taken by people commuting to and from work. This works because commute distances are small for people living and working in dense areas like Manhattan. A visualization of population density in Des Moines and the surrounding area would provide insight into whether a bike sharing program would be practical for commuters, as commutes of great lengths would not lend themselves to bicycle usage.

Additionally, car ownership in the Des Moines area would be another metric by which we could evaluate the feasibility of a bikesharing program. The Citi Bike program in New York City works so well because many people living in the city, and specifically in Manhattan, do not own cars they can use for their daily commutes. If the majority of people in Des Moines are car owners, they would be less likely to use a bikesharing program for their commute.
