# `covid19_tracking.national_testing_and_outcomes`
`bq-1` | `bigquery-public-data`

## Column details
* [DATE]      `date`
  - Date of the observations
* [INTEGER]   `death`
  - Total cumulative number of people that have died
* [INTEGER]   `death_increase`
  - The daily increase in the number of people that have died based on the previous day's value
* [INTEGER]   `in_icu_cumulative`
  - Total number of individuals who have ever been hospitalized in the Intensive Care Unit with COVID-19
* [INTEGER]   `in_icu_currently`
  - Individuals who are currently hospitalized in the Intensive Care Unit with COVID-19
* [INTEGER]   `hospitalized_increase`
  - Daily increase in hospitalized_cumulative, calculated from the previous day's value
* [INTEGER]   `hospitalized_currently`
  - Individuals who are currently hospitalized with COVID-19
* [INTEGER]   `hospitalized_cumulative`
  - Total number of individuals who have ever been hospitalized with COVID-19
* [INTEGER]   `negative`
  - Total number of unique people with a completed PCR test that returns negative
* [INTEGER]   `negative_increase`
  - Daily increase of unique people with a completed PCR test that returns negative based on the previous day's value
* [INTEGER]   `on_ventilator_cumulative`
  - Total number of individuals who have ever been hospitalized under advanced ventilation with COVID-19
* [INTEGER]   `on_ventilator_currently`
  - Individuals who are currently hospitalized under advanced ventilation with COVID-19
* [INTEGER]   `positive`
  - Total number of confirmed plus probable cases of COVID-19 reported by the state or territory
* [INTEGER]   `positive_increase`
  - The daily increase in positive, which measures cases (confirmed plus probable) calculated based on the previous day's value
* [INTEGER]   `states`
  - The number of states and territories included in the US dataset for this day
* [INTEGER]   `total_test_results`
  - In most states, this field is currently computed by adding positive and negative values because, historically, some states do not report totals, and to work around different reporting cadences for cases and tests
* [INTEGER]   `total_test_results_increase`
  - The daily increase in total_test_results, calculated from the previous day's value

-------------------------------------------------------------------------------
*Do not make edits above this line.*
