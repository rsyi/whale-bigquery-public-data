# `noaa_goes16.glm_l2_lcfa`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `dataset_name`
  - Dataset filename.
* [STRING]    `platform_ID`
  - Identifier for the GOES satellite. Possible values are "G16" and "G17". Currently, "G16".
* [STRING]    `orbital_slot`
  - Designated operating slot for the satellite. Possible values are "GOES-East", "GOES-West", "GOES-Test", and "GOES-Storage". Currently, "GOES-East".
* [TIMESTAMP] `time_coverage_start`
  - Date and time of the first data point in the dataset (UTC). Format is YYYY-MM-DD”T”HH:MM:SS.s”Z”.
* [TIMESTAMP] `time_coverage_end`
  - Date and time of the last data point in the dataset (UTC). Format is YYYY-MM-DD”T”HH:MM:SS.s”Z”.
* [TIMESTAMP] `date_created`
  - Date and time when dataset file was created (UTC). Format is YYYY-MM-DD”T”HH:MM:SS.s”Z”.
* [FLOAT]     `group_time_threshold`
  - Lightning group maximum time difference among lightning events in a group in seconds.
* [FLOAT]     `flash_time_threshold`
  - Lightning flash maximum time difference among lightning events in a flash in seconds.
* [INTEGER]   `event_count`
  - Count number of lightning events in product.
* [INTEGER]   `group_count`
  - Count number of lightning groups in product.
* [FLOAT]     `flash_count`
  - Count number of lightning flashes in product.
* [FLOAT]     `percent_navigated_L1b_events`
  - Percent of lightning events navigated by instrument after false event filtering.
* [FLOAT]     `percent_uncorrectable_L0_errors`
  - Percentage of data lost due to uncorrectable L0 errors.
* [STRING]    `total_size`
  - Size of the underlying .nc file(s) in bytes.
* [STRING]    `base_url`
  - Location in Google Cloud Storage for the underlying source file.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
