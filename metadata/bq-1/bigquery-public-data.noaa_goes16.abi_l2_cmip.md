# `noaa_goes16.abi_l2_cmip`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `dataset_name`
  - Dataset filename.
* [STRING]    `platform_id`
  - Identifier for the GOES satellite. Possible values are "G16" and "G17". Currently, "G16".
* [STRING]    `orbital_slot`
  - Designated operating slot for the satellite. Possible values are "GOES-East", "GOES-West", "GOES-East", and "GOES-Storage". Currently, "GOES-East".
* [STRING]    `timeline_id`
  - ABI scanning mode of operation. Possible values are "ABI Mode 3" and "ABI Mode 4". Full Disk images are generated in ABI scanning Mode 3 and 4, while Mesoscale and CONUS images are only generated in ABI scanning Mode 3.
* [STRING]    `scene_id`
  - One of three geographic coverage regions imaged by ABI. Possible values are "Full Disk", "CONUS", and "Mesoscale".
* [STRING]    `band_id`
  - ABI band or channel number. Possible values are "01" through "16". Bands 1 - 6 are reflectance factor values. Bands 7 - 16 are brightness temperature values.
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
* [INTEGER]   `total_number_of_points`
  - Number of geolocated/not missing pixels.
* [INTEGER]   `valid_pixel_count`
  - Number of good and conditionally usable quality pixels.
* [INTEGER]   `outlier_pixel_count`
  - Number of cloud and moisture imagery pixels with values outside the valid measurement range.
* [FLOAT]     `min_reflectance_factor`
  - Minimum reflectance factor value of good and conditionally usable quality pixels.
* [FLOAT]     `max_reflectance_factor`
  - Maximum reflectance factor value of good and conditionally usable quality pixels.
* [FLOAT]     `mean_reflectance_factor`
  - Mean reflectance factor value of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_reflectance_factor`
  - Standard deviation of reflectance factor values of good and conditionally usable quality pixels.
* [FLOAT]     `min_brightness_temperature`
  - Minimum brightness temperature value of good and conditionally usable quality pixels.
* [FLOAT]     `max_brightness_temperature`
  - Maximum brightness temperature value of good and conditionally usable quality pixels.
* [FLOAT]     `mean_brightness_temperature`
  - Mean brightness temperature value of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_brightness_temperature`
  - Standard deviation of brightness temperature values of good and conditionally usable quality pixels.
* [FLOAT]     `percent_uncorrectable_grb_errors`
  - Percentage of data lost due to uncorrectable GRB errors.
* [FLOAT]     `percent_uncorrectable_l0_errors`
  - Percentage of data lost due to uncorrectable L0 errors.
* [INTEGER]   `total_size`
  - Size of the underlying .nc file(s) in bytes.
* [STRING]    `base_url`
  - Location in Google Cloud Storage for the underlying source file.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
