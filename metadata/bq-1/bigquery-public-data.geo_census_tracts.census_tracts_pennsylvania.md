# `geo_census_tracts.census_tracts_pennsylvania`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `state_fips_code`
  - Two digit FIPS code that uniquely identifies each state. State names and their corresponding FIPS codes are available as a BigQuery Public Dataset: bigquery-public-data.census_fips_codes.states_2016
* [STRING]    `county_fips_code`
  - Four-digit county FIPS code.   County names and their corresponding FIPS codes can be found in BigQuery: bigquery-public-data.census_fips_codes.counties_2016
* [STRING]    `tract_ce`
  - Current Census tract code
* [STRING]    `geo_id`
  - Census tract identifier; a concatenation of Current state FIPS code, county FIPS code, and census tract code
* [STRING]    `tract_name`
  - Current census tract name, this is the census tract code converted to an integer or integer plus 2- character decimal if the last two characters of the code are not both zeros.
* [STRING]    `lsad_name`
  - Current translated legal/statistical area description and the census tract name
* [STRING]    `functional_status`
  - Current functional status of the Census tract
* [INTEGER]   `area_land_meters`
  - Current land area, in square meters
* [INTEGER]   `area_water_meters`
  - Current water area, in square meters
* [STRING]    `internal_point_lat`
  - Latitude of the state's internal point, which is the point at or closest to the state's geographic center
* [STRING]    `internal_point_lon`
  - Longitude of the state's internal point, which is the point at or closest to the state's geographic center
* [GEOGRAPHY] `internal_point_geo`
  - Geographic representation of the state's internal point, which is the point at or closest to the tract's geographic center
* [GEOGRAPHY] `tract_geom`
  - Geographical representation of the polygon that defines the perimeter of each Census tract. This column should be used as the GEO column for visualization in BigQuery Geo Viz

-------------------------------------------------------------------------------
*Do not make edits above this line.*
