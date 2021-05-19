# Ford GoBike Data Exploration

## Dataset

There are 174,880 FordGoBike bike share rides in the cleaned dataset. The data consists of following information for each ride:

* time information
 * timestamps for start and end of ride (start_time, end_time)
 * ride duration in minutes (duration_min)
 * weekday of ride start (weekday_start)
 * daytime of the ride (ride_type_daytime)
 * hour of the ride (hour_start)
 * type of ride - short (below mean ride time of dataset) , long (above mean ride time of dataset) (ride_type_duration)
* start and end station information(start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude)

* user information
 * user type (user_type)
 * age of user (member_age)
 * age_category (age_level)
 * gender of user (member_gender)
 * information if user is enrolled in "Bike Share for All" program for people with low income (bike_share_for_all_trip)
* bike id (bike_id)


## Summary of Findings

My main variable of interest was the overall ride frequency depending on other variables.
In the exploration I found that ride numbers strongly depend on  
daytime/hour with additional dependancy on the fact if we look on rides on weekdays
compared to weekends.  
When looking on bike stations I found the that ride numbers not only 
depend on daytimes but also on the location of the station. On having a close look
on the information on incoming/outgoing rides I even identified a movement pattern.

Besides the main variable of interest I was looking on available user information
and concentrated on dependencies related to user age. Here I found interesting, that
the avarage age of users is higher on daily ride peaks and lower on weekends.
When looking on the geo-coordinates of ride stations I clearly could identify three different
almost separated bike rent locations.


## Key Insights for Presentation

For the presentation I focus on the discovered commuter pattern in the dataset.
I start with the distribution of ride times showing a mean ridetime of around 12 min.
Then I will show some statistics on users followed by ride frequencies based on weekdays and time of day.
Finally I'm bringing it all together by showing the difference of ride distributions 
depending on weekdays/weekend.
Additionally I'm going to show the identified movement pattern.