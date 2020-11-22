# `san_francisco.bikeshare_trips`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `trip_id`
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

-------------------------------------------------------------------------------
*Do not make edits above this line.*
