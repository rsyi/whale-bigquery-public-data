# `geo_census_blockgroups.blockgroups_27`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `geo_id`
  - Unique identifier for each block group. Census block group identifier; a concatenation of the current state FIPS code, county FIPS code, census tract code, and block group number.
* [STRING]    `state_fips_code`
  - Two digit FIPS code that uniquely identifies each state. See https://www.census.gov/geo/reference/ansi_statetables.html for more information State names and their corresponding FIPS codes are available as a BigQuery Public Dataset: `bigquery-public-data.census_utility.fips_codes_states`
* [STRING]    `county_fips_code`
  - Four-digit county FIPS code. County names and their corresponding FIPS codes can be found in BigQuery: `bigquery-public-data.census_utility.fips_codes_all`
* [STRING]    `tract_ce`
  - Current Census tract code
* [STRING]    `blockgroup_ce`
  - Current block group number
* [STRING]    `lsad_name`
  - Current translated legal/statistical area description and the block group number
* [STRING]    `mtfcc_feature_class_code`
  - MAF/TIGER feature class code (G5030)
* [STRING]    `functional_status`
  - Current functional status
* [INTEGER]   `area_land_meters`
  - Current land area
* [INTEGER]   `area_water_meters`
  - Current water area
* [FLOAT]     `internal_point_lat`
  - Latitude of the block group's internal point, which is the point at or closest to the block group's geographic center
* [FLOAT]     `internal_point_lon`
  - Longitude of the block group's internal point, which is the point at or closest to the block group's geographic center
* [GEOGRAPHY] `internal_point_geom`
  - Geographical representation of the block group's internal point, which is the point at or closest to the block group's geographic center
* [GEOGRAPHY] `blockgroup_geom`
  - Geographical representation of the polygon that defines the perimeter of the block group. This column should be used as the GEO column for visualization in BigQuery Geo Viz

-------------------------------------------------------------------------------
*Do not make edits above this line.*
