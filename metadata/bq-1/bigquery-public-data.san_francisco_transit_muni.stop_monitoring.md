# `san_francisco_transit_muni.stop_monitoring`
`bq-1` | `bigquery-public-data`

## Column details
* [TIMESTAMP] `time_recorded`
  - The timestamp of the real-time update from the particular vehicle.
* [STRING]    `stop_id`
  - Unique reference for the stop being monitored. Maps to stop_id in the stops table
* [STRING]    `stop_name`
  - Full text name of the stop being monitored. Maps to stop_name in the stops table
* [STRING]    `route_id`
  - Unique reference for the route on which the vehicle is traveling. Maps to route_id in the routes table
* [STRING]    `direction`
  - Indicates the direction of travel for a trip. The following values are valid: - O: Outbound travel - I: Inbound travel  This field is not used in routing, but instead provides a way to separate trips by direction
* [DATE]      `trip_date`
  - The service date for the trip the vehicle is serving.
* [STRING]    `trip_id`
  - Unique reference for the trip that the vehicle is traveling. Maps to trip_id in the trips table
* [STRING]    `route_long_name`
  - Contains the full name of a route. This name is generally more descriptive than the name from route_short_name and often includes the route's destination or stop. Maps to route_long_name in routes table
* [FLOAT]     `vehicle_location_lat`
  - The latitude of the vehicle's location at the time when time_recorded indicates
* [FLOAT]     `vehicle_location_lon`
  - The longitude of the vehicle's location at the time when time_recorded indicates
* [GEOGRAPHY] `vehicle_location`
  - The geographic representation of the vehicle's location at the time indicated in the time_recorded column
* [STRING]    `vehicle_id`
  - The unique identifier of the vehicle to be monitored.
* [BOOLEAN]   `vehicle_at_stop`
  - Determines if the vehicle is at the monitored stop during the time_recorded. TRUE if vehicle is at the stop
* [TIMESTAMP] `aimed_arrival_time`
  - Vehicle's expected arrival time
* [TIMESTAMP] `aimed_departure_time`
  - Vehicle's expected departure time

-------------------------------------------------------------------------------
*Do not make edits above this line.*
