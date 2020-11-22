# `usa_names.usa_1910_2013`
`bq-1` | `bigquery-public-data`
The table contains the number of applicants for a Social Security card by year of birth and sex. The number of such applicants is restricted to U.S. births where the year of birth, sex, State of birth (50 States and District of Columbia) are known, and where the given name is at least 2 characters long.

source: http://www.ssa.gov/OACT/babynames/limits.html

## Column details
* [STRING]    `state`
  - 2-digit state code
* [STRING]    `gender`
  - Sex (M=male or F=female)
* [INTEGER]   `year`
  - 4-digit year of birth
* [STRING]    `name`
  - Given name of a person at birth
* [INTEGER]   `number`
  - Number of occurrences of the name

-------------------------------------------------------------------------------
*Do not make edits above this line.*
