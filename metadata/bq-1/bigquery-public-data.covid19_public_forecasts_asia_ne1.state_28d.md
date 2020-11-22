# `covid19_public_forecasts_asia_ne1.state_28d`
`bq-1` | `bigquery-public-data`
This predicts the value for key metrics for COVID-19 impacts over a 28-day horizon at the US state level.

## Column details
* [STRING]    `state_fips_code`
  - Unique identifier for the given state
* [STRING]    `state_name`
  - Full text name of the state in which a given county lies
* [DATE]      `forecast_date`
  - Date of the forecast
* [DATE]      `prediction_date`
  - Predicted date of the given metrics
* [FLOAT]     `new_confirmed`
  - Predicted number of new confirmed cases on the prediction_date. This is not cumulative over time
* [FLOAT]     `cumulative_confirmed`
  - Predicted number of cumulative cases on the prediction_date. This is cumulative over time
* [FLOAT]     `cumulative_confirmed_q0025`
  - The lower bound of the 95% confidence interval of cumulative cases on the prediction_date (2.5% quantile). This is cumulative over time
* [FLOAT]     `cumulative_confirmed_q0975`
  - The upper bound of the 95% confidence interval of cumulative cases on the prediction_date (97.5% quantile). This is cumulative over time
* [FLOAT]     `new_confirmed_7day_rolling`
  - The seven day rolling average of new confirmed cases.
* [FLOAT]     `new_deaths`
  - Predicted number of new deaths on the prediction_date. This is cumulative over time
* [FLOAT]     `cumulative_deaths`
  - Predicted number of cumulative confirmed cases on the prediction_date. This is not cumulative over time
* [FLOAT]     `cumulative_deaths_q0025`
  - The lower bound of the 95% confidence interval of cumulative deaths on the prediction_date (2.5% quantile). This is cumulative over time
* [FLOAT]     `cumulative_deaths_q0975`
  - The upper bound of the 95%  confidence interval of cumulative deaths on the prediction_date (97.5% quantile). This is cumulative over time
* [FLOAT]     `new_deaths_7day_rolling`
  - The seven day rolling average of new confirmed cases.
* [FLOAT]     `hospitalized_patients`
  - Predicted number of people hospitalized on the prediction_date. This is not cumulative over time
* [FLOAT]     `hospitalized_patients_q0025`
  - The lower bound of the 95% confidence interval of hospitalized patients on the prediction_date (2.5% quantile). This is not cumulative over time
* [FLOAT]     `hospitalized_patients_q0975`
  - The upper bound of the 95%  confidence interval of hospitalized patients on the prediction_date (97.5% quantile). This is not cumulative over time
* [FLOAT]     `intensive_care_patients`
  - Predicted number of people in the ICU on the prediction_date. This is not cumulative over time
* [FLOAT]     `intensive_care_patients_q0025`
  - The lower bound of the 95% confidence interval of ICU patients on the prediction_date (2.5% quantile). This is not cumulative over time
* [FLOAT]     `intensive_care_patients_q0975`
  - The upper bound of the 95%  confidence interval of the predicted number of people in the ICU on the prediction_date (97.5% quantile). This is not cumulative over time
* [FLOAT]     `ventilator_patients`
  - Predicted number of people on a ventilator on the prediction_date. This is not cumulative over time
* [FLOAT]     `ventilator_patients_q0025`
  - The lower bound of the 95% confidence interval of patients on a ventilator on the prediction_date (2.5% quantile). This is not cumulative over time
* [FLOAT]     `ventilator_patients_q0975`
  - The upper bound of the 95%  confidence interval of the predicted number of people on a ventilator on the prediction_date (97.5% quantile). This is not cumulative over time
* [FLOAT]     `recovered`
  - Predicted number of people documented as recovered on the prediction_date. This is not cumulative over time
* [FLOAT]     `recovered_q0025`
  - The lower bound of the 95% confidence interval of the predicted number of people documented as recovered on the prediction_date (2.5% quantile). This is not cumulative over time
* [FLOAT]     `recovered_q0975`
  - The upper bound of the 95% confidence interval of the predicted number of people documented as recovered on the prediction_date (97.5% quantile). This is not cumulative over time
* [FLOAT]     `new_confirmed_ground_truth`
  - Actual number of new confirmed cases according to the ground truth data. This is not cumulative over time
* [FLOAT]     `cumulative_confirmed_ground_truth`
  - Actual number of cumulative confirmed cases according to the ground truth data. This is cumulative over time
* [FLOAT]     `new_deaths_ground_truth`
  - Actual number of new deaths according to the ground truth data. This is not cumulative over time
* [FLOAT]     `cumulative_deaths_ground_truth`
  - Actual number of cumulative deaths according to the ground truth data. This is cumulative over time
* [FLOAT]     `hospitalized_patients_ground_truth`
  - Actual number of people hospitalized according to the ground truth data. This is not cumulative over time
* [FLOAT]     `intensive_care_patients_ground_truth`
  - Actual number of people documented as recovered according to the ground truth data
* [FLOAT]     `ventilator_patients_ground_truth`
  - Actual number of people on a ventilator according to the ground truth data. This is not cumulative over time
* [FLOAT]     `recovered_documented_ground_truth`
  - Actual number of people hospitalized according to the ground truth data
* [INTEGER]   `state_population`
  - Total population of the state

-------------------------------------------------------------------------------
*Do not make edits above this line.*
