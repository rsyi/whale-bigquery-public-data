# `openaq.global_air_quality`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `location`
  - Location where data was measured
* [STRING]    `city`
  - City containing location
* [STRING]    `country`
  - Country containing measurement in 2 letter ISO code
* [STRING]    `pollutant`
  - Name of the Pollutant being measured. Allowed values: PM25, PM10, SO2, NO2, O3, CO, BC
* [FLOAT]     `value`
  - Latest measured value for the pollutant
* [TIMESTAMP] `timestamp`
  - The datetime at which the pollutant was measured, in ISO 8601 format
* [STRING]    `unit`
  - The unit the value was measured in coded by UCUM Code
* [STRING]    `source_name`
  - Name of the source of the data
* [FLOAT]     `latitude`
  - Latitude in decimal degrees. Precision >3 decimal points.
* [FLOAT]     `longitude`
  - Longitude in decimal degrees. Precision >3 decimal points.
* [FLOAT]     `averaged_over_in_hours`
  - The number of hours the value was averaged over.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
