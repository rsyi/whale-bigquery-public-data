# `overture_maps.water`
`bq-1` | `bigquery-public-data`
Features in the water theme are from OpenStreetMap features with the natural=water tag.
The Overture base theme provides the land and water features that are necessary to render a complete basemap. These features are currently derived from the Daylight Earth Tables schema and include the Daylight Coastlines.
Founded in 2022 under the Joint Development Foundation, Overture Maps Foundation (Overture Maps) is dedicated to the development of reliable, easy-to-use, and interoperable open map data that will power current and next-generation map products. We build this data through a collaborative process that combines technology, data, and support from a wide range of companies. Map data are assembled from multiple sources including members, civic organizations, and open data sources.

## Column details
* [STRING]    `id`
  - A feature ID. This may be an ID associated with the Global Entity Reference System (GERS) if—and-only-if the feature represents an entity that is part of GERS.
* [GEOGRAPHY] `geometry`
  - Geometry of a physical representation of inland and ocean marine surfaces.
* [RECORD]    `bbox`
  - Area defined by two longitudes and two latitudes, where: Latitude is a decimal number between -90.0 and 90.0. Longitude is a decimal number between -180.0 and 180.0.
* [FLOAT]     `bbox.xmin`
* [FLOAT]     `bbox.xmax`
* [FLOAT]     `bbox.ymin`
* [FLOAT]     `bbox.ymax`
* [INTEGER]   `version`
  - Version number of the feature, incremented in each Overture release where the geometry or attributes of this feature changed.
* [STRING]    `update_time`
  - Timestamp when the feature was last updated.
* [RECORD]    `sources`
  - The array of source information for the properties of a given feature, with each entry being a source object which lists the property in JSON Pointer notation and the dataset that specific value came from. All features must have a root level source which is the default source if a specific property's source is not specified.
* [RECORD]    `sources.list`
* [RECORD]    `sources.list.element`
* [STRING]    `sources.list.element.property`
* [STRING]    `sources.list.element.dataset`
* [STRING]    `sources.list.element.record_id`
* [FLOAT]     `sources.list.element.confidence`
* [STRING]    `subtype`
  - The type of water body such as an river, ocean or lake.
* [STRING]    `wikidata`
  - A wikidata ID if available, as found on https://www.wikidata.org/.
* [RECORD]    `names`
  - The used name when referring to a feature. The first entry in the array of names must have a language of "local" making it the easiest, default name to use among all options.
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
  - Further description of the type of water
* [RECORD]    `source_tags`
  - Any attributes/tags from the original source data that should be passed through.
* [RECORD]    `source_tags.key_value`
* [STRING]    `source_tags.key_value.key`
* [STRING]    `source_tags.key_value.value`
* [BOOLEAN]   `is_salt`
  - Is it salt water or not.
* [BOOLEAN]   `is_intermittent`
  - Is it intermittent water or not.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
