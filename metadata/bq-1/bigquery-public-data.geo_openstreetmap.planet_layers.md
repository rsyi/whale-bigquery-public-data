# `geo_openstreetmap.planet_layers`
`bigquery`| `bigquery-public-data`
The planet_layers table contains semantically typed geography objects using the Layered GIS format, see:
https://www.geofabrik.de/data/geofabrik-osm-gis-standard-0.7.pdf

The semantically grouped objects can be found in their primary form in the planet_features table.

Queries used to populate the table are here:
https://github.com/allenday/bigquery-openstreetmap/tree/master/layered_gis

## Column details
* [INTEGER]   `layer_code`
 - Geofabrik layer code. Example: 1003. Layers are hierarchical; The mask code=10xx corresponds to 'place' layers, and code=1003 corresponds to a 'village' type of place.
* [STRING]    `layer_class`
 - Geofabrik layer class, a friendly name for layer_code. Example: 'place'
* [STRING]    `layer_name`
 - Geofabrik layer name, a friendly name for layer_code. Example: 'village'
* [STRING]    `gdal_type`
 - OpenStreetMap feature type. One of: point, line, multilinestring, multipolygon, other_relation
* [INTEGER]   `osm_id`
 - OSM Id taken from the id of this feature (node_id or relation_id) in the OSM database.
* [INTEGER]   `osm_way_id`
 - OSM Way Id taken from the id of this feature (way_id) in the OSM database.
* [TIMESTAMP] `osm_timestamp`
 - Last-modified timestamp for this object.
* [INTEGER]   `osm_version`
 - Version number for this object.
* [RECORD]    `all_tags`
 - Unstructured key=value attributes for this object.
* [STRING]    `all_tags.key`
 - Attribute key.
* [STRING]    `all_tags.value`
 - Attribute value.
* [GEOGRAPHY] `geometry`
 - GEOGRAPHY-encoded object

-------------------------------------------------------------------------------
*Do not make edits above this line.*
