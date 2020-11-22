# `census_bureau_international.midyear_population_5yr_age_sex`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `country_code`
  - Federal Information Processing Standard (FIPS) country/area code
* [STRING]    `country_name`
  - Country or area name
* [INTEGER]   `year`
  - Year
* [STRING]    `total_flag`
  - Total flag: "*"=Total, all ages; "A"=Individual age group
* [INTEGER]   `starting_age`
  - Starting age (0 to 100)
* [STRING]    `age_group_indicator`
  - Age group indicator: "-"=5-year age group; "+"=open-ended age group
* [INTEGER]   `ending_age`
  - Ending age (4 to 99; set to 0 if G="+")
* [INTEGER]   `midyear_population`
  - Both sexes midyear population in the age group
* [INTEGER]   `midyear_population_male`
  - Male midyear population in the age group
* [INTEGER]   `midyear_population_female`
  - Female midyear population in the age group

-------------------------------------------------------------------------------
*Do not make edits above this line.*
