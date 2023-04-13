# Bikesharing
## Overview of the Analysis
After a recent trip to New York City, I and my friend Kate returned home to Des Moines Iowa with the idea of creating a bikesharing company locally; similar to the one we were able to utilize while in New York City to see many of the sights. The purpose of this analysis is to convince a potential investor to provide us with the seed money to get our business up and running, and in order to accomplish that goal we have been asked to provide them analysis on bike trips by way of the bikesharing program in New York City; utilizing bikesharing date from August of 2019 to do so.

## Results
### Link to NYC Citibke Challence Dashboard
[NYC_Citibike_Challenge](https://public.tableau.com/shared/JN8BC46HK?:display_count=n&:origin=viz_share_link)
### Top Starting Locations
![Top Starting Locations](https://github.com/Caracalla1081/bikesharing/blob/352ca261bf84e4129e2651075f21d1f04e72832f/Images/Top%20Starting%20Locations.png)
- The highest count of trip starts, by longitude and longitude, are around the mid-town, pier areas, and Uptown/Central Park areas of New York City.

### Top Ending Locations
![Top Ending Locations](https://github.com/Caracalla1081/bikesharing/blob/352ca261bf84e4129e2651075f21d1f04e72832f/Images/Top%20Ending%20Locations.png)
- The highest count of trip ends, by longitude and longitude, are around the mid-town, pier areas, and Uptown/Central Park areas of New York City.

### User Trips by Weekday, per Hour
![User Trips by Weekday, per Hour](https://github.com/Caracalla1081/bikesharing/blob/2685d46b42689d29f2e2614ac3d992a562bc40cf/Images/User%20trips%20by%20Weekday%20per%20Hour.png)
- The highest periods of utilization of the bikesharing program are during what we historically have called "rush hour"; the hours of 6am-10am and 4pm-8pm.
- In New York City, Wednesday appears to be an outlier for weekday usage trends.
- On Weekends Saturday sees more usage than Sundays
-   Saturday peaks between 10am to 7pm
-   Sunday peakes between 12pm to 6pm

### Duration of Trips
![Duration of Trips](https://github.com/Caracalla1081/bikesharing/blob/352ca261bf84e4129e2651075f21d1f04e72832f/Images/Duration%20of%20Trips.png)
- The majority of trips are under an hour long, more specifically under thirty minutes.

### User Trips by Weekday by Gender
![User Trips by Weekday, by Gender](https://github.com/Caracalla1081/bikesharing/blob/81d5a3d4b7259a8404d57464a7aaef8030c61606/Images/User%20Trips%20by%20Weekday%20by%20Gender.png)
- Overall most users of the service are "subscribers"
- "Customers" utilize the service the most on weekend, followed by Friday and Thursday
- Male "subscribers" utilize the bikes the most on Thursdays, then pretty equally over the remaining days; with the exceptions of Sunday and Wednesday.

### Trips by Gender (Weekday per Hour)
![Trips by Gender Weekday per Hour](https://github.com/Caracalla1081/bikesharing/blob/352ca261bf84e4129e2651075f21d1f04e72832f/Images/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)
- Trends here follow similar patterns as "User Trips by Weekday, per Hour", with female riders using the service more than male riders.

### Duration of Trips by Gender
![Duration of Trips, by Gender](https://github.com/Caracalla1081/bikesharing/blob/352ca261bf84e4129e2651075f21d1f04e72832f/Images/Duration%20of%20Trips%20by%20Gender.png)
- Male riders had the majority of their rides come in at five minutes, whereas female riders were very similar at six minutes.
- Male riders took shorter trips on average more than female riders.
- Male riders utilized the service more than female riders.

## Summary
After completing my analysis the trends visible are that the if our bikesharing company is to be a success in Des Moines it would be dependent one on getting people to be "subscribers", and those "subscribers" would primarily be comprised of people that use the bikes for their daily commute to work.

The first point, gaining "subscribers" vs. just "customers" is based on the usage datapoints provided in the "User Trips by Weekday by Gender" visual that shows a clear gap, or preference, to between those that are "subscribers" as opposed to "customers" in overall users. Gaining "subscribers" is also advantageous to our planned business because it provides us a consistent source of revenue, as opposed to the welcome, but sporadic nature of "customers".

The second point of "subscribers" are primarily based comprised of people using the bikesharing service for their daily commute is supported specifically by the visuals "Top Starting Locations", "Top Ending Locations, and "User Trips by Weekday per Hour". Individually the longitude and latitude markers within the top starting and ending visuals line-up with each other, showing that most people are making round-trips when using the bikesharing service. The "User Trips per Weekday per Hour" visual shows that the highest times of utilization are primarily during "rush hour" time periods on weekdays. When the datapoints of all three visuals are analyzed for any relationships between them, it is safe to conclude that the majority of "subscribers" are using the bikesharing service as an alternative to owning a car, or ridesharing services to get to and from work.

Looking at the visuals that I created to present to the potential investor, I may have created two more to analyze; given the time. 

One of those visuals would be to either modify the "Top Starting Locations" and "Top Ending Locations" visuals to go by the field "Station Name", but even more I would create visual that shows the a count of trips that start and end at the same station to bolster the theory that most users are utilizing the bikesharing service for work commutes. This could either be done by a simple table/matrix, or map. 

Another visual, or visuals that could be created are breakdowns of current visuals in our workspace of "usertypes" by age. This would allow us to better take into account any data available regarding age demographics of Des Moines, and allow for more efficient micro-targeting of potential customers based on usage. For instance maybe older riders are the primary "usertypes" that make up the smaller count of riders taking trips over an our or several hours; if so it could influnce a strategy to get those potential customers to utilize our bikesharing service.
