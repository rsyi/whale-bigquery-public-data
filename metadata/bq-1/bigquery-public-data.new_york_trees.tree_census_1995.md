# `new_york_trees.tree_census_1995`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `recordid`
  - A unique identifier for each record in the table. Does not correspond to other datasets or identify the tree itself.
* [STRING]    `address`
  - Address of the tree.
* [STRING]    `house_number`
  - Numerical portion of the address.
* [STRING]    `street`
  - Street where address for tree is located.
* [INTEGER]   `zip_original`
  - The zip code originally geocoded to the address using LION 02A
* [INTEGER]   `cb_original`
  - The community board originally geocoded to the address using LION 02A
* [STRING]    `site`
  - This field clarifies the position relative to the address for trees not located in the front of buildings.
* [STRING]    `species`
  - Species of the tree using a four-letter code, comprised of the first two letters of the genus followed by the first two letters of the species.
* [INTEGER]   `diameter`
  - Diameter of the tree as measured at approximately 4.5 feet from the ground.
* [STRING]    `status`
  - Overall tree condition.
* [STRING]    `wires`
  - Whether the tree is located under utility wires
* [STRING]    `sidewalk_condition`
  - Whether the tree roots have lifted the adjacent sidewalk.
* [STRING]    `support_structure`
  - Whether the tree has support structures installed.
* [STRING]    `borough`
  - Borough where tree was recorded.
* [FLOAT]     `x`
  - X coordinate of point in the NAD_1983_StatePlane_New_York_Long_Island_FIPS_3104_Feet coordinate system, geocoded using LION 02A
* [FLOAT]     `y`
  - Y coordinate of point in the NAD_1983_StatePlane_New_York_Long_Island_FIPS_3104_Feet coordinate system, geocoded using LION 02A
* [FLOAT]     `longitude`
  - Longitude of point in decimal degrees as geocoded using LION 02A
* [FLOAT]     `latitude`
  - Latitude of point in decimal degrees as geocoded using LION 02A
* [INTEGER]   `cb_new`
  - Community Board geocoded to the address using Geosupport 11.4
* [INTEGER]   `zip_new`
  - Zip Code geocoded to the address using Geosupport 11.4
* [STRING]    `censustract_2010`
  - 2010 Census Tract geocoded to the address using Geosupport 11.4
* [STRING]    `censusblock_2010`
  - 2010 Census Block geocoded to the address using Geosupport 11.4
* [STRING]    `nta_2010`
  - Neighborhood Tabulation Area geocoded to the address using Geosupport 11.4
* [INTEGER]   `segmentid`
  - LION SegmentID geocoded to the address using Geosupport 11.4
* [STRING]    `spc_common`
  - This is the common name for the species of this tree.
* [STRING]    `spc_latin`
  - This is the latin/scientific name for the species of this tree.
* [STRING]    `location`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
