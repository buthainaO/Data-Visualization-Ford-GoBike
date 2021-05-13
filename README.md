# (Ford GoBike Data analysis)
## by (Buthaina Alotaibi)


## Dataset
The dataset for Ford GoBike aggregates the data for rides in February 2019, Ford GoBike is the Bay Area’s bike share system. Bay Area Bike Share was introduced in 2013. It services San Francisco, the East Bay and San Jose.
Similar to other bike share systems, Ford GoBike consists of a fleet of bikes that can be unlocked in one station and returned in any other network station. Thus, this is ideal for one-way trips. These bikes are available for use throughout the year and riders have access to all bikes in the network.
 
The dataset downloaded from udacity. It contains 183412 row and 16 columns.
>- duration_sec ”int64”: Trip Duration (seconds)
- start_time ”object“: Start Time and Date
- end_time ”object“: End Time and Date
- start_station_id ”float64”: Start Station ID
- start_station_name “object”: Start Station Name
- start_station_latitude “float64”: Start Station Latitude
- start_station_longitude “float64”: Start Station Longitude
- end_station_id “float64”: End Station ID
- end_station_name “object”: End Station Name
- end_station_latitude “float64”: End Station Latitude
- end_station_longitude “float64”: End Station Longitude
- bike_id “int64“: Bike ID
- user_type “object“: User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- member_birth_year “float64”: Member Year of Birth
- member_gender “object”: Member Gender
bike_share_for_all_trip “object”: Boolean to track members who are enrolled in the "Bike Share for All" program for low-income residents


## Used technologies:-
Before running the codes, you will need to install these:
- Anaconda
- Python  3
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Google Sheets



## Summary of Findings

> - Most of the members are born in the years from 1980 to 2000 and the peak is from 1985 to 1990. 
- The distribution between weekdays shows that Thursday and Tuesday are the peak days and most of the rides are during these days, on the other hand Sunday and Saturday are the least days. We can conclude from this information that most of the members are using it for work so there’s no need to use it on the weekends. 
- 74.6% of the members are men, 23.3% are women and 2.1% identified as “others”. 
- Most of the traffic in these start stations: Market St, San Francisco caltrain station 2, Berry St
- The age group 30-40 tends to have more duration for riders. 
- There is no big difference between the stations during the days of the week, most of the rides are during Thursday and Tuesday in all - stations, the least are on Saturday and Sunday.
- Most of the traffic for subscribers is in Market St and San Francisco Caltrain station 2. For customers, most of the traffic is in the San - Francisco Ferry Building. 
- Comparing the duration of rides across ages and user types. The subscriber type tends to overlap in small durations and the customer type has more durations. Most of the two types are between 20-60 years.


## Key Insights for Presentation

> - The age group 30-40 tends to have more duration for riders. 
- The subscriber type tends to overlap in small durations and the customer type has more durations. Most of the two types are between 20-60 years.
- The distribution between weekdays shows that Thursday and Tuesday are the peak days and most of the rides are during these days, on the other hand Sunday and Saturday are the least days. 
We can conclude from this information that most of the members are using it for work so there’s no need to use it on the weekends. 


## Recourses
- https://medium.com/@varunv31/ford-go-bike-deep-dive-into-2018-statistics-22a5ae682a37
