# `overture_maps.division_area`
`bq-1` | `bigquery-public-data`
The Overture Maps divisions theme includes features that represent human settlements in the real world, such as countries, regions, states, cities and towns. 

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
  - Timestamp when the feature was last updated
* [RECORD]    `sources`
  - The array of source information for the properties of a given feature, with each entry being a source object which lists the property in JSON Pointer notation and the dataset that specific value came from. All features must have a root level source which is the default source if a specific property's source is not specified.
* [RECORD]    `sources.list`
* [RECORD]    `sources.list.element`
* [STRING]    `sources.list.element.property`
* [STRING]    `sources.list.element.dataset`
* [STRING]    `sources.list.element.record_id`
* [FLOAT]     `sources.list.element.confidence`
* [STRING]    `subtype`
  - Like a division, a division area may have one of two possible sub-types: country or region.
* [STRING]    `wikidata`
  - A wikidata ID if available, as found on https://www.wikidata.org/.
* [INTEGER]   `population`
  - Population of the division
* [RECORD]    `names`
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
  - Possible variables: land / maritime
* [RECORD]    `divisions`
  - The two divisions to the left and right, respectively, of the boundary line, along with an indication of whether they dispute the boundary. The left- and right-hand sides of the boundary are considered from the perspective of a person standing on the line facing in the direction in which the geometry is oriented, i.e. facing toward the end of the line. The first array element represents the left division. The second element represents the right division.
* [RECORD]    `divisions.list`
* [RECORD]    `divisions.list.element`
* [STRING]    `divisions.list.element.division_id`
* [BOOLEAN]   `divisions.list.element.is_disputing`
* [RECORD]    `local_type`
* [RECORD]    `local_type.key_value`
* [STRING]    `local_type.key_value.key`
* [STRING]    `local_type.key_value.value`
* [STRING]    `country`
  - ISO 3166-1 alpha-2 country code.
* [STRING]    `region`
  - ISO 3166-2 principal subdivision code.
* [RECORD]    `hierarchies`
  - Hierarchies in which this division participates. Every division participates in at least one hierarchy. Most participate in only one. Some divisions may participate in more than one hierarchy, for example if they are claimed by different parent divisions from different political perspectives; or if there are other real-world reasons why the division or one of its ancestors has multiple parents. The first hierarchy in the list is the default hierarchy, and the second-to-last entry in the default hierarchy (if there is such an entry) always corresponds to the `parent_division_id' property. The ordering of hierarchies after the first one is arbitrary.
* [RECORD]    `hierarchies.list`
* [RECORD]    `hierarchies.list.element`
* [RECORD]    `hierarchies.list.element.list`
* [RECORD]    `hierarchies.list.element.list.element`
* [STRING]    `hierarchies.list.element.list.element.division_id`
* [STRING]    `hierarchies.list.element.list.element.subtype`
* [STRING]    `hierarchies.list.element.list.element.name`
* [STRING]    `parent_division_id`
  - A feature ID. This may be an ID associated with the Global Entity Reference System (GERS) if—and-only-if the feature represents an entity that is part of GERS.
* [RECORD]    `perspectives`
  - Political perspectives from which this division is considered to be an accurate representation. If this property is absent, then this division is seen from the default political perspective. If this property is present, then this division is seen from the political perspectives enumerated in the list.
* [RECORD]    `perspectives.list`
* [RECORD]    `perspectives.list.element`
* [STRING]    `perspectives.list.element.type`
* [STRING]    `perspectives.list.element.holder`
* [RECORD]    `norms`
  - Collects information about local norms and rules within the division that are generally useful for mapping and map-related use cases. If the norms property or a desired sub-property of the norms property is missing on a division, but at least one of its ancestor divisions has the norms property and the desired sub-property, then the value from the nearest ancestor division may be assumed.
* [STRING]    `norms.driving_side`
* [STRING]    `capital_division_id`
  - A feature ID. This may be an ID associated with the Global Entity Reference System (GERS) if—and-only-if the feature represents an entity that is part of GERS.
* [STRING]    `division_id`
  - A feature ID. This may be an ID associated with the Global Entity Reference System (GERS) if—and-only-if the feature represents an entity that is part of GERS.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
