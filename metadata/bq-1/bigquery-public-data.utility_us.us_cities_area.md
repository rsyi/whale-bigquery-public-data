# `utility_us.us_cities_area`
`bq-1` | `bigquery-public-data`
This dataset has moved!

You can find all of the datasets that define the polygons of US political and statistical boundaries, including this one, in the new bigquery-public-data:geo_us_boundaries dataset.

## Column details
* [STRING]    `urban_area_code`
  - Urban area code from the 2010 Census
* [STRING]    `geo_code`
  - Unique identifier for each urban area; Same as urban_area_code
* [STRING]    `name`
  - Full text name for the urban area
* [STRING]    `lsad_name`
  - 2010 Census name and the translated legal/statistical area description of a given urban area
* [STRING]    `lsad_code`
  - Legal/Statistical area description (LSAD) code for a given urban area. 

75 indicates an "urbanized area"
76 indicates an "urban cluster"
* [STRING]    `feature_class_code`
  - 5-digit code assigned by the Census Bureau intended to classify and describe geographic objects or features. 
"G3500" indicates "urban area"
* [STRING]    `area_type`
  - 2010 Census urban area type. 

C indicates an "urban cluster", which is an area with a population between 2,500 and 49,999 
U indicates an "urbanized area", which is an area with a population greater than or equal to 50,000

More information on how the Census Bureau made these determinations can be found here: https://www.census.gov/geo/reference/urban-rural.html
* [STRING]    `functional_status`
  - Current functional status code. A full list of possible results can be found: https://www.census.gov/geo/reference/funcstat.html 
"A" refers to "active government providing primary general-purpose functions"
* [NUMERIC]   `area_land_meters`
  - Current land area, in square meters
* [NUMERIC]   `area_water_meters`
  - Current water area, in square meters
* [STRING]    `int_point_lat`
  - Current latitude of the internal point, which is the point at or closest to the state's geographic center
* [STRING]    `int_point_lon`
  - Current longitude of the internal point, which is the point at or closest to the state's geographic center
* [GEOGRAPHY] `city_geom`
  - Points of a polygon that encompass the urban area. Should be used for geographic visualization

-------------------------------------------------------------------------------
*Do not make edits above this line.*
