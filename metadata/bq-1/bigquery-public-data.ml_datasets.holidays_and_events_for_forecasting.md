# `ml_datasets.holidays_and_events_for_forecasting`
`bq-1` | `bigquery-public-data`
This table contains holiday and special event data used to train time series forecasting models (ARIMA_PLUS & ARIMA_PLUS_XREG). The data is not comprehensive and does not cover all geographic regions. Within the supported regions, it also may not include all the known holidays.

## Column details
* [STRING]    `region`
* [STRING]    `holiday_name`
* [DATE]      `primary_date`
* [INTEGER]   `preholiday_days`
* [INTEGER]   `postholiday_days`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
