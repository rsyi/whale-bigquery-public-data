# `geo_openstreetmap.planet_features`
`bigquery`| `bigquery-public-data`
The planet_features table was created by transforming the OSM planet.pbf file's contents of (way, node, relation) records into GDAL-type records (point, line, multilinestring, multpolygon, other_relation) using ogr2ogr.

Software used to perform the ETL is located here:
https://github.com/allenday/bigquery-openstreetmap/tree/master/osm2bigquery
https://github.com/allenday/bigquery-openstreetmap/tree/master/bin

## Column details
* [STRING]    `feature_type`
* [INTEGER]   `osm_id`
* [INTEGER]   `osm_way_id`
* [INTEGER]   `osm_version`
* [TIMESTAMP] `osm_timestamp`
* [RECORD]    `all_tags`
* [STRING]    `all_tags.key`
* [STRING]    `all_tags.value`
* [GEOGRAPHY] `geometry`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
