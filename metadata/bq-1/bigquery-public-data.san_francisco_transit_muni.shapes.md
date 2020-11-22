# `san_francisco_transit_muni.shapes`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `shape_id`
  - Uniquely identifies each shape
* [INTEGER]   `shape_point_sequence`
  - Associates the latitude and longitude of a shape point with its sequence order along the shape. The values for shape_pt_sequence must increase throughout the trip but don't need to be consecutive.
* [FLOAT]     `shape_point_lat`
  - Associates a shape point's latitude with a shape ID.
* [FLOAT]     `shape_point_lon`
  - Associates a shape point's longitude with a shape ID.
* [GEOGRAPHY] `shape_point_geom`
  - Geographic representation of the points latitude and longitude
* [FLOAT]     `shape_distance_traveled`
  - Provides the actual distance traveled along the shape from the first shape point to the point specified in this record. This information allows the trip planner to determine how much of the shape to draw when they show part of a trip on the map. The values used for shape_dist_traveled must increase along with shape_pt_sequence: they can't be used to show reverse travel along a route.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
