# `nrel_nsrdb.psm_us_2016`
`bq-1` | `bigquery-public-data`
The NSRDB is a serially complete collection of hourly and half-hourly values of the three most common measurements of solar radiation—global horizontal, direct normal, and diffuse horizontal irradiance—and meteorological data. 

The current version of the NSRDB (v3.0.0) was developed using the Physical Solar Model (PSM).

For more details, please visit: nsrdb.nrel.gov

## Column details
* [DATETIME]  `time_utc`
  - Date time of instantaneous irradiance (UTC)
* [FLOAT]     `dhi`
  - Direct Horizontal Irradiance (w/m2)
* [FLOAT]     `dni`
  - Direct Normal Irradiance (w/m2)
* [FLOAT]     `wind_speed`
  - Wind Speed at 2-meters (m/s)
* [FLOAT]     `air_temperature`
  - Temperature at 2-meters (Celsius)
* [INTEGER]   `fname`
  - fname is used to identify the grid-cell of interest identified in the [psm_us_meta] table - a table that stores locational information of each grid-cell. Likewise, it can be used to identify associated .CSV files in GCP Storage Bucket: gs//gcp-public-data-nrel-nsrdb

-------------------------------------------------------------------------------
*Do not make edits above this line.*
