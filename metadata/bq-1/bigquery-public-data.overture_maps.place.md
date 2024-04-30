# `overture_maps.place`
`bq-1` | `bigquery-public-data`
A place is a business or point of interest within the world. A Place is a point representation of a real-world facility, service, or amenity.


Founded in 2022 under the Joint Development Foundation, Overture Maps Foundation (Overture Maps) is dedicated to the development of reliable, easy-to-use, and interoperable open map data that will power current and next-generation map products. We build this data through a collaborative process that combines technology, data, and support from a wide range of companies. Map data are assembled from multiple sources including members, civic organizations, and open data sources.

## Column details
* [STRING]    `id`
  - A feature ID. This may be an ID associated with the Global Entity Reference System (GERS) if—and-only-if the feature represents an entity that is part of GERS.
* [GEOGRAPHY] `geometry`
  - Place's geometry which MUST be a Point as defined by GeoJSON schema.
* [RECORD]    `bbox`
  - Area defined by two longitudes and two latitudes, where: Latitude is a decimal number between -90.0 and 90.0. Longitude is a decimal number between -180.0 and 180.0
* [FLOAT]     `bbox.xmin`
* [FLOAT]     `bbox.xmax`
* [FLOAT]     `bbox.ymin`
* [FLOAT]     `bbox.ymax`
* [INTEGER]   `version`
  - Version number of the feature, incremented in each Overture release where the geometry or attributes of this feature changed
* [STRING]    `update_time`
  - Timestamp when the feature was last updated.
* [RECORD]    `sources`
  - The array of source information for the properties of a given feature, with each entry being a source object which lists the property in JSON Pointer notation and the dataset that specific value came from. All features must have a root level source which is the default source if a specific property's source is not specified
* [RECORD]    `sources.list`
* [RECORD]    `sources.list.element`
* [STRING]    `sources.list.element.property`
* [STRING]    `sources.list.element.dataset`
* [STRING]    `sources.list.element.record_id`
* [FLOAT]     `sources.list.element.confidence`
* [RECORD]    `names`
  - The used names when referring to a feature. The first entry in the array of names must have a language of "local" making it the easiest, default name to use among all options.
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
* [RECORD]    `categories`
  - The categories of the place.
* [STRING]    `categories.main`
* [RECORD]    `categories.alternate`
* [RECORD]    `categories.alternate.list`
* [STRING]    `categories.alternate.list.element`
* [FLOAT]     `confidence`
  - The confidence of the existence of the place. It's a number between 0 and 1. 0 means that we're sure that the place doesn't exist (anymore). 1 means that we're sure that the place exists. If there's no value for the confidence, it means that we don't have any confidence information.
* [RECORD]    `websites`
  - The websites of the place.
* [RECORD]    `websites.list`
* [STRING]    `websites.list.element`
* [RECORD]    `socials`
  - The social media URLs of the place.
* [RECORD]    `socials.list`
* [STRING]    `socials.list.element`
* [RECORD]    `emails`
  - The email addresses of the place.
* [RECORD]    `emails.list`
* [STRING]    `emails.list.element`
* [RECORD]    `phones`
  - The phone numbers of the place.
* [RECORD]    `phones.list`
* [STRING]    `phones.list.element`
* [RECORD]    `brand`
  - The brand of the place. We consider a location with multiple brands as separate places, each with their own brand.
* [STRING]    `brand.wikidata`
* [RECORD]    `brand.names`
* [STRING]    `brand.names.primary`
* [RECORD]    `brand.names.common`
* [RECORD]    `brand.names.common.key_value`
* [STRING]    `brand.names.common.key_value.key`
* [STRING]    `brand.names.common.key_value.value`
* [RECORD]    `brand.names.rules`
* [RECORD]    `brand.names.rules.list`
* [RECORD]    `brand.names.rules.list.element`
* [STRING]    `brand.names.rules.list.element.variant`
* [STRING]    `brand.names.rules.list.element.language`
* [STRING]    `brand.names.rules.list.element.value`
* [RECORD]    `brand.names.rules.list.element.between`
* [RECORD]    `brand.names.rules.list.element.between.list`
* [FLOAT]     `brand.names.rules.list.element.between.list.element`
* [STRING]    `brand.names.rules.list.element.side`
* [RECORD]    `addresses`
  - The addresses of the place.
* [RECORD]    `addresses.list`
* [RECORD]    `addresses.list.element`
* [STRING]    `addresses.list.element.freeform`
* [STRING]    `addresses.list.element.locality`
* [STRING]    `addresses.list.element.postcode`
* [STRING]    `addresses.list.element.region`
* [STRING]    `addresses.list.element.country`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
