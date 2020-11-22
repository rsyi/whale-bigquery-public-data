# `utility_us.us_csa_area`
`bq-1` | `bigquery-public-data`
This dataset has moved!

You can find all of the datasets that define the polygons of US political and statistical boundaries, including this one, in the new bigquery-public-data:geo_us_boundaries dataset.

## Column details
* [STRING]    `csa_code`
  - Current Combined Statistical Area (CSA) code
* [STRING]    `aff_geo_code`
  - 14-digit codes that identify the summary level of data, the geographic component of the data and FIPS codes that uniquely identify the data. Corresponds to geo_id from American Fact Finder data
* [STRING]    `geo_code`
  - Unique identifier for each CSA; should be same as csa_code
* [STRING]    `name`
  - Current full text name of CSA
* [STRING]    `lsad_code`
  - Legal/Statistical area description (LSAD) code for a given CSA.

M0 indicates "CSA (suffix)".  A full list of LSAD codes can be found here: https://www.census.gov/geo/reference/lsad.html
* [INTEGER]   `area_land_meters`
  - Current land area, in square meters
* [INTEGER]   `area_water_meters`
  - Current water area, in square meters
* [GEOGRAPHY] `csa_geom`
  - Geographical representation of the polygon that defines the perimeter of each CSA. This should be used for geographic visualization

-------------------------------------------------------------------------------
*Do not make edits above this line.*
