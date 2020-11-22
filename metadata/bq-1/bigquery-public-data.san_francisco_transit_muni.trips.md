# `san_francisco_transit_muni.trips`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `trip_id`
  - Unique identifier for each trip
* [STRING]    `route_id`
  - Unique identifier for each route. A single route will have multiple trips
* [STRING]    `direction`
  - "Indicates the direction of travel for a trip. The following values are valid:   -  O: Outbound travel -  I: Inbound travel  This field is not used in routing, but instead provides a way to separate trips by direction"
* [STRING]    `block_id`
  - Identifies the block to which the trip belongs. A block consists of a single trip or many sequential trips made with the same vehicle. The trips are grouped into a block by the use of a shared service day andblock_id. A block_id can include trips with different service days, which then makes distinct blocks. For more details, see: https://developers.google.com/transit/gtfs/reference/#example-showing-blocks-and-service-day
* [STRING]    `service_category`
  - Indicates the type of service for this trip
* [STRING]    `trip_headsign`
  - Contains the text that appears on signage that identifies the trip's destination to riders. Use this field to distinguish between different patterns of service on the same route.
* [STRING]    `shape_id`
  - Unique identifier for the geospatial shape that describes the vehicle travel for a trip along individual points. Use to JOIN with the shapes available in the shapes table
* [GEOGRAPHY] `trip_shape`
  - Geographical representation of the trip's entire route.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
