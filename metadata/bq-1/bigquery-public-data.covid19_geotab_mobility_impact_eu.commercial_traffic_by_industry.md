# `covid19_geotab_mobility_impact_eu.commercial_traffic_by_industry`
`bq-1` | `bigquery-public-data`
The commercial traffic dataset measures the volume of commercial activity each day (at local time) from March 16 onwards, as measured by number of trips taken. Volume of activity is calculated on a relative basis using data from Feb. 1st and March 15th, 2020 as a benchmark, controlled for day-of-week. Activity is further classified by industry based on the destination location of each trip, using OpenStreetMap's building tag; no classification are made if the trip does not end around a building, though the trip will count towards percent_of_baseline_activity.

## Column details
* [STRING]    `alpha_code_3`
  - If the record contains country-level stats: 3-letter Country code
* [STRING]    `region`
  - If the record contains region-level stats: region description as found in `bigquery-public-data.covid19_geotab_mobility_impact.lookup_region`
* [STRING]    `industry`
  - Major industry impacted by COVID.
* [DATE]      `date`
  - Date of the data
* [FLOAT]     `percent_of_baseline`
  - Percent of baseline activity for the corresponding industry and region.
* [STRING]    `version`
  - Version of the table

-------------------------------------------------------------------------------
*Do not make edits above this line.*
