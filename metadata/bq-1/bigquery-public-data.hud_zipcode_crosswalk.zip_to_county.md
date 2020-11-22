# `hud_zipcode_crosswalk.zip_to_county`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `zip_code`
  - 5 digit USPS Zip Code.
* [STRING]    `county_geoid`
  - 5 digit unique 2000 or 2010 Census County GEOID consisting of state FIPS + county FIPS. These can map to multiple USPS ZIPs. Maps to 'geo_id' in tables with county data
* [NUMERIC]   `residential_ratio`
  - The ratio of residential addresses in the ZIP - County part to the total number of residential addresses in the entire ZIP.
* [NUMERIC]   `business_ratio`
  - The ratio of business addresses in the ZIP - County part to the total number of business addresses in the entire ZIP.
* [NUMERIC]   `other_ratio`
  - The ratio of other addresses in the ZIP - County part to the total number of business addresses in the entire ZIP.
* [NUMERIC]   `total_ratio`
  - The ratio of all addresses in the ZIP - County part to the total number of business addresses in the entire ZIP.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
