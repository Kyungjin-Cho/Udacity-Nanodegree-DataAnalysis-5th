# Analyzing Bay Wheels's trip data
## by Kyungjin Cho


## Dataset

> This document explores the Bay Wheels's trip data for public use containing over 230,000 bike rides. This data was modified on the 6th of November, 2019. There are about 239,895 bike rides in the dataset with 17 features. 
•duration: duration_sec, start_time, end_time 
•stations(start/end): id, name, latitude, longitude 
•user: bike_id, user_type, birty_year, gender, age 
•bike share: bike_share_for_all_trip
However, some of them are removed because of the inconsistency in the birth date, which in some cases was dated prior 1900.


## Summary of Findings

> In this exploration process, I could find diverse information. For example, two types of users are using this bike sharing service. These are subscribers and customers. Because of results, I could guess that subscribers are daily commuters. In general, they are having short trips and using this service on weekdays mainly. On the other hand, I could guess that customers are probably tourists or occassional riders because of their specific using patterns. In addition, I tried to check if there are any differences between males and females. The characteristics for men and women were similar with each other. However, I could observe that women generally take longer trips than men and other.


## Key Insights for Presentation

> When I make this presentation, I tried to focus on users' using patterns per diverse user types. I start by creating the histogram of the trip duration time per user type to check the differences in using behavior. Then, I analyzed features of Users per gender and user type by introducing a bar chart. Afterwards, I focused on hourly and weekly usage of each user type. I tried to figure out diffrences in using patterns among diverse user types.
