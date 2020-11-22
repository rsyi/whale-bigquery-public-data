# `noaa_goes17.abi_l1b_radiance`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `dataset_name`
  - Dataset filename.
* [STRING]    `platform_id`
  - Identifier for the GOES satellite. Possible values are "G16" and "G17". Currently, "G17".
* [STRING]    `orbital_slot`
  - Designated operating slot for the satellite. Possible values are "GOES-East", "GOES-West", "GOES-Test", and "GOES-Storage". Currently, "GOES-West".
* [STRING]    `timeline_id`
  - ABI scanning mode of operation. Possible values are "ABI Mode 3" and "ABI Mode 4". Full Disk images are generated in ABI scanning Mode 3 and 4, while Mesoscale and CONUS images are only generated in ABI scanning Mode 3.
* [STRING]    `scene_id`
  - One of three geographic coverage regions imaged by ABI. Possible values are "Full Disk", "CONUS", and "Mesoscale".
* [STRING]    `band_id`
  - ABI band or channel number. Possible values are "01" through "16".
* [TIMESTAMP] `time_coverage_start`
  - Date and time of the first data point in the dataset (UTC). Format is YYYY-MM-DD”T”HH:MM:SS.s”Z”.
* [TIMESTAMP] `time_coverage_end`
  - Date and time of the last data point in the dataset (UTC). Format is YYYY-MM-DD”T”HH:MM:SS.s”Z”.
* [TIMESTAMP] `date_created`
  - Date and time when dataset file was created (UTC). Format is YYYY-MM-DD”T”HH:MM:SS.s”Z”.
* [FLOAT]     `geospatial_westbound_longitude`
  - Westernmost longitude in decimal degrees covered by the dataset.
* [FLOAT]     `geospatial_northbound_latitude`
  - Northernmost latitude in decimal degrees covered by the dataset.
* [FLOAT]     `geospatial_eastbound_longitude`
  - Easternmost longitude in decimal degrees covered by the dataset.
* [FLOAT]     `geospatial_southbound_latitude`
  - Southernmost latitude in decimal degrees covered by the dataset.
* [FLOAT]     `nominal_satellite_subpoint_lon`
  - Longitude of satellite subpoint in decimal degrees.
* [INTEGER]   `valid_pixel_count`
  - Number of good and conditionally usable quality pixels.
* [INTEGER]   `missing_pixel_count`
  - Number of missing pixels on ABI fixed grid.
* [INTEGER]   `saturated_pixel_count`
  - Number of radiometrically saturated geolocated/not missing pixels.
* [INTEGER]   `undersaturated_pixel_count`
  - Number of radiometrically undersaturated geolocated/not missing pixels.
* [FLOAT]     `min_radiance_value_of_valid_pixels`
  - Minimum radiance value of good and conditionally usable quality pixels.
* [FLOAT]     `max_radiance_value_of_valid_pixels`
  - Maximum radiance value of good and conditionally usable quality pixels.
* [FLOAT]     `mean_radiance_value_of_valid_pixels`
  - Mean radiance value of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_radiance_value_of_valid_pixels`
  - Standard deviation of radiance values of good and conditionally usable quality pixels.
* [FLOAT]     `percent_uncorrectable_l0_errors`
  - Percentage of data lost due to uncorrectable L0 errors.
* [INTEGER]   `total_size`
  - Size of the underlying .nc file(s) in bytes.
* [STRING]    `base_url`
  - Location in Google Cloud Storage for the underlying source file.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
