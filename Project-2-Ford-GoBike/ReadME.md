# Ford GoBike Data
![img](image/ford.jpeg)


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

It contains 16 features as follows:

    1. duration_sec 
    2. start_time 
    3. end_time 
    4. start_station_id 
    5. start_station_name 
    6. start_station_latitude 
    7. start_station_longitude 
    8. end_station_id 
    9. end_station_name 
    10.end_station_latitude 
    11.end_station_longitude 
    12.bike_id 
    13.user_type --> (Subscriber, Customer) 
    14.member_birth_year
    15.member_gender --> (Male, Female, Other)
    16.bike_share_for_all_trip --> (Yes, No)
    
## Summary of Findings

After invetsigation in FordGoBike service on Feb 2019, It's found that :

* Age

    The ages from 25 to 35 years tends to make more rides than others.
    
    The most long trip durations take place by 30-year old persons.
    
  
* Gender

    The number of males is much more than the other genders.
    
    The "other" gender went in longer trips than the females and males.
    
    All Genders prefer thursdays for the trip.
    
    Most of them prefered going in a trip at 7 AM and 5 PM.
    
    The most of "Other" Gender are 30 years old who made more rides.
    
    
* Duration

    The most average duration of the bike rides is from 200 to 600 Secs, This means that most of people use bikes for quick rides.
    
* Days of a week 
    
    Thursday and Tuesday are the most days on which people make more rides. On the other hand, saturday and sunday are the most days on which people make few rides. I think the reason is these days are weekends and people prefer to stay at home or travell together. 
    
    The most long distances took place on Thursday and Friday but with few meters only.
    
    
* Hour of a day
    
    The most rides happened at (5-6) PM at the sunset and (8-9) AM in the morning. 
    
    
* Distance
    
    People prefer the short distance between (0.5 - 2) Km.
    

* Bike Share of all trip
    
    The number of enrolled people is fewer than who didn't enroll.
    
* User Type
    
    For Customers, the number of trips increased on Thursday at 5-6 PM.

    On the other hand for subscribers, the number of trips increased on thursday and tuesday at 8-9 AM, and on thursday at 5-6 PM.
    


## Key Insights for Presentation

* The day of the week plays an important role in the bikes riding as we have seen in the exploration, The most rides happened on Thursday and Tuesday, but the fewest rides happened on Saturdays and sundays which are weekends.

* The hour of a day also has an important impact as the rush hours for the bikes ridings are 8-9 AM and 5-6 PM.


## Resources

* Advanced Data Analysis, Udacity
* https://stackoverflow.com/questions/19412462/getting-distance-between-two-points-based-on-latitude-longitude
* https://stackoverflow.com/questions/54733465/pandas-how-to-extract-hhmm-from-datetime-column-in-python/54733582
* https://matplotlib.org/
* https://seaborn.pydata.org/
