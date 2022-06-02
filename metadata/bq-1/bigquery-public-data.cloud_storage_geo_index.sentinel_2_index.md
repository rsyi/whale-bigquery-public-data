# `cloud_storage_geo_index.sentinel_2_index`
`bq-1` | `bigquery-public-data`
Sentinel 2 table

## Column details
* [STRING]    `granule_id`
  - Unique identifier for a particular Sentinel-2 image granule.
* [STRING]    `product_id`
  - Unique identifier for a particular set of Sentinel-2 granules processed by ESA at a particular time.
* [STRING]    `datatake_identifier`
  - Identifier for a particular Sentinel-2 satellite image acquisition, which may be divided into multiple granules and products for processing. 
* [STRING]    `mgrs_tile`
  - The location of this granule in the Military Grid Reference System.
* [TIMESTAMP] `sensing_time`
  - The approximate time at which this granule was acquired (UTC).
* [STRING]    `geometric_quality_flag`
  - Indicates whether the granule 'PASSED' or 'FAILED' the assessment of geometric quality (i.e. spatial image alignment).
* [TIMESTAMP] `generation_time`
  - The time at which this granule was processed.
* [FLOAT]     `north_lat`
  - The northern latitude of the bounding box of this granule.
* [FLOAT]     `south_lat`
  - The southern latitude of the bounding box of this granule.
* [FLOAT]     `west_lon`
  - The western longitude of the bounding box of this granule.
* [FLOAT]     `east_lon`
  - The eastern longitude of the bounding box of this granule.
* [STRING]    `base_url`
  - The base URL for this granule in Cloud Storage.
* [INTEGER]   `total_size`
  - The total size of this scene in bytes.
* [FLOAT]     `cloud_cover`
  - Estimated percentage of this scene affected by cloud cover.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
