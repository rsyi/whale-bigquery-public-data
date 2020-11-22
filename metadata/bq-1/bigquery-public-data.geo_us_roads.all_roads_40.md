# `geo_us_roads.all_roads_40`
`bq-1` | `bigquery-public-data`

## Column details
* [GEOGRAPHY] `road_geom`
  - Geographic representation of the road. Each road is a line string. Primary roads will have two separate rows with different geographies representing each direction of travel
* [STRING]    `road_id`
  - Unique identifier for each road
* [STRING]    `full_name`
  - Full text name of the road
* [STRING]    `route_type`
  - Defines the route type for a given road. Possible values: C - County; I - Interstate; M - Common Name; O - Other; S - State-Recognized; U - U.S.
* [STRING]    `mtfcc_feature_class_code`
  - MAF/TIGER feature class code. Maps to `bigquery-public-data.census_utility.mtfcc_feature_class_codes`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
