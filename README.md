# Ford Go Bike Data Exploration
## by Michael Owusu Agyebeng


## Dataset

> This document explores a dataset containing individual rides made in a bike-sharing system covering the greater San Francisco Bay area.This data set is taken from https://www.fordgobike.com/system-data and represents trips taken by members of the service for month of February of 2019.
There are 174,875 bike rides in the dataset with 19 features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip,age, weekday_start, and start_hour). A few of the variables are numeric in nature, whiles some are boolean, strings and dates.


## Summary of Findings

* Most rides lasted for short durations whiles a few lasted for longer durations. Also Most riders were between the ages of 20 and 40. Hence both are right skewed distributions. 
* Thursdays had the most rides and also the hours 8 and 17 had the most counts.
* More rides were made per hour by Subscribers than Customers. Similarly, more rides were made by males than every gender in each hour.
* Averagely, the longest lasting trips started at 2:00 am and 3:00 am with the other leading the chart
* Averagely, the Other gender had more duration for each day than Males and Females.


## Key Insights for Presentation

> Males and Females daily duration were fairly stable across all the days, with females rising slightly high during the weekends. However, the other gender had a major spike in duration of rides on the weekends and midweek
Also, it is interesting to see that average duration at 2:00 AM & 3.00 AM are higher than other hours for all genders especially the other gender which seems to be over 175 minutes long.