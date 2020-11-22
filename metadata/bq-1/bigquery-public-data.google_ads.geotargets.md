# `google_ads.geotargets`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `criteria_id`
  - Unique and persistent assigned ID.
* [STRING]    `en_name`
  - Best available English name of the geo target.
* [STRING]    `canonical_name`
  - The constructed fully qualified English name consisting of the target's own name, and that of its parent and country. This field is meant only for disambiguating similar target names.
* [STRING]    `parent_id`
  - The criteria ID of a parent. This field is included for legacy support, and the IDs may not be consistent across datasets.
* [STRING]    `country_code`
  - The ISO-3166-1 alpha-2 country code that is associated with the target.
* [STRING]    `display_feature_type`
  - Type of geography. Allowed values: Airport, Autonomous Community, Borough, Canton, City, City Region, Congressional District, Country, County, Department, District, Governorate, Municipality, National Park, Neighborhood, Okrug, Postal Code, Prefecture, Province, Region, State, Territory, TV Region, Union Territory, University,
* [STRING]    `status`
  - Status of the given feature. Allowable values: Active - Location is currently valid; Removal Planned - Location is obsolete and will be removed in the next version

-------------------------------------------------------------------------------
*Do not make edits above this line.*
