# `cloud_storage_geo_index.landsat_index`
`bigquery`| `bigquery-public-data`

## Column details
* [STRING]    `scene_id`
 - Unique identifier for a particular Landsat image downlinked to a particular ground station.
* [STRING]    `product_id`
 - Unique identifier for a particular scene processed by the USGS at a particular time, or null for pre-collection data.
* [STRING]    `spacecraft_id`
 - The spacecraft that acquired this scene: one of 'LANDSAT_4' through 'LANDSAT_8'.
* [STRING]    `sensor_id`
 - The type of spacecraft sensor that acquired this scene: 'TM' for the Thematic Mapper, 'ETM' for the Enhanced Thematic Mapper+, or 'OLI/TIRS' for the Operational Land Imager and Thermal Infrared Sensor.
* [STRING]    `date_acquired`
 - The date on which this scene was acquired (UTC).
* [STRING]    `sensing_time`
 - The approximate time at which this scene was acquired (UTC).
* [STRING]    `collection_number`
 - The Landsat collection that this image belongs to, e.g. '01' for Collection 1 or 'PRE' for pre-collection data.
* [STRING]    `collection_category`
 - Indicates the processing level of the image: 'RT' for real-time, 'T1' for Tier 1, 'T2' for Tier 2, and 'N/A' for pre-collection data. RT images will be replaced with Tier 1 or Tier 2 images as they become available.
* [STRING]    `data_type`
 - The type of processed image, e.g. 'L1T' for Level 1 terrain-corrected images.
* [INTEGER]   `wrs_path`
 - The path number of this scene's location in the Worldwide Reference System (WRS).
* [INTEGER]   `wrs_row`
 - The row number of this scene's location in the Worldwide Reference System (WRS).
* [FLOAT]     `cloud_cover`
 - Estimated percentage of this scene affected by cloud cover.
* [FLOAT]     `north_lat`
 - The northern latitude of the bounding box of this scene.
* [FLOAT]     `south_lat`
 - The southern latitude of the bounding box of this scene.
* [FLOAT]     `west_lon`
 - The western longitude of the bounding box of this scene.
* [FLOAT]     `east_lon`
 - The eastern longitude of the bounding box of this scene.
* [INTEGER]   `total_size`
 - The total size of this scene in bytes.
* [STRING]    `base_url`
 - The base URL for this scene in Cloud Storage.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
