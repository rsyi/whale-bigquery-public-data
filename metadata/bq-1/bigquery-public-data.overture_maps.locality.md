# `overture_maps.locality`
`bq-1` | `bigquery-public-data`
Localities are named, and typically populated, areas. Administrative Localities represent countries and hierarchical subdivisions of countries. Every Administrative Locality has a valid adminLevel property set, defining its position in the subdivision hierarchy. All Administrative Localities at sub-country level must have a contextId property containing the GERS ID of the feature's parent Administrative Locality. The borders of Administrative Localities, if known, are given by Administrative Boundary features. Named Localities represent named areas which are not formally part of the hierarchical subdivision of a country (are not Administrative Localities). Localities are named, populated areas. If a locality is a country or an official subdivision of a country, it will have adminLevel property set and its subType will be an administrativeLocality. Otherwise, adminLevel property will not be set and its subType will be a namedLocality.


Founded in 2022 under the Joint Development Foundation, Overture Maps Foundation (Overture Maps) is dedicated to the development of reliable, easy-to-use, and interoperable open map data that will power current and next-generation map products. We build this data through a collaborative process that combines technology, data, and support from a wide range of companies. Map data are assembled from multiple sources including members, civic organizations, and open data sources.

## Column details
* [STRING]    `id`
  - Feature ID. This may be an ID associated with the Global Entity Reference System (GERS) if—and-only-if the feature represents an entity that is part of GERS.
* [GEOGRAPHY] `geometry`
  - Geometry for the administratie boundary
* [RECORD]    `bbox`
  - Area defined by two longitudes and two latitudes, where: Latitude is a decimal number between -90.0 and 90.0. Longitude is a decimal number between -180.0 and 180.0
* [FLOAT]     `bbox.xmin`
* [FLOAT]     `bbox.xmax`
* [FLOAT]     `bbox.ymin`
* [FLOAT]     `bbox.ymax`
* [INTEGER]   `admin_level`
  - Hierarchical level for administrative entity or border (matching admin_level in OSM taxonomy)
* [BOOLEAN]   `is_maritime`
  - Flag that specifies if feature is maritime (i.e., a boundary at a particular distance from a jurisdiction's coastline)
* [STRING]    `geopol_display`
  - Optional value that indicates if the boundary needs special rendering logic
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
  - Subtype of admin area
* [STRING]    `locality_type`
  - Describes the entity's type in the categorical nomenclature used locally.
* [STRING]    `wikidata`
  - A wikidata ID if available, as found on https://www.wikidata.org/.
* [STRING]    `context_id`
  - Context entity is the most granular entity that logically contains given entity (but doesn't have to contain it spatially due to minor discrepancies in geometries)
* [INTEGER]   `population`
  - Population in the administrative boundary.
* [STRING]    `iso_country_code_alpha_2`
  - ISO 3166-1 alpha-2 country code.
* [STRING]    `iso_sub_country_code`
  - ISO-3166-2 Country subdivision code.
* [STRING]    `default_language`
  - Area's official language in ISO 3166-1 alpha-2 country code.
* [STRING]    `driving_side`
  - Left-hand traffic (LHT) or right-hand traffic (RHT).
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
* [STRING]    `locality_id`
  - Propoerty localityId points at the Locality feature that this area belongs to.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
