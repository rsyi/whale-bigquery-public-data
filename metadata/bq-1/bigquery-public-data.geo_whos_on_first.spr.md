# `geo_whos_on_first.spr`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `geoid`
  - Who's On First ID
* [INTEGER]   `id`
  - Who's On First ID
* [INTEGER]   `parent_id`
  - Parent's Who's On First ID
* [STRING]    `name`
  - Name of the place. More info available at: https://whosonfirst.org/docs/names/
* [STRING]    `placetype`
  - Type of place. Full list available at https://whosonfirst.org/docs/placetypes/
* [STRING]    `country`
  - Place's two-letter Alpha-2 ISO code. Null for places spanning several countries
* [STRING]    `repo`
  - GitHub repo containing the place
* [FLOAT]     `latitude`
  - Latitude
* [FLOAT]     `longitude`
  - Longitude
* [FLOAT]     `min_latitude`
  - Minimum latitude
* [FLOAT]     `min_longitude`
  - Minimum longitude
* [FLOAT]     `max_latitude`
  - Maximum latitude
* [FLOAT]     `max_longitude`
  - Maximum longitude
* [INTEGER]   `is_current`
  - Flag indicating whether the place is current
* [INTEGER]   `is_deprecated`
  - Flag indicating whether the place is deprecated
* [INTEGER]   `is_ceased`
  - Flag indicating whether the place is ceased
* [INTEGER]   `is_superseded`
  - Flag indicating whether the place is superseded
* [INTEGER]   `is_superseding`
  - Flag indicating whether the place supersedes another place
* [INTEGER]   `superseded_by`
  - ID of the place superseding this one
* [INTEGER]   `supersedes`
  - ID of the place superseded by this one
* [GEOGRAPHY] `geom`
  - Centroid of the place
* [STRING]    `do_label`
  - Name of the place. More info available at: https://whosonfirst.org/docs/names/
* [INTEGER]   `last_modified`
  - Last modified timestamp, in seconds since the Unix Epoch
* [TIMESTAMP] `last_modified_timestamp`
  - Last modified timestamp

-------------------------------------------------------------------------------
*Do not make edits above this line.*
