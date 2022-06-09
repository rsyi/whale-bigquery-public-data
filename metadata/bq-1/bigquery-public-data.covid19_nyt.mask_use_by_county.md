# `covid19_nyt.mask_use_by_county`
`bq-1` | `bigquery-public-data`
Sourced from https://github.com/nytimes/covid-19-data/tree/master/mask-use. This data comes from a large number of interviews conducted online by the global data and survey firm Dynata at the request of The New York Times. The firm asked a question about mask use to obtain 250,000 survey responses between July 2 and July 14, enough data to provide estimates more detailed than the state level. (Several states have imposed new mask requirements since the completion of these interviews.)

Specifically, each participant was asked: How often do you wear a mask in public when you expect to be within six feet of another person?

This survey was conducted a single time, and at this point we have no plans to update the data or conduct the survey again.

## Column details
* [STRING]    `county_fips_code`
* [FLOAT]     `never`
* [FLOAT]     `rarely`
* [FLOAT]     `sometimes`
* [FLOAT]     `frequently`
* [FLOAT]     `always`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
