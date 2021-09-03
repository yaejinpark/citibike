# NYC Citibike - Berkeley DA
Yae Jin Park\
Module 14

## Overview
Tableau is a great visualization tool that helps data analysts present their findings in a visually appealing way with user-friendly interface that allows creating of a variety of plots, tables, and other interesting visualization patterns. The objective of this project was to analyze the data from Citibike recorded in NYC during August of 2019 with Tableau. Pandas was used to change the datatype on one of the columns (date) in the data before creating visualization on Tableau.

NOTE: None of the csv files are uploaded in the repository due to size limit.

## Results
### Dashboard Access
Please refer to the following link to the Tableau Dashboard for further details: 
[!link to dashboard](https://public.tableau.com/shared/65GT93RGJ?:display_count=n&:origin=viz_share_link)

### Preparation
Prior to importing data on Tableau, the 'tripduration' column's datatype was changed from int to datetime and then exported as a csv file. The following is a part of the resulting csv file opened in Excel.
[!D1](https://github.com/yaejinpark/citibike/blob/main/resources/d1_converted_tripdata.png)

### Visualization of Trip Data

#### Checkout Time for Users
[!D2-1](https://github.com/yaejinpark/citibike/blob/main/resources/d2_1_checkout_times_for_users.png)

#### Checkout Time by Gender
[!D2-2](https://github.com/yaejinpark/citibike/blob/main/resources/d2_2_checkout_time_by_gender.png)

#### Trips by Weekday for Each Hour
[!D2-3](https://github.com/yaejinpark/citibike/blob/main/resources/d2_3_trips_by_weekday_each_hour.png)

#### Trips by Gender (Weekday per Hour)
[!D2-4](https://github.com/yaejinpark/citibike/blob/main/resources/d2_4_trips_by_gender_weekday_each_hour.png)

#### User Trips by Gender by Weekday
[!D2-5](https://github.com/yaejinpark/citibike/blob/main/resources/d2_5_trips_by_gender_by_weekday.png)

### Additional Visualization - Start and End Locations

#### Top 10 Start Locations
[!D3-1](https://github.com/yaejinpark/citibike/blob/main/resources/d3_1_top_starting_loc.png)

#### Top 10 Ending Locations
[!D3-2](https://github.com/yaejinpark/citibike/blob/main/resources/d3_2_top_ending_loc.png)