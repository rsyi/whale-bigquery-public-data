# `san_francisco_transit_muni.vehicle_monitoring`
`bq-1` | `bigquery-public-data`

## Column details
* [TIMESTAMP] `time_recorded`
  - The timestamp of the last real-time update from the particular vehicle.
* [STRING]    `route_id`
  - Unique reference for the route on which the vehicle is traveling. Maps to route_id in the routes table
* [STRING]    `direction`
  - Indicates the direction of travel for a trip. The following values are valid:   -  O: Outbound travel -  I: Inbound travel  This field is not used in routing, but instead provides a way to separate trips by direction
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
* [STRING]    `next_stop_id`
  - Unique reference for the stop being monitored. Maps to stop_id in the stops table
* [STRING]    `next_stop_name`
  - Full text name of the stop being monitored. Maps to stop_name in the stops table
* [TIMESTAMP] `next_stop_expected_arrival_time`
  - Estimated arrival time at the next stop
* [TIMESTAMP] `next_stop_aimed_arrival_time`
  - Aimed arrival time at the next stop
* [TIMESTAMP] `next_stop_expected_departure_time`
  - Estimated departure time from the next stop
* [TIMESTAMP] `next_stop_aimed_departure_time`
  - Aimed departure time from the next stop
* [STRING]    `onward_stop_id_1`
  - Unique reference for onward stop 1. Maps to stop_id in the stops table
* [STRING]    `onward_stop_name_1`
  - Full text name of onward stop 1. Maps to stop_name in the stops table
* [TIMESTAMP] `onward_stop_expected_arrival_time_1`
  - Estimated arrival time at onward stop 1
* [TIMESTAMP] `onward_stop_aimed_arrival_time_1`
  - Estimated arrival time at onward stop 1
* [TIMESTAMP] `onward_stop_aimed_departure_time_1`
  - Aimed departure time from onward stop 1
* [STRING]    `onward_stop_id_2`
  - Unique reference for onward stop 2. Maps to stop_id in the stops table
* [STRING]    `onward_stop_name_2`
  - Full text name of onward stop 2. Maps to stop_name in the stops table
* [TIMESTAMP] `onward_stop_expected_arrival_time_2`
  - Estimated arrival time at onward stop 2
* [TIMESTAMP] `onward_stop_aimed_arrival_time_2`
  - Estimated arrival time at onward stop 2
* [TIMESTAMP] `onward_stop_aimed_departure_time_2`
  - Aimed departure time from onward stop 2
* [STRING]    `onward_stop_id_3`
  - Unique reference for onward stop 3. Maps to stop_id in the stops table
* [STRING]    `onward_stop_name_3`
  - Full text name of onward stop 3. Maps to stop_name in the stops table
* [TIMESTAMP] `onward_stop_expected_arrival_time_3`
  - Estimated arrival time at onward stop 3
* [TIMESTAMP] `onward_stop_aimed_arrival_time_3`
  - Estimated arrival time at onward stop 3
* [TIMESTAMP] `onward_stop_aimed_departure_time_3`
  - Aimed departure time from onward stop 3
* [STRING]    `onward_stop_id_4`
  - Unique reference for onward stop 4. Maps to stop_id in the stops table
* [STRING]    `onward_stop_name_4`
  - Full text name of onward stop 4. Maps to stop_name in the stops table
* [TIMESTAMP] `onward_stop_expected_arrival_time_4`
  - Estimated arrival time at onward stop 4
* [TIMESTAMP] `onward_stop_aimed_arrival_time_4`
  - Estimated arrival time at onward stop 4
* [TIMESTAMP] `onward_stop_aimed_departure_time_4`
  - Aimed departure time from onward stop 4
* [STRING]    `onward_stop_id_5`
  - Unique reference for onward stop 5. Maps to stop_id in the stops table
* [STRING]    `onward_stop_name_5`
  - Full text name of onward stop 5. Maps to stop_name in the stops table
* [TIMESTAMP] `onward_stop_expected_arrival_time_5`
  - Estimated arrival time at onward stop 5
* [TIMESTAMP] `onward_stop_aimed_arrival_time_5`
  - Estimated arrival time at onward stop 5
* [TIMESTAMP] `onward_stop_aimed_departure_time_5`
  - Aimed departure time from onward stop 5
* [STRING]    `onward_stop_id_6`
  - Unique reference for onward stop 6. Maps to stop_id in the stops table
* [STRING]    `onward_stop_name_6`
  - Full text name of onward stop 6. Maps to stop_name in the stops table
* [TIMESTAMP] `onward_stop_expected_arrival_time_6`
  - Estimated arrival time at onward stop 6
* [TIMESTAMP] `onward_stop_aimed_arrival_time_6`
  - Estimated arrival time at onward stop 6
* [TIMESTAMP] `onward_stop_aimed_departure_time_6`
  - Aimed departure time from onward stop 6
* [STRING]    `onward_stop_id_7`
  - Unique reference for onward stop 7. Maps to stop_id in the stops table
* [STRING]    `onward_stop_name_7`
  - Full text name of onward stop 7. Maps to stop_name in the stops table
* [TIMESTAMP] `onward_stop_expected_arrival_time_7`
  - Estimated arrival time at onward stop 7
* [TIMESTAMP] `onward_stop_aimed_arrival_time_7`
  - Estimated arrival time at onward stop 7
* [TIMESTAMP] `onward_stop_aimed_departure_time_7`
  - Aimed departure time from onward stop 7
* [STRING]    `onward_stop_id_8`
  - Unique reference for onward stop 8. Maps to stop_id in the stops table
* [STRING]    `onward_stop_name_8`
  - Full text name of onward stop 8. Maps to stop_name in the stops table
* [TIMESTAMP] `onward_stop_expected_arrival_time_8`
  - Estimated arrival time at onward stop 8
* [TIMESTAMP] `onward_stop_aimed_arrival_time_8`
  - Estimated arrival time at onward stop 8
* [TIMESTAMP] `onward_stop_aimed_departure_time_8`
  - Aimed departure time from onward stop 8
* [STRING]    `onward_stop_id_9`
  - Unique reference for onward stop 9. Maps to stop_id in the stops table
* [STRING]    `onward_stop_name_9`
  - Full text name of onward stop 9. Maps to stop_name in the stops table
* [TIMESTAMP] `onward_stop_expected_arrival_time_9`
  - Estimated arrival time at onward stop 9
* [TIMESTAMP] `onward_stop_aimed_arrival_time_9`
  - Estimated arrival time at onward stop 9
* [TIMESTAMP] `onward_stop_aimed_departure_time_9`
  - Aimed departure time from onward stop 9
* [STRING]    `onward_stop_id_10`
  - Unique reference for onward stop 10. Maps to stop_id in the stops table
* [STRING]    `onward_stop_name_10`
  - Full text name of onward stop 10. Maps to stop_name in the stops table
* [TIMESTAMP] `onward_stop_expected_arrival_time_10`
  - Estimated arrival time at onward stop 10
* [TIMESTAMP] `onward_stop_aimed_arrival_time_10`
  - Estimated arrival time at onward stop 10
* [TIMESTAMP] `onward_stop_aimed_departure_time_10`
  - Aimed departure time from onward stop 10

-------------------------------------------------------------------------------
*Do not make edits above this line.*
