# `san_francisco_transit_muni.stop_times`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `stop_id`
  - Identifies the serviced stop. Multiple routes can use the same stop.
* [INTEGER]   `trip_id`
  - Identifies a trip. Multiple trips can have the same stop
* [INTEGER]   `stop_sequence`
  - Identifies the order of the stops for a particular trip. The values for stop_sequence must increase throughout the trip but do not need to be consecutive.
* [TIME]      `arrival_time`
  - Specifies the scheduled arrival time at a specific stop for a specific trip on a route.
* [BOOLEAN]   `arrives_next_day`
  - Several routes begin before midnight, with service continuing throughout the night. This variable specifies whether arrival_time occurs after midnight the day after the scheduled day.  This is useful for identifying routes that begin one day and end the next day
* [TIME]      `departure_time`
  - Specifies the scheduled departure time at a specific stop for a specific trip on a route.
* [BOOLEAN]   `departs_next_day`
  - Several routes begin before midnight, with service continuing throughout the night. This variable specifies whether departure_time occurs after midnight the day after the scheduled day.  This is useful for identifying routes that begin one day and end the next day
* [STRING]    `dropoff_type`
  - "Indicates whether riders are dropped off at a stop as part of the normal schedule or whether a drop off at the stop isn't available. Available options:  -  regular -  none -  phone (indicates must phone agency to arrange drop off) -  driver (indicates must coordinate with driver to arrange drop off)"
* [BOOLEAN]   `exact_timepoint`
  - Indicates if the specified arrival and departure times for a stop are strictly adhered to by the transit vehicle, or if they're instead approximate or interpolated times.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
