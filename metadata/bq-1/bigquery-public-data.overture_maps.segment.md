# `overture_maps.segment`
`bq-1` | `bigquery-public-data`
Segments are paths which can be traveled by people or things. Segment geometry represents the center-line of a path which may be traveled. Segment properties describe both the physical attributes (e.g. road surface and width) and non-physical attributes (e.g. access restriction rules) of that path. Two Segments are physically connected if a common Connector is referenced from the connectors property of both Segments. Where this occurs, both Segment geometries must contain the common Connector's coordinates. A physical connection between Segments indicates that it may be possible to travel from one segment to the next at the connected location, provided the Segment properties do not indicate a restriction, such as a turn restriction, which would prevent the transition in a particular case. Conversely, two segments are not physically connected—even if their geometries intersect—if they do not share a Connector in common.


Founded in 2022 under the Joint Development Foundation, Overture Maps Foundation (Overture Maps) is dedicated to the development of reliable, easy-to-use, and interoperable open map data that will power current and next-generation map products. We build this data through a collaborative process that combines technology, data, and support from a wide range of companies. Map data are assembled from multiple sources including members, civic organizations, and open data sources.

## Column details
* [STRING]    `id`
  - A feature ID. This may be an ID associated with the Global Entity Reference System (GERS) if—and-only-if the feature represents an entity that is part of GERS.
* [GEOGRAPHY] `geometry`
  - Connector's geometry which MUST be a Point as defined by GeoJSON schema in Overture data.
* [RECORD]    `bbox`
  - Area defined by two longitudes and two latitudes, where: Latitude is a decimal number between -90.0 and 90.0. Longitude is a decimal number between -180.0 and 180.0
* [FLOAT]     `bbox.xmin`
* [FLOAT]     `bbox.xmax`
* [FLOAT]     `bbox.ymin`
* [FLOAT]     `bbox.ymax`
* [INTEGER]   `version`
  - Version number of the feature, incremented in each Overture release where the geometry or attributes of this feature changed
* [STRING]    `update_time`
  - Timestamp when the feature was last updated
* [RECORD]    `sources`
  - The array of source information for the properties of a given feature, with each entry being a source object which lists the property in JSON Pointer notation and the dataset that specific value came from. All features must have a root level source which is the default source if a specific property's source is not specified
* [RECORD]    `sources.list`
* [RECORD]    `sources.list.element`
* [STRING]    `sources.list.element.property`
* [STRING]    `sources.list.element.dataset`
* [STRING]    `sources.list.element.record_id`
* [FLOAT]     `sources.list.element.confidence`
* [STRING]    `subtype`
  - Broad category of transportation segment (road, rail, water)
* [RECORD]    `names`
  - The used name when referring to a feature. The first entry in the array of names must have a language of "local" making it the easiest, default name to use among all options
* [STRING]    `names.primary`
* [RECORD]    `names.common`
* [RECORD]    `names.common.key_value`
* [STRING]    `names.common.key_value.key`
* [STRING]    `names.common.key_value.value`
* [RECORD]    `names.rules`
* [RECORD]    `names.rules.list`
* [RECORD]    `names.rules.list.element`
* [STRING]    `names.rules.list.element.variant`
* [STRING]    `names.rules.list.element.language`
* [STRING]    `names.rules.list.element.value`
* [RECORD]    `names.rules.list.element.between`
* [RECORD]    `names.rules.list.element.between.list`
* [FLOAT]     `names.rules.list.element.between.list.element`
* [STRING]    `names.rules.list.element.side`
* [STRING]    `class`
* [RECORD]    `connector_ids`
  - List of connectors this segment is physically connected to. Each connector is a possible routing decision point meaning it defines place along segment in which there is possibility to transition to other segments which share same connector
* [RECORD]    `connector_ids.list`
* [STRING]    `connector_ids.list.element`
* [STRING]    `road`
  - Properties for segments whose segment subType is road. The road subType includes any variety of road, street, or path, including dedicated paths for walking and cycling.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
