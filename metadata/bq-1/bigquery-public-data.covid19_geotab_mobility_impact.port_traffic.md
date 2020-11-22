# `covid19_geotab_mobility_impact.port_traffic`
`bq-1` | `bigquery-public-data`
This dataset shows the average percentage week-on-week volume changes and the average weekly wait times for ports. It includes aggregate metrics for the ports as a whole, broken down by each vehicle type and for 2 high-level vehicle type groupings.

## Column details
* [STRING]    `country_iso_code_2`
  - ISO 3166-2 code representing the county and state/province where the port is located
* [STRING]    `port_id`
  - Unique port identifier
* [STRING]    `port`
  - Port name
* [STRING]    `year_week`
  - Concatenation of the year and week for which the aggregation values are calculated. Format <YYYYWW>
* [DATE]      `week_end`
  - The last day of the week for the aggregation calculations. Format <YYYY-MM-DD>
* [STRING]    `aggregation_method`
  - Define the level of the aggregation. Weekly: the average metric is calculated across the full week prior to the week_end
* [FLOAT]     `percent_of_vehicle_volume_change`
  - The percentage change in vehicle volumes in relation to the previous week
* [FLOAT]     `percent_of_trip_volume_change`
  - The percentage change in trip volumes in relation to the previous week
* [FLOAT]     `percent_of_hdt_volume_change`
  - The percentage change in Hdt vehicle volumes in relation to the previous week. Hdt = heavy duty trucks; weight class 7-8
* [FLOAT]     `percent_of_mdt_volume_change`
  - The percentage change in Mdt vehicle volumes in relation to the previous week. Mdt = medium duty trucks; weight class 4-6
* [FLOAT]     `percent_of_ldt_volume_change`
  - The percentage change in Ldt vehicle volumes in relation to the previous week. Ldt = light duty trucks; weight class 1-3 | A-H
* [FLOAT]     `percent_of_mpv_volume_change`
  - The percentage change in Mpv vehicle volumes in relation to the previous week. Mpv = multi-purpose vehicle
* [FLOAT]     `percent_of_car_volume_change`
  - The percentage change in car vehicle volumes in relation to the previous week.
* [FLOAT]     `percent_of_other_volume_change`
  - The percentage change in vehicle volumes in relation to the previous week, for all vehicles that are not classed as a Hdt, Mdt, Ldt, Mpv or car
* [FLOAT]     `percent_of_agg_truck_volume_change`
  - The percentage change in vehicle volumes in relation to the previous week, for a combined grouping of Hdt, Mdt and Ldt vehicle types
* [FLOAT]     `percent_of_agg_nontruck_volume_change`
  - The percentage change in vehicle volumes in relation to the previous week, for a combined grouping of Mpv, car and other vehicle types
* [FLOAT]     `wait_time_avg`
  - The average wait time (in minutes)
* [FLOAT]     `wait_time_hdt`
  - The average wait time (in minutes) for Hdt vehicle types. Hdt = heavy duty trucks; weight class 7-8
* [FLOAT]     `wait_time_mdt`
  - The average wait time (in minutes) for Mdt vehicle types. Mdt = medium duty trucks; weight class 4-6
* [FLOAT]     `wait_time_ldt`
  - The average wait time (in minutes) for Mdt vehicle types Ldt = light duty trucks; weight class 1-3 | A-H
* [FLOAT]     `wait_time_mpv`
  - The average wait time (in minutes) for Mdt vehicle types Mpv = multi-purpose vehicle
* [FLOAT]     `wait_time_car`
  - The average wait time (in minutes) for car vehicle types
* [FLOAT]     `wait_time_other`
  - The average wait time (in minutes) for all vehicles that are not classed as a Hdt, Mdt, Ldt, Mpv or car
* [FLOAT]     `wait_time_agg_truck`
  - The average wait time (in minutes) for a combined grouping of Hdt, Mdt and Ldt vehicle types
* [FLOAT]     `wait_time_agg_nontruck`
  - The average wait time (in minutes) for a combined grouping of Mpv, car and other vehicle types
* [STRING]    `city`
  - City in which the port resides
* [FLOAT]     `port_latitude`
  - Latitude of the centroid for the port
* [FLOAT]     `port_longitude`
  - Longitude of the centroid for the port
* [STRING]    `version`
  - Version of the table
* [GEOGRAPHY] `port_geom`
  - Polygon object of the port bounds

-------------------------------------------------------------------------------
*Do not make edits above this line.*
