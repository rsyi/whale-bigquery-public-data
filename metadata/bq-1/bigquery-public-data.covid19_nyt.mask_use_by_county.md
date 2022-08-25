# `covid19_nyt.mask_use_by_county`
`bq-1` | `bigquery-public-data`
This data comes from a large number of interviews conducted online by the global data and survey firm Dynata at the request of The New York Times. The firm asked a question about mask use to obtain 250,000 survey responses between July 2 and July 14, enough data to provide estimates more detailed than the state level. (Several states have imposed new mask requirements since the completion of these interviews.)

Specifically, each participant was asked: How often do you wear a mask in public when you expect to be within six feet of another person?

This survey was conducted a single time, and at this point we have no plans to update the data or conduct the survey again.

Sourced from https://github.com/nytimes/covid-19-data/tree/master/mask-use.

## Column details
* [STRING]    `county_fips_code`
  - Standard geographic identifier for the county
* [FLOAT]     `never`
  - The estimated share of people in this county who would say never in response to the question "How often do you wear a mask in public when you expect to be within six feet of another person?"
* [FLOAT]     `rarely`
  - The estimated share of people in this county who would say rarely
* [FLOAT]     `sometimes`
  - The estimated share of people in this county who would say sometimes
* [FLOAT]     `frequently`
  - The estimated share of people in this county who would say frequently
* [FLOAT]     `always`
  - The estimated share of people in this county who would say always

-------------------------------------------------------------------------------
*Do not make edits above this line.*
