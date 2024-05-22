# `overture_maps.building`
`bq-1` | `bigquery-public-data`
Buildings are human-made structures with roofs or interior spaces that are permanently or semi-permanently in one place. The most basic form of a building feature in the Overture Schema. The geometry is expected to be the most outer footprint (or roofprint if traced from satellite/aerial imagery) of a building. A building is a man-made structure with a roof that exists permanently in one place. 


Founded in 2022 under the Joint Development Foundation, Overture Maps Foundation (Overture Maps) is dedicated to the development of reliable, easy-to-use, and interoperable open map data that will power current and next-generation map products. We build this data through a collaborative process that combines technology, data, and support from a wide range of companies. Map data are assembled from multiple sources including members, civic organizations, and open data sources.

## Column details
* [STRING]    `id`
  - A feature ID. This may be an ID associated with the Global Entity Reference System (GERS) if—and-only-if the feature represents an entity that is part of GERS.
* [GEOGRAPHY] `geometry`
  - A regular building's geometry is defined as it's footprint or roofprint (if traced from aerial/satellite imagery). These MUST be a Polygon as defined by GeoJSON schema.
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
  - A broad category of the building type / purpose. When the current use of the building does not match the built purpose, the class should be set to represent the current use of the building.
* [INTEGER]   `level`
  - Properties defining feature Z-order, i.e., stacking order. Z-order of the feature where 0 is visual level.
* [BOOLEAN]   `has_parts`
  - Flag indicating whether the building has parts.
* [FLOAT]     `height`
  - Height of the building or part in meters. The height is the distance from the lowest point to the highest point.
* [INTEGER]   `num_floors`
  - Number of above-ground floors of the building or part.
* [FLOAT]     `min_height`
  - The height of the bottom part of building in meters. Used if a building or part of building starts above the ground level.
* [INTEGER]   `min_floor`
  - The "start" floor of this building or part. Indicates that the building or part is "floating" and its bottom-most floor is above ground level, usually because it is part of a larger building in which some parts do reach down to ground level. An example is a building that has an entry road or driveway at ground level into an interior courtyard, where part of the building bridges above the entry road. This property may sometimes be populated when min_height is missing and in these cases can be used as a proxy for min_height.
* [STRING]    `facade_color`
  - The color (name or color triplet) of the facade of a building or building part in hexadecimal.
* [STRING]    `facade_material`
  - The outer surface material of building facade.
* [STRING]    `roof_material`
  - The outermost material of the roof.
* [STRING]    `roof_shape`
  - The shape of the roof.
* [FLOAT]     `roof_direction`
  - Bearing of the roof ridge line.
* [STRING]    `roof_orientation`
  - Orientation of the roof shape relative to the footprint shape. Either "along" or "across".
* [STRING]    `roof_color`
  - The color (name or color triplet) of the roof of a building or building part in hexadecimal.
* [FLOAT]     `eave_height`
  - The height of the building eave in meters.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
