# `san_francisco_bikeshare.bikeshare_trips`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `trip_id`
  - Numeric ID of bike trip
* [INTEGER]   `duration_sec`
  - Time of trip in seconds
* [TIMESTAMP] `start_date`
  - Start date of trip with date and time, in PST
* [STRING]    `start_station_name`
  - Station name of start station
* [INTEGER]   `start_station_id`
  - Numeric reference for start station
* [TIMESTAMP] `end_date`
  - End date of trip with date and time, in PST
* [STRING]    `end_station_name`
  - Station name for end station
* [INTEGER]   `end_station_id`
  - Numeric reference for end station
* [INTEGER]   `bike_number`
  - ID of bike used
* [STRING]    `zip_code`
  - Home zip code of subscriber (customers can choose to manually enter zip at kiosk however data is unreliable)
* [STRING]    `subscriber_type`
  - Subscriber = annual or 30-day member; Customer = 24-hour or 3-day member
* [STRING]    `c_subscription_type`
* [FLOAT]     `start_station_latitude`
* [FLOAT]     `start_station_longitude`
* [FLOAT]     `end_station_latitude`
* [FLOAT]     `end_station_longitude`
* [INTEGER]   `member_birth_year`
* [STRING]    `member_gender`
* [STRING]    `bike_share_for_all_trip`
* [GEOGRAPHY] `start_station_geom`
* [GEOGRAPHY] `end_station_geom`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
