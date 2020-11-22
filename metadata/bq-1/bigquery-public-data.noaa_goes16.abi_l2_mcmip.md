# `noaa_goes16.abi_l2_mcmip`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `dataset_name`
  - Dataset filename.
* [STRING]    `platform_id`
  - Identifier for the GOES satellite. Possible values are "G16" and "G17". Currently, "G16".
* [STRING]    `orbital_slot`
  - Designated operating slot for the satellite. Possible values are "GOES-East", "GOES-West", "GOES-Test", and "GOES-Storage". Currently, "GOES-East".
* [STRING]    `timeline_id`
  - ABI scanning mode of operation. Possible values are "ABI Mode 3" and "ABI Mode 4". Full Disk images are generated in ABI scanning Mode 3 and 4, while Mesoscale and CONUS images are only generated in ABI scanning Mode 3.
* [STRING]    `scene_id`
  - One of three geographic coverage regions imaged by ABI. Possible values are "Full Disk", "CONUS", and "Mesoscale".
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
* [INTEGER]   `outlier_pixel_count_c01`
  - Number of band 1 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c02`
  - Number of band 2 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c03`
  - Number of band 3 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c04`
  - Number of band 4 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c05`
  - Number of band 5 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c06`
  - Number of band 6 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c07`
  - Number of band 7 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c08`
  - Number of band 8 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c09`
  - Number of band 9 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c10`
  - Number of band 10 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c11`
  - Number of band 11 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c12`
  - Number of band 12 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c13`
  - Number of band 13 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c14`
  - Number of band 14 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c15`
  - Number of band 15 cloud and moisture imagery pixels with values outside the valid measurement range.
* [INTEGER]   `outlier_pixel_count_c16`
  - Number of band 16 cloud and moisture imagery pixels with values outside the valid measurement range.
* [FLOAT]     `min_reflectance_factor_c01`
  - Minimum reflectance factor value for band 1 of good and conditionally usable quality pixels.
* [FLOAT]     `max_reflectance_factor_c01`
  - Maximum reflectance factor value for band 1 of good and conditionally usable quality pixels.
* [FLOAT]     `mean_reflectance_factor_c01`
  - Mean reflectance factor value for band 1 of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_reflectance_factor_c01`
  - Standard deviation of reflectance factor values for band 1 of good and conditionally usable quality pixels.
* [FLOAT]     `min_reflectance_factor_c02`
  - minimum reflectance factor value of band 2 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `max_reflectance_factor_c02`
  - maximum reflectance factor value of band 2 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `mean_reflectance_factor_c02`
  - mean reflectance factor value of band 2 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `std_dev_reflectance_factor_c02`
  - standard deviation of reflectance factor values of band 2 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `min_reflectance_factor_c03`
  - minimum reflectance factor value of band 3 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `max_reflectance_factor_c03`
  - maximum reflectance factor value of band 3 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `mean_reflectance_factor_c03`
  - mean reflectance factor value of band 3 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `std_dev_reflectance_factor_c03`
  - standard deviation of reflectance factor values of band 3 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `min_reflectance_factor_c04`
  - minimum reflectance factor value of band 4 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `max_reflectance_factor_c04`
  - maximum reflectance factor value of band 4 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `mean_reflectance_factor_c04`
  - mean reflectance factor value of band 4 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `std_dev_reflectance_factor_c04`
  - standard deviation of reflectance factor values of band 4 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `min_reflectance_factor_c05`
  - minimum reflectance factor value of band 5 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `max_reflectance_factor_c05`
  - maximum reflectance factor value of band 5 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `mean_reflectance_factor_c05`
  - mean reflectance factor value of band 5 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `std_dev_reflectance_factor_c05`
  - standard deviation of reflectance factor values of band 5 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `min_reflectance_factor_c06`
  - minimum reflectance factor value of band 6 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `max_reflectance_factor_c06`
  - maximum reflectance factor value of band 6 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `mean_reflectance_factor_c06`
  - mean reflectance factor value of band 6 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `std_dev_reflectance_factor_c06`
  - standard deviation of reflectance factor values of band 6 pixels - good and conditionally usable quality pixels only
* [FLOAT]     `min_brightness_temperature_c07`
  - Minimum brightness temperature value for band 7 of good and conditionally usable quality pixels.
* [FLOAT]     `max_brightness_temperature_c07`
  - Maximum brightness temperature value for band 7 of good and conditionally usable quality pixels.
* [FLOAT]     `mean_brightness_temperature_c07`
  - Mean brightness temperature value for band 7 of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_brightness_temperature_c07`
  - Standard deviation of brightness temperature values for band 7 of good and conditionally usable quality pixels.
* [FLOAT]     `min_brightness_temperature_c08`
  - Minimum brightness temperature value for band 8 of good and conditionally usable quality pixels.
* [FLOAT]     `max_brightness_temperature_c08`
  - Maximum brightness temperature value for band 8 of good and conditionally usable quality pixels.
