# `catalonian_mobile_coverage_eu.mobile_data_2015_2017`
`bq-1` | `bigquery-public-data`
Data collected by the Catalonia Mobile Coverage application 2015-2017

## Column details
* [DATE]      `date`
  - Telemetry date on format YYYY-MM-DD. This is the partition key
* [TIME]      `hour`
  - Telemetry hour on format HH24:MM:SS
* [FLOAT]     `lat`
  - Latitude
* [FLOAT]     `long`
  - Longitude
* [INTEGER]   `signal`
  - Average signal measured in ASU (Arbitrary Strength Unit)
* [STRING]    `network`
  - Network name
* [STRING]    `operator`
  - Operator name
* [INTEGER]   `status`
  - Status code = {0,1,2,3}
* [STRING]    `description`
  - Description STATE_POWER_OFF (3), STATE_OUT_OF_SERVICE (1), STATE_IN_SERVICE (0), STATE_EMERGENCY_ONLY (2)
* [STRING]    `net`
  - Network type = 2G,3G,4G
* [FLOAT]     `speed`
  - Source estimated speed
* [FLOAT]     `satellites`
  - Number of GPS satellites
* [FLOAT]     `precission`
  - Constant that describes the provider accuracy
* [STRING]    `provider`
  - Position provider name
* [STRING]    `activity`
  - User activity: IN_VEHICLE-STILL-ON_FOOT-TILTING-UNKNOWN-ON_BICYCLE
* [FLOAT]     `downloadSpeed`
  - Current download speed
* [FLOAT]     `uploadSpeed`
  - Current upload speed
* [STRING]    `postal_code`
  - Town postal code
* [STRING]    `town_name`
  - Name of the town where th telemetry were acquired
* [GEOGRAPHY] `position_geom`
  - Geographic representation of the position

-------------------------------------------------------------------------------
*Do not make edits above this line.*
