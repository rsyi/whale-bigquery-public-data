# `covid19_geotab_mobility_impact_eu.us_border_wait_times`
`bq-1` | `bigquery-public-data`
This dataset shows hourly average border crossing duration for US-Canada and US-Mexico borders starting from 2020-03-16. Hourly trip volume is compared to average trip volume calculated between Feb.1st and Mar.15th, 2020 as a control group in each country.

## Column details
* [STRING]    `border_id`
  - Unique ID of the border crossing
* [STRING]    `port_name`
  - Port Name in Canada or Mexico
* [STRING]    `port_name_us`
  - Port Name in the US
* [STRING]    `trip_direction`
  - Direction of the trip
* [INTEGER]   `hour_local`
  - Local hour of the data
* [DATE]      `date_local`
  - Local date of the data
* [STRING]    `day_type`
  - Weekday/Weekend indicator
* [DATE]      `date_utc`
  - UTC date of the data
* [INTEGER]   `hour_utc`
  - UTC hour of the data
* [FLOAT]     `avg_crossing_duration`
  - Average border crossing times (in minutes)
* [STRING]    `aggregation_method`
  - Daily Average: the average is taken for the current LocalHour; Weekly Average: the average is taken for the full week prior to the current LocalDate; Monthly Average: the average is taken for the full month prior to the current LocalDate; Yearly Average: the average is taken for the full year prior to the LocalDate
* [FLOAT]     `percent_of_baseline_trip_volume`
  - Proportion of trips in this time interval as compared to Avg number of trips on the same hour of day in baseline period i.e 1st February 2020 - 15th March 2020. Data is only available for daily aggregation level with valid baseline number.
* [GEOGRAPHY] `border_zone`
  - Polygon of the Port in Canada or Mexico
* [STRING]    `province_code`
  - ISO 3166-2 Country-Province code in Canada or Mexico
* [GEOGRAPHY] `border_zone_us`
  - Polygon of the Port in the US
* [STRING]    `state_code_us`
  - ISO 3166-2 Country-State code for US
* [FLOAT]     `border_latitude`
  - Latitude of the border
* [FLOAT]     `border_longitude`
  - Longitude of the border
* [STRING]    `border_geohash`
  - Geohash of the Border Station with level of 7
* [STRING]    `version`
  - Version of the table

-------------------------------------------------------------------------------
*Do not make edits above this line.*