* [FLOAT]     `mean_brightness_temperature_c08`
  - Mean brightness temperature value for band 8 of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_brightness_temperature_c08`
  - Standard deviation of brightness temperature values for band 8 of good and conditionally usable quality pixels.
* [FLOAT]     `min_brightness_temperature_c09`
  - Minimum brightness temperature value for band 9 of good and conditionally usable quality pixels.
* [FLOAT]     `max_brightness_temperature_c09`
  - Maximum brightness temperature value for band 9 of good and conditionally usable quality pixels.
* [FLOAT]     `mean_brightness_temperature_c09`
  - Mean brightness temperature value for band 9 of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_brightness_temperature_c09`
  - Standard deviation of brightness temperature values for band 9 of good and conditionally usable quality pixels.
* [FLOAT]     `min_brightness_temperature_c10`
  - Minimum brightness temperature value for band 10 of good and conditionally usable quality pixels.
* [FLOAT]     `max_brightness_temperature_c10`
  - Maximum brightness temperature value for band 10 of good and conditionally usable quality pixels.
* [FLOAT]     `mean_brightness_temperature_c10`
  - Mean brightness temperature value for band 10 of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_brightness_temperature_c10`
  - Standard deviation of brightness temperature values for band 10 of good and conditionally usable quality pixels.
* [FLOAT]     `min_brightness_temperature_c11`
  - Minimum brightness temperature value for band 11 of good and conditionally usable quality pixels.
* [FLOAT]     `max_brightness_temperature_c11`
  - Maximum brightness temperature value for band 11 of good and conditionally usable quality pixels.
* [FLOAT]     `mean_brightness_temperature_c11`
  - Mean brightness temperature value for band 11 of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_brightness_temperature_c11`
  - Standard deviation of brightness temperature values for band 11 of good and conditionally usable quality pixels.
* [FLOAT]     `min_brightness_temperature_c12`
  - Minimum brightness temperature value for band 12 of good and conditionally usable quality pixels.
* [FLOAT]     `max_brightness_temperature_c12`
  - Maximum brightness temperature value for band 12 of good and conditionally usable quality pixels.
* [FLOAT]     `mean_brightness_temperature_c12`
  - Mean brightness temperature value for band 12 of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_brightness_temperature_c12`
  - Standard deviation of brightness temperature values for band 12 of good and conditionally usable quality pixels.
* [FLOAT]     `min_brightness_temperature_c13`
  - Minimum brightness temperature value for band 13 of good and conditionally usable quality pixels.
* [FLOAT]     `max_brightness_temperature_c13`
  - Maximum brightness temperature value for band 13 of good and conditionally usable quality pixels.
* [FLOAT]     `mean_brightness_temperature_c13`
  - Mean brightness temperature value for band 13 of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_brightness_temperature_c13`
  - Standard deviation of brightness temperature values for band 13 of good and conditionally usable quality pixels.
* [FLOAT]     `min_brightness_temperature_c14`
  - Minimum brightness temperature value for band 14 of good and conditionally usable quality pixels.
* [FLOAT]     `max_brightness_temperature_c14`
  - Maximum brightness temperature value for band 14 of good and conditionally usable quality pixels.
* [FLOAT]     `mean_brightness_temperature_c14`
  - Mean brightness temperature value for band 14 of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_brightness_temperature_c14`
  - Standard deviation of brightness temperature values for band 14 of good and conditionally usable quality pixels.
* [FLOAT]     `min_brightness_temperature_c15`
  - Minimum brightness temperature value for band 15 of good and conditionally usable quality pixels.
* [FLOAT]     `max_brightness_temperature_c15`
  - Maximum brightness temperature value for band 15 of good and conditionally usable quality pixels.
* [FLOAT]     `mean_brightness_temperature_c15`
  - Mean brightness temperature value for band 15 of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_brightness_temperature_c15`
  - Standard deviation of brightness temperature values for band 15 of good and conditionally usable quality pixels.
* [FLOAT]     `min_brightness_temperature_c16`
  - Minimum brightness temperature value for band 16 of good and conditionally usable quality pixels.
* [FLOAT]     `max_brightness_temperature_c16`
  - Maximum brightness temperature value for band 16 of good and conditionally usable quality pixels.
* [FLOAT]     `mean_brightness_temperature_c16`
  - Mean brightness temperature value for band 16 of good and conditionally usable quality pixels.
* [FLOAT]     `std_dev_brightness_temperature_c16`
  - Standard deviation of brightness temperature values for band 16 of good and conditionally usable quality pixels.
* [FLOAT]     `percent_uncorrectable_grb_errors`
  - Percentage of data lost due to uncorrectable GRB errors.
* [FLOAT]     `percent_uncorrectable_l0_errors`
  - Percentage of data lost due to uncorrectable L0 errors.
* [FLOAT]     `min_brightness_temperature_c06`
* [FLOAT]     `max_brightness_temperature_c06`
* [FLOAT]     `mean_brightness_temperature_c06`
* [FLOAT]     `std_dev_brightness_temperature_c06`
* [INTEGER]   `total_size`
  - Size of the underlying .nc file(s) in bytes.
* [STRING]    `base_url`
  - Location in Google Cloud Storage for the underlying source file.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
