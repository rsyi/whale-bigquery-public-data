# `covid19_geotab_mobility_impact.commercial_traffic`
`bq-1` | `bigquery-public-data`
The commercial traffic dataset measures the volume of commercial activity each day (at local time) from March 16 onwards, as measured by number of trips taken. Volume of activity is calculated on a relative basis using data from Feb. 1st and March 15th, 2020 as a benchmark, controlled for day-of-week. Activity is further classified by industry based on the destination location of each trip, using OpenStreetMap's building tag; no classification are made if the trip does not end around a building, though the trip will count towards PercentOfBaselineActivity.

## Column details
* [STRING]    `alpha_code_3`
  - If the record contains country-level stats: 3-letter Country code
* [STRING]    `country_iso_code_2`
  - If the record contains state-level stats: 2-letter country code, followed by dash, then 2-letter state code.
* [STRING]    `region`
  - If the record contains region-level stats: region description as found in `bigquery-public-data.covid19_geotab_mobility_impact.lookup_region`
* [DATE]      `date`
  - Date of the data
* [INTEGER]   `day_of_week`
  - Day of Week starting with Sunday as Day 1. Range between [1,7]
* [FLOAT]     `percent_of_baseline_activity`
  - Number of trips taken on DATE, relative to the median value for the same day-of-week during baseline period
* [FLOAT]     `percent_of_baseline_commercial`
  - percent_of_baseline_activity counting only trips starting around commercial buildings, as labelled by OpenStreetMap
* [FLOAT]     `percent_of_baseline_industrial`
  - percent_of_baseline_activity counting only trips starting around industrial buildings, as labelled by OpenStreetMap
* [FLOAT]     `percent_of_baseline_warehouse`
  - percent_of_baseline_activity counting only trips starting around warehouse buildings, as labelled by OpenStreetMap
* [FLOAT]     `percent_of_baseline_grocery_store`
  - percent_of_baseline_activity counting only trips starting around grocery store buildings, as labelled by OpenStreetMap
* [FLOAT]     `percent_of_baseline_other_retail`
  - percent_of_baseline_activity counting only trips starting around all retail buildings, excluding those classified as GroceryStore, as labelled by OpenStreetMap
* [GEOGRAPHY] `region_geom`
  - Geographic shape of the country, region, or state; for performance, shapes of regions and states are rough approximates of real boundaries.
* [STRING]    `version`
  - Version of the table

-------------------------------------------------------------------------------
*Do not make edits above this line.*
