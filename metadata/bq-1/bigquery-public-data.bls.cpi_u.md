# `bls.cpi_u`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `series_id`
  - Code identifying the specific series
* [INTEGER]   `year`
  - Identifies year of observation
* [STRING]    `period`
  - Identifies period for which data is observed. M01 = January, M02 = February….M13 = Annual Average
* [FLOAT]     `value`
  - Price index for item
* [STRING]    `footnote_codes`
  - Identifies footnote for the data series
* [STRING]    `survey_abbreviation`
  - Code identifying the survey
* [STRING]    `seasonal_code`
  - Code identifying whether the data are seasonally adjusted. S = Seasonally Adjusted, U = Unadjusted
* [STRING]    `periodicity_code`
  - Frequency of data observation. R = Monthly, S = Semi-Annual
* [STRING]    `area_code`
  - Unique code used to identify a specific geographic area. Full area codes found here: http://download.bls.gov/pub/time.series/cu/cu.area
* [STRING]    `area_name`
  - Name of specific geographic area.
* [STRING]    `item_code`
  - Identifies item for which data observations pertain. Full item codes found here: http://download.bls.gov/pub/time.series/cu/cu.item
* [STRING]    `item_name`
  - Full names of items.
* [DATE]      `date`
  - Specifies period in date format. M01 -> [year]-01-01...., M12 -> [year]-12-01, M13 -> [year]-12-31, Q01 -> [year]-01-15...., Q04 -> [year]-10-15, Q05 -> [year]-12-31, S01 -> [year]-06-30, S02 -> [year]-12-30, S03 -> [year]-12-31, A01 -> [year]-12-31

-------------------------------------------------------------------------------
*Do not make edits above this line.*
