# `utility_us.us_states_area`
`bq-1` | `bigquery-public-data`
This dataset has moved!

You can find all of the datasets that define the polygons of US political and statistical boundaries, including this one, in the new bigquery-public-data:geo_us_boundaries dataset.

## Column details
* [STRING]    `region_code`
  - Current region code. Regions consist of 2 or more divisions
* [STRING]    `division_code`
  - Current division code. Divisions consist of 2 or more states
* [STRING]    `state_fips_code`
  - Two digit FIPS code that uniquely identifies each state. See https://www.census.gov/geo/reference/ansi_statetables.html for more information

State names and their corresponding FIPS codes can be found in BigQuery: bigquery-public-data.census_fips_codes.states_2016
* [STRING]    `state_gnis_code`
  - Current state GNIS code as maintained by USGS. GNIS is a database that contains name and locative information about more than two million physical and cultural features.
* [STRING]    `state_geo_id`
  - Unique identifier for each state. Identical to state_fips_code
* [STRING]    `state_abbreviation`
  - 2 letter abbreviation of state name as determined by the United States Postal Service
* [STRING]    `state_name`
  - Full text name of state
* [STRING]    `legal_area_code`
  - Current legal/statistical area description code for state
* [STRING]    `feature_class_code`
  - MAF/TIGER feature class code. G4000 indicates "State or Equivalent Feature"
* [STRING]    `functional_status_code`
  - Current functional status code. A full list of possible results can be found: https://www.census.gov/geo/reference/funcstat.html
* [INTEGER]   `area_land_meters`
  - Current land area, in square meters
* [INTEGER]   `area_water_meters`
  - Current water area, in square meters
* [STRING]    `internal_point_lat`
  - Current latitude of the internal point, which is the point at or closest to the state's geographic center
* [STRING]    `internal_point_lon`
  - Current longitude of the internal point, which is the point at or closest to the state's geographic center
* [GEOGRAPHY] `state_geom`
  - Points of a polygon that encompass the state. Should be used for geographic visualization

-------------------------------------------------------------------------------
*Do not make edits above this line.*
