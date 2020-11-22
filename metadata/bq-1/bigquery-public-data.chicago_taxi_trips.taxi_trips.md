# `chicago_taxi_trips.taxi_trips`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `unique_key`
  - Unique identifier for the trip.
* [STRING]    `taxi_id`
  - A unique identifier for the taxi.
* [TIMESTAMP] `trip_start_timestamp`
  - When the trip started, rounded to the nearest 15 minutes.
* [TIMESTAMP] `trip_end_timestamp`
  - When the trip ended, rounded to the nearest 15 minutes.
* [INTEGER]   `trip_seconds`
  - Time of the trip in seconds.
* [FLOAT]     `trip_miles`
  - Distance of the trip in miles.
* [INTEGER]   `pickup_census_tract`
  - The Census Tract where the trip began. For privacy, this Census Tract is not shown for some trips.
* [INTEGER]   `dropoff_census_tract`
  - The Census Tract where the trip ended. For privacy, this Census Tract is not shown for some trips.
* [INTEGER]   `pickup_community_area`
  - The Community Area where the trip began.
* [INTEGER]   `dropoff_community_area`
  - The Community Area where the trip ended.
* [FLOAT]     `fare`
  - The fare for the trip.
* [FLOAT]     `tips`
  - The tip for the trip. Cash tips generally will not be recorded.
* [FLOAT]     `tolls`
  - The tolls for the trip.
* [FLOAT]     `extras`
  - Extra charges for the trip.
* [FLOAT]     `trip_total`
  - Total cost of the trip, the total of the fare, tips, tolls, and extras.
* [STRING]    `payment_type`
  - Type of payment for the trip.
* [STRING]    `company`
  - The taxi company.
* [FLOAT]     `pickup_latitude`
  - The latitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy.
* [FLOAT]     `pickup_longitude`
  - The longitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy.
* [STRING]    `pickup_location`
  - The location of the center of the pickup census tract or the community area if the census tract has been hidden for privacy.
* [FLOAT]     `dropoff_latitude`
  - The latitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy.
* [FLOAT]     `dropoff_longitude`
  - The longitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy.
* [STRING]    `dropoff_location`
  - The location of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
