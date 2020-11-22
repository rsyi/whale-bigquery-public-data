# `geo_us_census_places.us_national_places`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `state_name`
  - Full text name of the state
* [STRING]    `state_fips_code`
  - Two digit FIPS code that uniquely identifies each state. State names and their corresponding FIPS codes are available as a BigQuery Public Dataset: `bigquery-public-data.census_utility.census_utility.fips_codes_states`
* [STRING]    `place_fips_code`
  - Five-digit FIPS code for the given place. Maps to: `bigquery-public-data.census_utility.census_utility.fips_codes_all`
* [STRING]    `place_gnis_code`
  - Current place GNIS code
* [STRING]    `place_id`
  - Unique idenifier for each place. This is a concatenation of the current state FIPS code and the place FIPS code
* [STRING]    `place_name`
  - Full text name of the place
* [STRING]    `name_lsad`
  - Current name and the translated legal/statistical area description for place
* [STRING]    `lsad_code`
  - A two-character code to describe the general characteristics of a geographic area related to its legal or statistical status,governmental status,and in some cases relationship to other geographic entities. For example, an incorporated place may serve as the statistical equivalent of a county. These map to `bigquery-public-data.census_utility.census_fips_class_code`
* [STRING]    `fips_class_code`
  - Current FIPS class code
* [BOOLEAN]   `principal_city_msa`
  - Indicates if a place is the principal city for a metropolitan or micropolitan statistical area. The polygons defining metropolitan and micropolitan statistical areas are available in `bigquery-public-data.geo_us_boundaries.msa`
* [BOOLEAN]   `principal_city_ne`
  - Indicates if a place is the principal city for a Combined New England City and Town Areas (CNECTA). The polygons defining CNECTA boundaries is available from `bigquery-public-data.geo_us_boundaries.us_cnecta`
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
