# `utility_us.us_county_area`
`bq-1` | `bigquery-public-data`
This dataset has moved!

You can find all of the datasets that define the polygons of US political and statistical boundaries, including this one, in the new bigquery-public-data:geo_us_boundaries dataset.

## Column details
* [STRING]    `state_fips_code`
  - Two digit state FIPS code.  Unique identifier for states. More detail on FIPS codes and other geographic areas can be found here: https://www2.census.gov/geo/pdfs/reference/GARM/Ch4GARM.pdf

State names and their corresponding FIPS codes can be found in BigQuery: bigquery-public-data.census_fips_codes.states_2016
* [STRING]    `county_fips_code`
  - Four-digit county FIPS code. 

County names and their corresponding FIPS codes can be found in BigQuery: bigquery-public-data.census_fips_codes.counties_2016
* [STRING]    `county_gnis_code`
  - Identifier for the USGS-maintained Geographic Names Information System (GNIS). GNIS database contains information about physical and cultural geographic features of all types in the United States, associated areas, and Antarctica, current and historical, but not including roads and highways. The database holds the Federally recognized name of each feature and defines the feature location by state, county, USGS topographic map, and geographic coordinates. Other attributes include names or spellings other than the official name, feature designations, feature classification, historical and descriptive information, and for some categories the geometric boundaries.
* [STRING]    `aff_geo_code`
  - 14-digit codes that identify the summary level of data, the geographic component of the data and FIPS codes that uniquely identify the data. Corresponds to geo_id from American Fact Finder data
* [STRING]    `geo_id`
  - Unique county identifier. It is a concatenation of current state FIPS code and county FIPS code.
* [STRING]    `county_name`
  - Full text name of the county
* [STRING]    `legal_area_code`
  - Current legal/statistical area description code. Full list of these can be found: https://www.census.gov/geo/reference/lsad.html
* [INTEGER]   `area_land_meters`
  - Current land area, in square meters
* [INTEGER]   `area_water_meters`
  - Current water area, in square meters
* [GEOGRAPHY] `county_geom`
  - Geographical representation of the polygon that defines the perimeter of each county. This column should be used as the GEO column for visualization in BigQuery Geo Viz

-------------------------------------------------------------------------------
*Do not make edits above this line.*
