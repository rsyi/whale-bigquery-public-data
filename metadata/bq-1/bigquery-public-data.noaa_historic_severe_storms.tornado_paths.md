# `noaa_historic_severe_storms.tornado_paths`
`bq-1` | `bigquery-public-data`

## Column details
* [DATE]      `storm_date`
  - Date of the tornado
* [TIME]      `storm_time`
  - Time of the tornado
* [STRING]    `time_zone_offset`
  - Timezone offset of where the the tornado occurred. Possible values are -06:00 (CST), -00:00 (GMT/UTC), and unknown
* [STRING]    `state_abbreviation`
  - 2 letter postal abbreviation of the state's name
* [STRING]    `state_name`
  - Full text name of the state in which the tornado occurred
* [STRING]    `state_fips_code`
  - 2-digit state FIPS code. This maps to all state_fips_code columns in the BigQuery Public Datasets Program
* [STRING]    `magnitude`
  - EF-Scale rating for the tornado. Possible values are 0, 1, 2, 3, 4 , 5 and unknown
* [INTEGER]   `injured_count`
  - Number of people injured as a result of the storm
* [INTEGER]   `fatality_count`
  - Number of fatalities that resulted from the storm
* [STRING]    `property_loss`
  - Estimated property loss in USD. Note that zero does not indicate $0. Possible values are: 0 - unknown or not provided; 1 - <50; 2 - 50 - <500; 3 - 500 - <5,000; 4 - 5,000 - <50,000; 5 - 50,000 - <500,000; 6 - 500,000 - <5,000,000; 7 - 5,000,000 - <50,000,000; 8 - 50,000,000 - <500,000,000; 9 - 500,000,000 or greater.
* [STRING]    `crop_loss`
  - Estimated crop value loss in millions of USD. Note that zero does not indicate $0. This data was is available starting in 2007
* [STRING]    `yearly_tornado_count`
  - Count of tornadoes that year after the given tornado is reported to the NWS database. This does not necessarily indicate sequential order because of reporting potential delays.
* [FLOAT]     `start_lon`
  - Tornado's starting longitude in decimal degrees
* [FLOAT]     `start_lat`
  - Tornado's starting latitude in decimal degrees
* [FLOAT]     `end_long`
  - Tornado's end longitude in decimal degrees
* [FLOAT]     `end_lat`
  - Tornado's end latitude in decimal degrees
* [FLOAT]     `length`
  - Length of the tornado, in miles
* [FLOAT]     `width`
  - Width of the tornado in feet
* [GEOGRAPHY] `tornado_path_geom`
  - Geographic representation of the storm's path

-------------------------------------------------------------------------------
*Do not make edits above this line.*
