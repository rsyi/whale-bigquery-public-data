# `covid19_geotab_mobility_impact.airport_traffic`
`bq-1` | `bigquery-public-data`
This dataset shows traffic to and from the Airport as a Percentage of the Traffic volume during the baseline period. The baseline period used for computing this metric is from 1st Feb to 15th March 2020. The dataset gets updated daily.

## Column details
* [STRING]    `aggregation_method`
  - Aggregation period used to compute this metric
* [DATE]      `date`
  - Date of the data
* [STRING]    `version`
  - Version of the table
* [STRING]    `airport_name`
  - Aggregation period used to compute this metric
* [FLOAT]     `percent_of_baseline`
  - Proportion of trips on this date as compared to Avg number of trips on the same day of week in baseline period i.e 1st February 2020 - 15th March 2020
* [GEOGRAPHY] `center_point_geom`
  - Geographic representation of the centroid of the Airport polygon
* [STRING]    `city`
  - City within which the Airport is located
* [STRING]    `state_region`
  - State within which the Airport is located
* [STRING]    `country_iso_code_2`
  - ISO 3166-2 code representing the county and subdivision within which the Airport is located
* [STRING]    `country_name`
  - Full text name of the country within which the Airport is located
* [GEOGRAPHY] `airport_geom`
  - Geographic representation of the Airport polygon

-------------------------------------------------------------------------------
*Do not make edits above this line.*
