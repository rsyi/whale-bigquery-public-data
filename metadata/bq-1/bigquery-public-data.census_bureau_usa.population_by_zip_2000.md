# `census_bureau_usa.population_by_zip_2000`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `zipcode`
  - Five digit ZIP Code Tabulation Area Census Code
* [STRING]    `geo_id`
  - Geo code
* [INTEGER]   `minimum_age`
  - The minimum age in the age range. If null, this indicates the row as a total for male, female, or overall population.
* [INTEGER]   `maximum_age`
  - The maximum age in the age range. If null, this indicates the row as having no maximum (such as 85 and over) or the row is a total of the male, female, or overall population.
* [STRING]    `gender`
  - male or female. If empty, the row is a total population summary.
* [INTEGER]   `population`
  - The total count of the population for this segment.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
