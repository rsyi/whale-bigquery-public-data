# `geo_openstreetmap.history_nodes`
`bigquery`| `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - Object unique ID.
* [INTEGER]   `version`
  - Version number for this object.
* [STRING]    `username`
  - Name of user who created this version of the object.
* [INTEGER]   `changeset`
  - Changeset number for this object.
* [BOOLEAN]   `visible`
  - Is this version of the object visible?
* [TIMESTAMP] `osm_timestamp`
  - Last-modified timestamp for this object.
* [GEOGRAPHY] `geometry`
  - GEOGRAPHY-encoded point
* [RECORD]    `all_tags`
  - Unstructured key=value attributes for this object.
* [STRING]    `all_tags.key`
  - Attribute key.
* [STRING]    `all_tags.value`
  - Attribute value.
* [NUMERIC]   `latitude`
* [NUMERIC]   `longitude`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
