# `utility_eu.time`
`bq-1` | `bigquery-public-data`

## Column details
* [TIME]      `time`
  - Time as TIME - CAST('23:59:59' AS TIME)
* [INTEGER]   `hour`
  - Hour as INTEGER - [0, 23]
* [INTEGER]   `minute`
  - Minute as INTEGER - [0, 59]
* [INTEGER]   `second`
  - Second as INTEGER - [0, 59]
* [INTEGER]   `second_in_day`
  - Seconds as INTEGER - [0, 86399]; 00:00:00 = 0, 23:59:59 = 86399
* [INTEGER]   `hour_ampm`
  - Hour as INTEGER - [1, 12]
* [BOOLEAN]   `is_pm`
  - AM = False, PM = True

-------------------------------------------------------------------------------
*Do not make edits above this line.*
