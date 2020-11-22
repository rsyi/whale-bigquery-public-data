# `utility_us.zipcode_area`
`bq-1` | `bigquery-public-data`
This dataset has moved!

You can find all of the datasets that define the polygons of US political and statistical boundaries, including this one, in the new bigquery-public-data:geo_us_boundaries dataset.

Combining a variety of sources, mainly from the Census Bureau (such as National Places: https://www2.census.gov/geo/docs/reference/codes/files/national_places.txt), we've derived a useful US zipcode and general geographic table.

## Column details
* [STRING]    `zipcode`
  - Five digit ZIP Code Tabulation Area Census Code
* [INTEGER]   `area_land_meters`
  - Land Area (square meters) - Created for statistical purposes only
* [INTEGER]   `area_water_meters`
  - Water Area (square meters) - Created for statistical purposes only
* [FLOAT]     `area_land_miles`
  - Land Area (square miles) - Created for statistical purposes only
* [FLOAT]     `area_water_miles`
  - Water Area (square miles) - Created for statistical purposes only
* [FLOAT]     `latitude`
  - Latitude (decimal degrees) First character is blank or "-" denoting North or South latitude respectively
* [FLOAT]     `longitude`
  - Longitude (decimal degrees) First character is blank or "-" denoting East or West longitude respectively
* [STRING]    `state_code`
  - Abbreviations of the state for the zipcode
* [STRING]    `state_name`
  - Name of the state for the zipcode
* [STRING]    `city`
  - Comma-separated list of cities
* [STRING]    `county`
  - Comma-separated list of counties
* [STRING]    `state_fips`
  - FIPS state code for the zipcode
* [STRING]    `zipcode_geom`
  - Generalized areal representations of United States Postal Service (USPS) ZIP Codes as polygons

-------------------------------------------------------------------------------
*Do not make edits above this line.*
