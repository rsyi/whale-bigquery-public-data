# `covid19_geotab_mobility_impact_eu.us_border_volumes`
`bq-1` | `bigquery-public-data`
This dataset is about daily trip volume and weighted average crossing duration per trip direction. This table is updated daily.

## Column details
* [STRING]    `trip_direction`
  - Direction of the trip
* [STRING]    `day_type`
  - Weekday/Weekend indicator
* [INTEGER]   `day_of_week`
  - Day of Week starting with Sunday as Day 1. Range between [1,7]
* [DATE]      `date`
  - Date of the data
* [FLOAT]     `avg_crossing_duration`
  - Weighted average crossing duration (min)
* [INTEGER]   `percent_of_normal_volume`
  - The overall daily trip volume is compared to avg number of trips in baseline period i.e Jan.1st to Feb.29, 2020.
* [FLOAT]     `avg_crossing_duration_truck`
  - Weighted average crossing duration (min) for trucks
* [INTEGER]   `percent_of_normal_volume_truck`
  - The truck daily trip volume is compared to avg number of trips in baseline period i.e Jan.1st to Feb.29, 2020.
* [STRING]    `version`
  - Version of the table

-------------------------------------------------------------------------------
*Do not make edits above this line.*
