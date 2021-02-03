# Des Moine's Bike Sharing Program: Key Considerations from Citibike

# Overview of the Analysis

In the interest of creating a bike sharing program in Des Moines, Iowa, taking a data driven approach is key. The following presents data taken from New York City's Citibike program in August 2019 in the form of 7 key visualizations using Tableau.

# Results

If you would like to view these visualizations in more detail, please follow this link:

[Link to dashboard](https://public.tableau.com/views/Module14Challenge_16122839309400/KeyCitibikeMetrics?:language=en&:display_count=y&publish=yes&:origin=viz_share_link)

### Trip Duration (All and by Gender)

![trip duration all](https://github.com/juberr/bikesharing/blob/main/pics/trip-duration%20all.png?raw=true)

This chart plots the amount of trips by their duration. After 5 minutes, the amount of trips falls sharply as trip duration increases. This implies most users have a trip of around 5 minutes.

A gendered view of this data suggests the same thing, as males have the highest amount of trips, but all groups follow a similar trend.

![trip duration gender](https://github.com/juberr/bikesharing/blob/main/pics/trip-duration%20gender.png?raw=true)

### Daily Usage Heatmap (All and by Gender)

![Heatmap all](https://github.com/juberr/bikesharing/blob/main/pics/heatmap%20all.png?raw=true)

At an hourly level, this visualization shows Citibike usage for each day of the week. On weekends (Saturdays and Sundays), usage increases from 9am until 5pm. This suggests people like to use Citibikes as a means to go about their weekend plans. On weekdays (Monday through Friday), usage heats up from 6am-9am and then again from 5pm-7pm. This suggests on weekdays, people use Citibikes as a means for their work commute.

In a gendered view, the same trends can be seen, but more intensely for male users. This follows similar trends seen in the Trip Duration visualization.

![Heatmap Gender](https://github.com/juberr/bikesharing/blob/main/pics/heatmap%20gender.png?raw=true)

### Daily Usage Subscribers vs Customers

![Usertype Gender](https://github.com/juberr/bikesharing/blob/main/pics/subs%20vs%20customers.png?raw=true)

This chart plots out (by gender and user type) Citibike usage for each day of the week. Between Customers, usage seems to be quite uniform throughout the week. Subscribers use Citibike more frequently, especially so for Male Subscribers.

### Usage by Birth Year

![Use by Age](https://github.com/juberr/bikesharing/blob/main/pics/use%20by%20age.png?raw=true)

This chart describes the relationship between birth year and number of trips. Saving for an outlier in 1969, there is an increase of usage for those born between 1980 and 1990. After 1990 there is a gradual drop off in trips.

### Usertype Breakdown

![Usertype Breakdown](https://github.com/juberr/bikesharing/blob/main/pics/usertype%20breakdown.png?raw=true)

The breakdown above shows the proportion of Citibike's users that are customers versus paying subscribers. An overwhelming percentage of Citibike's userbase are paying subscribers, showing subscribers are imperative for a healthy userbase.

# Summary

## Conclusions

Des Moine's bike sharing program has some great data to learn from New York's Citibike. 

Since most trips hover around 5 minutes long, Des Moine can leverage this information when deciding where to put their bike stations. Bike stations can be placed in such a way that they are accessible within a 5 minute bike ride between each other, this will bring a great convenience to users.

A common theme among three presented visualizations is that Citibike's userbase is heavily male. This presents an opportunity for Des Moine to research the question further for their own bike sharing program. Why is Citibike's userbase heavily male? Is there something missing from their program that discourages other those of other genders from participating? Those born between 1980 and 1990 present another opportunity for Des Moine to research similar questions.

Lastly, the information gleaned from the Daily Usage visualizations will provide Des Moine with key information in terms of usage patterns. Des Moine can reasonably predict peak usage times, and dynamically change the allocation of their bikes in accordance to usage.

## Future Analysis Suggestions

A visualization to consider with this given data set is a look at the relationship between trip duration and bike Id. This would provide key insight into whether bikes get uniform use, or some get used more than others. If the usage is not uniform, how could Des Moine predict which bikes will get used more?

Another visualization to consider is a look at trip duration by day of the week. If trips are longer on the weekend than they are on weekdays, more bikes may need to be available at any given moment to account the amount of bikes that are currently out on a trip.

