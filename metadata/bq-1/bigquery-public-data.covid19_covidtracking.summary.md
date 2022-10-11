# `covid19_covidtracking.summary`
`bq-1` | `bigquery-public-data`

## Column details
* [DATE]      `date`
  - Date of the observations
* [STRING]    `admin_level_1`
  - 2-letter postal abbreviation for the state
* [STRING]    `state`
  - 2-letter postal abbreviation for the state
* [INTEGER]   `tests_increase`
  - number of new tests performed
* [INTEGER]   `tests_total`
  - total number of new tests performed
* [INTEGER]   `tests_pending`
  - number of tests pending
* [INTEGER]   `cases_positive_increase`
  - number of new positive cases identified
* [INTEGER]   `cases_positive_total`
  - total number of positive cases
* [INTEGER]   `cases_negative_increase`
  - number of new negative cases identified
* [INTEGER]   `cases_negative_total`
  - total number of negative cases
* [INTEGER]   `deaths_increase`
  - number of new deaths reported
* [INTEGER]   `deaths_total`
  - total cumulative number of people that have died
* [INTEGER]   `recovered_total`
  - total number of individuals that have tested negative after a previous positive test
* [INTEGER]   `hospitilzations_current`
  - number of individuals currently hospitalized
* [INTEGER]   `hospitalizations_increase`
  - number of individuals newly hospitalized
* [INTEGER]   `hospitalizations_total`
  - total number of individuals that have been hospitalized, including those that have been discharged
* [INTEGER]   `icu_current`
  - number of individuals currently in an ICU
* [INTEGER]   `icu_total`
  - total number of individuals that have been in the ICU
* [INTEGER]   `ventilator_current`
  - number of individuals currently on a ventilator
* [INTEGER]   `ventilator_total`
  - total number of individuals that have been on a ventilator
* [TIMESTAMP] `last_checked_ts`
  - datetime of the last update from state department health sites

-------------------------------------------------------------------------------
*Do not make edits above this line.*
