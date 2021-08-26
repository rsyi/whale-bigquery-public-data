# `covid19_italy.data_by_region`
`bq-1` | `bigquery-public-data`
COVID-19 Italy Data By Region

## Column details
* [TIMESTAMP] `date`
  - Date of notification
* [STRING]    `country`
  - Country of reference
* [INTEGER]   `region_code`
  - Code of the Region (ISTAT 2019)
* [STRING]    `region_name`
  - Name of the Region
* [FLOAT]     `latitude`
  - Latitude
* [FLOAT]     `longitude`
  - Longitude
* [GEOGRAPHY] `location_geom`
  - Geographic representation of the longitude and latitude
* [INTEGER]   `hospitalized_patients_symptoms`
  - Hospitalised patients with symptoms
* [INTEGER]   `hospitalized_patients_intensive_care`
  - Intensive Care
* [INTEGER]   `total_hospitalized_patients`
  - Total hospitalised patients
* [INTEGER]   `home_confinement_cases`
  - Home confinement
* [INTEGER]   `total_current_confirmed_cases`
  - Total amount of current positive cases (Hospitalised patients + Home confinement)
* [INTEGER]   `new_current_confirmed_cases`
  - News amount of current positive cases (totale_positivi current day - totale_positivi previous day)
* [INTEGER]   `new_total_confirmed_cases`
  - News amount of current positive cases (totale_casi current day - totale_casi previous day)
* [INTEGER]   `recovered`
  - Recovered
* [INTEGER]   `deaths`
  - Death
* [INTEGER]   `total_confirmed_cases`
  - Total amount of positive cases
* [INTEGER]   `tests_performed`
  - Tests performed
* [STRING]    `note`
  - Notes in english language

-------------------------------------------------------------------------------
*Do not make edits above this line.*
