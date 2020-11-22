# `utility_us.date_greg`
`bq-1` | `bigquery-public-data`

## Column details
* [DATE]      `date`
  - Date as DATE - CAST('2000-12-31' AS DATE); [1582-10-15, 2199-12-31]
* [STRING]    `date_str`
  - Date as STRING - '20001231'
* [INTEGER]   `date_int`
  - Date as INTEGER - 20001231
* [STRING]    `date_dash`
  - Date as STRING - '2000-12-31'
* [STRING]    `date_slash`
  - Date as STRING - '2000/12/31'
* [INTEGER]   `day`
  - Day as Integer - [1, 31]
* [STRING]    `day_abbr`
  - Day as 3-letter STRING - [mon, tue, wed, thu, fri, sat, sun]
* [INTEGER]   `dow_mon17`
  - 1 = mon, 7 = sun ; https://en.wikipedia.org/wiki/ISO_week_date)
* [INTEGER]   `dow_mon06`
  - 0 = mon, 6 = sun
* [INTEGER]   `dow_sun17`
  - 1 = sun, 7 = sat
* [INTEGER]   `dow_sun06`
  - 0 = sun, 6 = sat
* [INTEGER]   `week_mon`
  - Week Number - First Monday - [0, 53]
* [INTEGER]   `week_sun`
  - Week Number - First Sunday - [0, 53]
* [INTEGER]   `week_iso`
  - Week Number - First Thursday (ISO) - [0, 53] ; https://en.wikipedia.org/wiki/ISO_week_date
* [INTEGER]   `month`
  - Month as Integer - [1, 12]
* [STRING]    `month_abbr`
  - Month as 3-letter STRING - [jan, feb, mar, apr, may, jun, jul, aug, sep, oct, nov, dec]
* [DATE]      `month_first_day`
  - First Day of Month as DATE - [2000-01-01, 2000-02-01, 2000-03-01, ..., 2000-12-01]
* [INTEGER]   `quarter`
  - Quarter as Integer - [1, 4]
* [DATE]      `quarter_first_day`
  - First Day of Quarter as DATE - [2000-01-01, 2000-04-01, 2000-07-01, 2000-10-01]
* [INTEGER]   `half`
  - Half as Integer - [1, 2]
* [DATE]      `half_first_day`
  - First Day of Half as DATE - [2000-01-01, 2000-07-01]
* [INTEGER]   `year`
  - Year as Integer - [1, 9999]
* [INTEGER]   `year_iso`
  - Year ISO ; https://en.wikipedia.org/wiki/ISO_week_date
* [DATE]      `year_first_day`
  - First Day of Year as DATE - [2000-01-01, 2001-01-01, 2002-01-01, ...]

-------------------------------------------------------------------------------
*Do not make edits above this line.*
