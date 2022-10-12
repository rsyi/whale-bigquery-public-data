# `us_res_real_est_data.zip_cs`
`bq-1` | `bigquery-public-data`
Sample of Zipcode cross section

## Column details
* [STRING]    `zip`
  - 5 digit Zipcode
* [STRING]    `msa`
  - 5 digit Metropolitan Statistical Area code
* [STRING]    `state`
  - 2-digit USPS State Abbreviation
* [FLOAT]     `cagr`
  - Compound annual growth rate of the Zipcode HPI Value over the trailing 20 years
* [FLOAT]     `cagr_zscore`
  - The number of standard deviations the cagr (20Y) is from the mean of all Zipcodes
* [FLOAT]     `cagr_1`
  - Compound annual growth rate of the Zipcode HPI Value over the trailing year
* [FLOAT]     `cagr_1_zscore`
  - The number of standard deviations the cagr_1 is from the mean of all Zipcodes
* [FLOAT]     `cagr_5`
  - Compound annual growth rate of the Zipcode HPI Value over the trailing 5 years
* [FLOAT]     `cagr_5_zscore`
  - The number of standard deviations the cagr_5 is from the mean of all Zipcodes
* [FLOAT]     `cagr_10`
  - Compound annual growth rate of the Zipcode HPI Value over the trailing 10 years
* [FLOAT]     `cagr_10_zscore`
  - The number of standard deviations the cagr_10 is from the mean of all Zipcodes
* [FLOAT]     `returns_1`
  - Percentage growth in the Zipcode HPI Value over the trailing year
* [FLOAT]     `returns_5`
  - Percentage growth in the Zipcode HPI Value over the trailing 5 years
* [FLOAT]     `returns_10`
  - Percentage growth in the Zipcode HPI Value over the trailing 10 years
* [FLOAT]     `beta`
  - Measure of volatility of the Zipcode HPIover the last 20 years relative to the National HPI
* [FLOAT]     `beta_zscore`
  - The number of standard deviations beta is from the mean of all MSAs
* [FLOAT]     `sharpe`
  - Sharpe ratio is a measure of risk adjusted return calcuated as the average excess returns of the Zipcode HPI (Zipcode HPI growth minus risk free rate) times the ratio of the standard deviation of excess returns of the benchmark (National HPI) over the standard deviation of excess returns of the Zipcode HPI for the trailing 20 years.
* [FLOAT]     `sharpe_zscore`
  - The number of standard deviations sharpe is from the mean of all Zipcodes
* [FLOAT]     `m2`
  - Modigliani risk-adjusted performance is calcuated as the ratio of excess returns (Zipcode HPI growth minus risk free rate) over the standard deviation of excess returns over the trailing 20 years.
* [FLOAT]     `m2_zscore`
  - The number of standard deviations m2 is from the mean of all Zipcodes
* [FLOAT]     `returns_12mo_f`
  - Forecasted percentage growth in the Zipcode HPI Value over the following 12 months
* [FLOAT]     `returns_24mo_f`
  - Forecasted percentage growth in the Zipcode HPI Value over the following 24 months
* [FLOAT]     `returns_36mo_f`
  - Forecasted percentage growth in the Zipcode HPI Value over the following 36 months
* [FLOAT]     `cagr_12mo_f`
  - Forecasted compound annual growth rate in the Zipcode HPI Value over the following 12 months
* [FLOAT]     `cagr_24mo_f`
  - Forecasted compound annual growth rate in the Zipcode HPI Value over the following 24 months
* [FLOAT]     `cagr_36mo_f`
  - Forecasted compound annual growth rate in the Zipcode HPI Value over the following 36 months

-------------------------------------------------------------------------------
*Do not make edits above this line.*
