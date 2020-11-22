# `faa.us_airports`
`bq-1` | `bigquery-public-data`
Airport defines area on land or water intended to be used either wholly or in part for the arrival; departure and surface movement of aircraft/helicopters. This airport data is provided as a vector geospatial-enabled file format. Airport information is published every eight weeks by the U.S. Department of Transportation, Federal Aviation Administration-Aeronautical Information Services.

The data is provided by the Federal Aviation Administration for public use with no restrictions for use. A limited number of Non-US Landing Facilities are included in this file. Some of these, in particular the Canadian facilities, are included to facilitate cartographic requirements in border regions. These records are not guaranteed to be complete and are not inclusive of all Canadian facilities. This airport data should not be considered official source for non-US facilities. Please contact the appropriate authority for more accurate and updated non-US airports data.

## Column details
* [STRING]    `object_id`
* [STRING]    `global_id`
* [STRING]    `faa_identifier`
* [STRING]    `name`
* [FLOAT]     `latitude`
* [FLOAT]     `longitude`
* [GEOGRAPHY] `airport_geom`
* [FLOAT]     `elevation`
* [STRING]    `icao_id`
* [STRING]    `airport_type`
* [STRING]    `service_city`
* [STRING]    `state_abbreviation`
* [STRING]    `country`
* [STRING]    `oper_status`
* [STRING]    `airport_use`
* [BOOLEAN]   `iap_exists`
* [BOOLEAN]   `dod_hiflip`
* [BOOLEAN]   `far_91`
* [BOOLEAN]   `far_93`
* [STRING]    `mil_code`
* [STRING]    `airspace_analysis`
* [BOOLEAN]   `us_high`
* [BOOLEAN]   `us_low`
* [BOOLEAN]   `ak_high`
* [BOOLEAN]   `ak_low`
* [BOOLEAN]   `us_area`
* [BOOLEAN]   `pacific`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
