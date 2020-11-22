# `utility_us.us_msa_area`
`bq-1` | `bigquery-public-data`
This dataset has moved!

You can find all of the datasets that define the polygons of US political and statistical boundaries, including this one, in the new bigquery-public-data:geo_us_boundaries dataset.

## Column details
* [STRING]    `csa_code`
  - Current Combined Statistical Area (CSA) code of the CSA that contains the metropolitan statistical area/micropolitan statistical area (MSA)
* [STRING]    `msa_code`
  - Current metropolitan statistical area/micropolitan
statistical area (MSA) code
* [STRING]    `geo_code`
  - Unique identifier for each MSA. Matches msa_code
* [STRING]    `name`
  - Full text name of the metropolitan statistical area/micropolitan statistical area
* [STRING]    `lsad_name`
  - Current name and the translated legal/statistical area description for metropolitan statistical area/micropolitan statistical area
* [STRING]    `lsad_code`
  - Legal/Statistical area description (LSAD) code for a given MSA.

M1 indicates a "metro area (suffix)"
M2 indicates a "micro area (suffix)"
* [STRING]    `status_indicator`
  - Current metropolitan/micropolitan status indicator. 

1 indicates a metropolitan statistical area. Each metropolitan statistical area must have at least one urbanized area of 50,000 or more inhabitants.
2 indicates a micropolitan statistical area. Each micropolitan statistical area must have at least one urban cluster of at least 10,000 inhabitants, with no more than 49,999
* [STRING]    `feature_class_code`
  - MAF/TIGER feature class code 

G3110 indicates either a metropolitan or micropolitan statistical area
* [NUMERIC]   `area_land_meters`
  - Current land area, in square meters
* [NUMERIC]   `area_water_meters`
  - Current water area, in square meters
* [STRING]    `int_point_lat`
  - Current latitude of the internal point, which is the point at or closest to the MSA's geographic center
* [STRING]    `int_point_lon`
  - Current longitude of the internal point, which is the point at or closest to the MSA's geographic center
* [GEOGRAPHY] `msa_geom`
  - Points of a polygon that encompass the state. Should be used for geographic visualization

-------------------------------------------------------------------------------
*Do not make edits above this line.*
