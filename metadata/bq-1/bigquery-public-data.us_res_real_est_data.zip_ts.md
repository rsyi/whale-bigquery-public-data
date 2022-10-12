# `us_res_real_est_data.zip_ts`
`bq-1` | `bigquery-public-data`
Sample of Zipcode timeseries

## Column details
* [STRING]    `zip`
  - 5 digit Zipcode
* [STRING]    `msa`
  - 5 digit Metropolitan Statistical Area code
* [DATE]      `month`
  - Month of timeseries
* [FLOAT]     `hpi_value`
  - Nominal housing price index
* [FLOAT]     `hpi_yoy_pct_chg`
  - Year over year percent change in the nominal housing price index. Formally computed as [hpi_value(t)/hpi_value(t-12)]-1
* [FLOAT]     `hpi_distance`
  - The normalized distance of hpi_value from a long term linear trend. Units are in standard deviations from the mean
* [FLOAT]     `hpi_returns`
  - Monthly returns in the nominal housing price index. Formally computed as hpi_value(t)/hpi_value(t-1)
* [FLOAT]     `hpi_real`
  - Real housing price index after adjusting nominal HPI for inflation as measured by the CPI
* [FLOAT]     `hpi_trend`
  - Long term linear trend in hpi_value
* [FLOAT]     `afford_detrended`
  - Normalized distance of afford_pmt from a long term linear trend. Units are in standard deviations from the mean
* [FLOAT]     `afford_pmt`
  - Raw affordability value. Represents the percent of median household income required to make the median home payment on a 30 year fixed rate mortgage with 20% down
* [FLOAT]     `acceleration_value`
  - Monthly change in velocity_value
* [FLOAT]     `velocity_value`
  - Smoothed year over year change in hpi_value

-------------------------------------------------------------------------------
*Do not make edits above this line.*
