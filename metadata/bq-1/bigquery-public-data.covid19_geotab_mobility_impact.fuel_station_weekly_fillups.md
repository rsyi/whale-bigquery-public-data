# `covid19_geotab_mobility_impact.fuel_station_weekly_fillups`
`bq-1` | `bigquery-public-data`
Percentage of normal number of fuelling events at fuel stations in North America relative to the period immediately pre-Covid-19. Aggregated by day and vehicle class.

## Column details
* [DATE]      `week_start`
  - The start of the week in which fuelling events at fuel stations was measured.
* [DATE]      `week_end`
  - The end of the week in which fuelling events at fuel stations was measured.
* [STRING]    `state_province`
  - The state where fuelling events was measured.
* [STRING]    `country_iso_code_2`
  - ISO 3166-2 code representing the county and state/province of the aggregation
* [FLOAT]     `percent_of_normal_volume`
  - The percentage of fuelling events at fuel stations relative to the baseline period.
* [STRING]    `version`
  - Version of the table

-------------------------------------------------------------------------------
*Do not make edits above this line.*
