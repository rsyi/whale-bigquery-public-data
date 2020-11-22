# `san_francisco_transit_muni.routes`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `route_id`
  - Unique identifier for each route. A single route will have multiple trips
* [STRING]    `route_short_name`
  - Contains the short name of a route. This is a short, abstract identifier like 32, 100X, or Green that riders use to identify a route, but which doesn't give any indication of what places the route serves.
* [STRING]    `route_long_name`
  - Contains the full name of a route. This name is generally more descriptive than the name from route_short_name and often includes the route's destination or stop.
* [STRING]    `route_type`
  - "Describes the type of transportation used on a route. The following are valid values for this field:  -  light_rail: Streetcar or light rail. Used for any light rail or street-level system within a metropolitan area. -  subway: Subway or metro. Used for any underground rail system within a metropolitan area. -  rail: Used for intercity or long-distance travel. -  bus: Used for short- and long-distance bus routes. -  ferry: Used for short- and long-distance boat service. -  cable_car: Used for street-level cable cars where the cable runs beneath the car. -  tram: Gondola or suspended cable car. Typically used for aerial cable cars where the car is suspended from the cable. -  funicular: Used for any rail system that moves on steep inclines with a cable traction system."

-------------------------------------------------------------------------------
*Do not make edits above this line.*
