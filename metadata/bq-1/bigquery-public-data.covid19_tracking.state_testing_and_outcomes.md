# `covid19_tracking.state_testing_and_outcomes`
`bq-1` | `bigquery-public-data`

## Column details
* [DATE]      `date`
  - Date of the observations
* [STRING]    `state`
  - 2-letter postal abbreviation for the state
* [INTEGER]   `death`
  - Total cumulative number of people that have died
* [INTEGER]   `death_confirmed`
  - Total deaths with confirmed COVID-19 case diagnosis
* [INTEGER]   `death_increase`
  - Number of new deaths reported
* [INTEGER]   `death_probable`
  - Total deaths with probable COVID-19 case diagnosis
* [INTEGER]   `hospitalized`
  - Total number of individuals who have ever been hospitalized with COVID-19
* [INTEGER]   `hospitalized_cumulative`
  - Total number of individuals who have ever been hospitalized with COVID-19
* [INTEGER]   `hospitalized_currently`
  - Individuals who are currently hospitalized with COVID-19
* [INTEGER]   `hospitalized_increase`
  - Daily increase in hospitalized_cumulative, calculated from the previous day's value
* [INTEGER]   `in_icu_cumulative`
  - Total number of individuals who have ever been hospitalized in the Intensive Care Unit with COVID-19
* [INTEGER]   `in_icu_currently`
  - Individuals who are currently hospitalized in the Intensive Care Unit with COVID-19
* [INTEGER]   `negative`
  - Total number of unique people with a completed PCR test that returns negative
* [INTEGER]   `negative_increase`
  - Daily increase of unique people with a completed PCR test that returns negative based on the previous day's value
* [INTEGER]   `negative_tests_antibody`
  - The total number of unique people with completed antibody tests that return negative as reported by the state or territory
* [INTEGER]   `negative_tests_people_antibody`
  - The total number of unique people with completed antibody tests that return positive as reported by the state or territory
* [INTEGER]   `negative_tests_viral`
  - Total number of completed PCR tests (or specimens tested) that return negative as reported by the state or territory
* [INTEGER]   `on_ventilator_cumulative`
  - Total number of individuals who have ever been hospitalized under advanced ventilation with COVID-19
* [INTEGER]   `on_ventilator_currently`
  - Individuals who are currently hospitalized under advanced ventilation with COVID-19
* [INTEGER]   `positive`
  - Total number of confirmed plus probable cases of COVID-19 reported by the state or territory
* [INTEGER]   `positive_cases_viral`
  - Total number of unique people with a positive PCR or other approved nucleic acid amplification test (NAAT), as reported by the state or territory
* [INTEGER]   `positive_increase`
  - The daily increase in positive, which measures cases (confirmed plus probable) calculated based on the previous day's value
* [INTEGER]   `positive_score`
* [INTEGER]   `positive_tests_antibody`
  - Total number of completed antibody tests that return positive as reported by the state or territory
* [INTEGER]   `positive_tests_antigen`
  - Total number of completed antigen tests that return positive as reported by the state or territory
* [INTEGER]   `positive_tests_people_antibody`
  - The total number of unique people with completed antibody tests that return positive as reported by the state or territory
* [INTEGER]   `positive_tests_people_antigen`
  - Total number of unique people with a completed antigen test that returned positive as reported by the state or territory
* [INTEGER]   `positive_tests_viral`
  - Total number of completed PCR tests (or specimens tested) that return positive as reported by the state or territory
* [INTEGER]   `recovered`
  - Total number of people that are identified as recovered from COVID-19
* [INTEGER]   `total_test_encounters_viral`
  - Total number of people tested per day via PCR testing as reported by the state or territory
* [INTEGER]   `total_test_encounters_viral_increase`
  - The daily increase in people tested via PCR testing based on the previous day's value
* [INTEGER]   `total_test_results`
  - In most states, this field is currently computed by adding positive and negative values because, historically, some states do not report totals, and to work around different reporting cadences for cases and tests
* [INTEGER]   `total_test_results_increase`
  - The daily increase in total_test_results, calculated from the previous day's value
* [INTEGER]   `total_tests_antibody`
  - Total number of completed antibody tests as reported by the state or territory
* [INTEGER]   `total_tests_antigen`
  - Total number of completed antigen tests, as reported by the state or territory
* [INTEGER]   `total_tests_people_antibody`
  - The total number of unique people who have been tested at least once via antibody testing as reported by the state or territory
* [INTEGER]   `total_tests_people_antigen`
  - Total number of unique people who have been tested at least once via antigen testing, as reported by the state or territory
* [INTEGER]   `total_tests_people_viral`
  - Total number of unique people tested at least once via PCR testing, as reported by the state or territory
* [INTEGER]   `total_tests_people_viral_increase`
  - The daily increase in the number of unique people tested at least once via PCR testing, based on the previous day's value
* [INTEGER]   `total_tests_viral`
  - Total number of PCR tests (or specimens tested) as reported by the state or territory
* [INTEGER]   `total_tests_viral_increase`
  - The daily increase in the number of PCR tests (or specimens tested) based on the previous day's value

-------------------------------------------------------------------------------
*Do not make edits above this line.*
