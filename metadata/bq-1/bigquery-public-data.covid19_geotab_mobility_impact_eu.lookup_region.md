# `covid19_geotab_mobility_impact_eu.lookup_region`
`bq-1` | `bigquery-public-data`
A reference table to group states in the US and provinces in Canada into regions; using official federal regions from the Office of Management and Budget for the regions in the US.

## Column details
* [STRING]    `country_iso_code_2`
  - ISO 3166-2 code representing the county and state/province
* [STRING]    `region_id`
  - Unique identifier for each region
* [STRING]    `region_description`
  - Name of the region
* [STRING]    `states`
  - Concatenated list of states that are contained within the region. Values are separated by a semi-colon (;)

-------------------------------------------------------------------------------
*Do not make edits above this line.*
