# Data-Analyst with Minh
# Ford System Data Analyst
# Overview
Start Data Analyst with the exploration of Ford System. This Document explores a dataset about individual rides which was made in a bike-sharing system covering the San Francisco in 2019

## Dataset

The data consists of information regarding 183,412 rides made in a bike-sharing system covering the greater San Francisco Bay area in 2019. The dataset includes 16 features ('duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude','start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type','member_birth_year', 'member_gender', 'bike_share_for_all_trip'). The dataset can be found [here](https://www.kaggle.com/datasets/chirag02/ford-gobike-2019feb-tripdata?resource=download).
Upon proper data cleaning, the dataset was reduced and feature-engineered into 11 columns with  the new columns being: 

> day_of_week: to store week day number from start_time.

> start_hour: to store hour number from start_time.

> time_of_day: to store the time of the day from start_hour.

> duration_min: to store the duration in minutes.

> user_age: to store the user's age from member.

> user_age_bin: grouped/binned ages for age group exploration.