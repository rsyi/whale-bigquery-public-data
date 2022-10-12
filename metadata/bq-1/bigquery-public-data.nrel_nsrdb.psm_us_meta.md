# `nrel_nsrdb.psm_us_meta`
`bq-1` | `bigquery-public-data`

## Column details
* [FLOAT]     `latitude`
  - Latitude of the grid-cell centroid. PSM is on a nominal 4km grid
* [FLOAT]     `longitude`
  - Longitude of the grid-cell centroid. PSM is on a nominal 4km grid
* [FLOAT]     `elevation`
  - Elevation of the grid-cell centroid sourced from SRTM
* [INTEGER]   `timezone`
  - Time zone of grid-cell centroid
* [STRING]    `country`
  - Country of the grid-cell identified using Natural Earth vectors
* [STRING]    `state`
  - State of the grid-cell identified using Natural Earth vectors
* [STRING]    `county`
  - County of the grid-cell identified using Natural Earth vectors
* [STRING]    `urban`
  - Urban name of the grid-cell identified using Natural Earth vectors
* [INTEGER]   `fname`
  - fname is used to identify the grid-cell of interest in the psm time series table [psm_us_2016]. Likewise, it can be used to identify associated .CSV files in GCP Storage Bucket: gs//gcp-public-data-nrel-nsrdb

-------------------------------------------------------------------------------
*Do not make edits above this line.*
