# `covid19_public_forecasts.japan_prefecture_28d_historical_`
`bq-1` | `bigquery-public-data`
This predicts the value for key metrics for COVID-19 impacts over a 28-day horizon at the US county level.

## Column details
* [STRING]    `prefecture_code`
  - Unique identifer of the prefecture.
* [STRING]    `prefecture_name`
  - Full text name of the prefecture
* [STRING]    `prefecture_name_kanji`
  - Full text name of the prefecture in Kanji
* [DATE]      `forecast_date`
  - Date of the forecast
* [DATE]      `prediction_date`
  - Predicted date of the given metrics
* [FLOAT]     `new_confirmed`
  - Predicted number of new confirmed cases on the prediction_date. This is not cumulative over time
* [FLOAT]     `cumulative_confirmed`
  - Predicted number of cumulative confirmed cases on the prediction_date. This is cumulative over time
* [FLOAT]     `cumulative_confirmed_q0025`
  - The lower bound of the 95% confidence interval of the predicted number of cumulative confirmed cases on the prediction_date (2.5% quantile). This is cumulative over time
* [FLOAT]     `cumulative_confirmed_q0975`
  - The upper bound of the 95% confidence interval of cumulative confirmed cases on the prediction_date (97.5% quantile). This is cumulative over time
* [FLOAT]     `new_confirmed_7day_rolling`
  - The seven day rolling average of new confirmed cases.
* [FLOAT]     `new_deaths`
  - Predicted number of new deaths on the prediction_date. This is not cumulative over time
* [FLOAT]     `cumulative_deaths`
  - Predicted number of cumulative confirmed cases on the prediction_date. This is cumulative over time
* [FLOAT]     `cumulative_deaths_q0025`
  - The lower bound of the 95% confidence interval of the predicted number of cumulative deaths on the prediction_date (2.5% quantile). This is cumulative over time
* [FLOAT]     `cumulative_deaths_q0975`
  - The upper bound of the 95% confidence interval of the predicted number of cumulative deaths on the prediction_date (97.5% quantile). This is cumulative over time
* [FLOAT]     `new_deaths_7day_rolling`
  - The seven day rolling average of new confirmed cases.
* [FLOAT]     `hospitalized_patients`
  - Predicted number of people hospitalized on the prediction_date. This is not cumulative over time
* [FLOAT]     `hospitalized_patients_q0025`
  - The lower bound of the 95% confidence interval of the predicted number of people hospitalized on the prediction_date (2.5% quantile). This is cumulative over time
* [FLOAT]     `hospitalized_patients_q0975`
  - The upper bound of the 95% confidence interval of the predicted number of people hospitalized on the prediction_date (97.5% quantile). This is cumulative over time
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
* [FLOAT]     `recovered_documented_ground_truth`
  - Actual number of people hospitalized according to the ground truth data
* [INTEGER]   `prefecture_population`
  - Total population of the prefecture

-------------------------------------------------------------------------------
*Do not make edits above this line.*
