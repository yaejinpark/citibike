# NYC Citibike - Berkeley DA
Yae Jin Park\
Module 14 - NY Citibike with Tableau

## Overview
Tableau is a great visualization tool that helps data analysts present their findings in a visually appealing way with user-friendly interface that allows creating of a variety of plots, tables, and other interesting visualization patterns. The objective of this project was to analyze the data from Citibike recorded in NYC during August of 2019 with Tableau. Pandas was used to change the datatype on one of the columns (date) in the data before creating visualization on Tableau.

NOTE: None of the csv files are uploaded in the repository due to size limit.

## Results
### Dashboard Access
Please refer to the following link to the Tableau Dashboard for further details: 
[link to dashboard](https://public.tableau.com/shared/65GT93RGJ?:display_count=n&:origin=viz_share_link)

### Preparation
Prior to importing data on Tableau, the 'tripduration' column's datatype was changed from int to datetime and then exported as a csv file. The following is a part of the resulting csv file opened in Excel.
![D1](https://github.com/yaejinpark/citibike/blob/main/resources/d1_converted_tripdata.png)

### Visualization of Trip Data

#### Checkout Time for Users
![D2-1](https://github.com/yaejinpark/citibike/blob/main/resources/d2_1_checkout_times_for_users.png)
Most users travelled for a duration of five minutes. A peak is observed at 5 minutes of travel duration with 146,752 users.

#### Checkout Time by Gender
![D2-2](https://github.com/yaejinpark/citibike/blob/main/resources/d2_2_checkout_time_by_gender.png)
Of the number of users vs. travel duration shown in the previous screenshot, I decided to categorize said users by their gender. The plots of the male and female users show that both genders' travel durations are usually around five minutes, as expected, but the unknown gendered users' travel duration 'peak' is more spread out. 108,087 male users traveled for five minutes and 34,151 female users did the same. 

#### Trips by Weekday for Each Hour
![D2-3](https://github.com/yaejinpark/citibike/blob/main/resources/d2_3_trips_by_weekday_each_hour.png)
At what time of each weekday did all types of users travel the most? It can be observed that they did so during rush hours during business days and during daylight for weekends.

#### Trips by Gender (Weekday per Hour)
![D2-4](https://github.com/yaejinpark/citibike/blob/main/resources/d2_4_trips_by_gender_weekday_each_hour.png)
Again, male users travelled the most during rush hour hence more variation in the color of the heat map for male users. Female users, however, still follow the same pattern of peak travel numbers during the same hours. Unknown gender users show a less distinct pattern, but it seems that they travelled the most during daylight on Saturdays.

#### User Trips by Gender by Weekday
![D2-5](https://github.com/yaejinpark/citibike/blob/main/resources/d2_5_trips_by_gender_by_weekday.png)
This time, the users are divided by their genders and subscription statuses. Male and female subscription users travelled the most during business days, with male users being the largest group. Unknown gendered subscription users do not show a distinct travel pattern throughout the weekdays. During weekends, non-subscribed female and male users show less distinct patterns but have recorded highest number of travels. Unknown gendered users have the highest number of travels during the weekend among all three gender categories.

### Additional Visualization - Start and End Locations

#### Start Locations
![D3-1](https://github.com/yaejinpark/citibike/blob/main/resources/d3_1_top_starting_loc.png)
Where do most users start their travels from? Unfortunately, I do not have the locations' data besides their longitude and latitude, but the darker the circle markers' colors are, the more users started from that location.

#### Ending Locations
![D3-2](https://github.com/yaejinpark/citibike/blob/main/resources/d3_2_top_ending_loc.png)
A lot of the dark circle markers for this map are on the same locations as those of the start locations.

## Summary
From the visualization, Here are some conclusions:
* The largest group of the users are male.
* Most female and male users are subscription users.
* Subscription users seem to travel on the bikes for commuting to and from work, as the number of rides are higher during rush hours of business days.
* The top start locations and ending locations are vastly similar, which means said locations are most likely the users' workplaces or homes.
* Non-subscription users of all genders seem to prefer to ride during weekends, and of these users unknown gender is the largest group.
* Non-subscription users are biking for leisure during the daylight on weekends.