# `geo_us_census_places.places_oregon`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `state_fips_code`
  - Two digit FIPS code that uniquely identifies each state. State names and their corresponding FIPS codes are available as a BigQuery Public Dataset: bigquery-public-data.census_fips_codes.states_2016
* [STRING]    `place_fips_code`
  - Five-digit FIPS code for the given place
* [STRING]    `place_gnis_code`
  - Current place GNIS code
* [STRING]    `place_id`
  - Unique idenifier for each place. This is a concatenation of the current state FIPS code and the place FIPS code
* [STRING]    `place_name`
  - Full text name of the place
* [STRING]    `name_lsad`
  - Current name and the translated legal/statistical area description for place
* [STRING]    `lsad_code`
  - Current legal/statistical area description code for each place. This helps differentiate between Census Designated Places (CDPs), which are statistical entities) and incorporated places, which are legal entities, among other differences. Census LSAD codes and their descriptions can be found in bigquery-public-data.census_lsad_codes.lsad_codes
* [STRING]    `fips_class_code`
  - Current FIPS class code
* [BOOLEAN]   `principal_city_msa`
  - Indicates if a place is the principal city for a metropolitan or micropolitan statistical area. The polygons defining metropolitan and micropolitan statistical areas are available in bigquery-public-data.geo_us_boundaries.us_msa 
* [BOOLEAN]   `principal_city_ne`
  - Indicates if a place is the principal city for a New England city and town area
* [STRING]    `functional_status`
  - Current functional status code. A full list of possible results can be found: https://www.census.gov/geo/reference/funcstat.html
* [INTEGER]   `area_land_meters`
  - Area of the place that consists of land, in square meters
* [INTEGER]   `area_water_meters`
  - Area of the place that consists of water, in square meters
* [FLOAT]     `internal_point_lat`
  - Latitude of the place's internal point, which is the point at or closest to the place's geographic center
* [FLOAT]     `internal_point_lon`
  - Longitude of the place's internal point, which is the point at or closest to the place's geographic center
* [GEOGRAPHY] `internal_point_geom`
  - Geographic representation of the state's internal point, which is the point at or closest to the state's geographic center
* [GEOGRAPHY] `place_geom`
  - Geographical representation of the polygon that defines the perimeter of each place. This column should be used as the GEO column for visualization in BigQuery Geo Viz

-------------------------------------------------------------------------------
*Do not make edits above this line.*
