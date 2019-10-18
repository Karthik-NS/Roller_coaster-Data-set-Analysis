# Roller_coaster-Data-set-Analysis
Roller_coaster Data set Analysis Using Hive

Objective:
Process the Roller Coaster data and solve the below mentioned KPIs.

Data Format:
 park_id int,
 theme string,
 rollercoaster_type string,
 custom_design int,
 excitement double,
 excitement_rating string,
 intensity double,
 intensity_rating string,
 nausea double,
 nausea_rating string,
 max_speed double,
 avg_speed double,
 ride_time int,
 ride_length int,
 max_pos_gs double,
 max_neg_gs double,
 max_lateral_gs double,
 total_air_time double,
 drops int,
 highest_drop_height int,
 inversions int

Sample Data-set:
https://drive.google.com/file/d/0B6rxRECSt4WddDl4X1c1V0t3LVk/view?usp=sharing

KPIs:
1. Number of rollercoaster type based on excitement and nausea and also print theme name
2. no of rollercoaster where grouping based on excitement level and drop height 1) where excitement level is highest(very high) and drop_height>50 2) where excitement level is high
and drop_height>50 and also print the park_id.
3. Find out the name of rollercoaster_type, excitement_level intensity _level and nausea_level where total_air_time is max and find out the total_air_time of that row whose excitement_level intensity _level and nausea_level is similar to row where total_air_time is maximum.
4. Find out the name of rollercoaster_type, excitement_level ,intensity _level and nausea_level where avg_speed is max and compare the max_speed of that row whose excitement_level intensity _level and nausea_level is similar to row where avg_speed is maximum.
5. Find out the parkid and rollercoaster type where no of drop is greater than 10 and have same excitement _level.
6. Group rollercoaster_type based on custom_design where excitement level is high.
7. If ride_length is greater than 2000 and max_speed is greater than 50 so what is the level of excitement and nausea.
8. Park_name(theme) where atleast 2 rides excitement level is high.
9. In which roller coaster ride excitement level and avg_speed is highest.
10. Name of Rollercoaster where total_air_time is greater than 5 but still excitement_level is not very high.
11. If ride_length is greater than 3000 then find out avg_speed and excitement_level , group excitement_level based on avg_speed(>30 and >40).
12. When max_pos> 4 and max_neg is >1 then find out the name of rollercoaster where intensity_level is greater than excitement_level.
13. When max_pos>= 4 and max_neg is >=1 count the no of rollercoaster grouping based on
Intensity_level greater than equal or less than excitement_level and find out the same
When max_pos>= 4 and max_neg is >=1 condition is not true.
14. When nausea_level is low that what is the value of excitement_level.
15. Group rollercoaster_type based on custom_design where intensity level is very high and ride_length is greater than 2000.
