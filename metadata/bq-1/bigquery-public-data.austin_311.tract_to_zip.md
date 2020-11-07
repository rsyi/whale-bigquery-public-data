# `austin_311.tract_to_zip`
`bigquery` | `bigquery-public-data`
Census tract crosswalk to USPS ZIP code.
This file is not 1-1; please use ratio columns when aggregating to zips.

This is ZIP CODE, not ZCTA.
Do not join ZIP CODE directly to ZCTA census tables.

This cross reference table is supplied by US HUD.
https://www.huduser.gov/portal/datasets/usps_crosswalk.html


"One of the many challenges that researchers and practitioners face is the difficulty of relating United States Postal Service (USPS) ZIP codes to Census Bureau geographies. There are valuable data available only at the ZIP code level that, when combined with demographic data tabulated at various Census geography levels, could open up new avenues of exploration.

While some acceptable methods of combining ZIP codes and Census geography exist, they have limitations. To provide additional avenues for merging these data, PD&R has released the HUD-USPS Crosswalk Files. These unique files are derived from data in the quarterly USPS Vacancy Data. They originate directly from the USPS; are updated quarterly, making them highly responsive to changes in ZIP code configurations; and reflect the locations of both business and residential addresses."

## Column details
* [STRING]    `census_tract_geoid`
  - 11 digit unique 2000 or 2010 Census tract GEOID consisting of state FIPS + county FIPS + tract code. The decimal is implied and leading and trailing zeros have been preserved. These can map to multiple USPS ZIPs. Maps to 'geo_id' in tables with Census Tract data
* [STRING]    `zip_code`
  - 5 digit USPS Zip Code.
* [NUMERIC]   `residential_ratio`
  - The ratio of residential addresses in the Tract-ZIP part to the total number of residential addresses in the entire Tract.
* [NUMERIC]   `business_ratio`
  - The ratio of business addresses in the Tract-ZIP part to the total number of business addresses in the entire Tract.
* [NUMERIC]   `other_ratio`
  - The ratio of other addresses in the Tract-ZIP part to the total number of other addresses in the entire Tract.
* [NUMERIC]   `total_ratio`
  - The ratio of all addresses in the Tract-ZIP part to the total number of all types of addresses in the entire Tract.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
