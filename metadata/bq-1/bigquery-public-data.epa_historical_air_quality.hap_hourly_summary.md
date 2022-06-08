# `epa_historical_air_quality.hap_hourly_summary`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `state_code`
  - The FIPS code of the state in which the monitor resides.
* [STRING]    `county_code`
  - The FIPS code of the county in which the monitor resides.
* [STRING]    `site_num`
  - A unique number within the county identifying the site.
* [INTEGER]   `parameter_code`
  - The AQS code corresponding to the parameter measured by the monitor.
* [INTEGER]   `poc`
  - This is the “Parameter Occurrence Code” used to distinguish different instruments that measure the same parameter at the same site.
* [FLOAT]     `latitude`
  - The monitoring site’s angular distance north of the equator measured in decimal degrees.
* [FLOAT]     `longitude`
  - The monitoring site’s angular distance east of the prime meridian measured in decimal degrees.
* [STRING]    `datum`
  - The Datum associated with the Latitude and Longitude measures.
* [STRING]    `parameter_name`
  - The name or description assigned in AQS to the parameter measured by the monitor. Parameters may be pollutants or non-pollutants.
* [DATE]      `date_local`
  - The calendar date for the summary. All daily summaries are for the local standard day (midnight to midnight) at the monitor.
* [STRING]    `time_local`
  - The time of day that sampling began on a 24-hour clock in Local Standard Time.
* [DATE]      `date_gmt`
  - The calendar date of the sample in Greenwich Mean Time.
* [STRING]    `time_gmt`
  - The time of day that sampling began on a 24-hour clock in Greenwich Mean Time.
* [FLOAT]     `sample_measurement`
  - The measured value in the standard units of measure for the parameter.
* [STRING]    `units_of_measure`
  - The unit of measure for the parameter. QAD always returns data in the standard units for the parameter. Submitters are allowed to report data in any unit and EPA converts to a standard unit so that we may use the data in calculations.
* [FLOAT]     `mdl`
  - The Method Detection Limit. The minimum sample concentration detectable for the monitor and method. Note: if samples are reported below this level, they may have been replaced by 1/2 the MDL.
* [FLOAT]     `uncertainty`
  - The total measurement uncertainty associated with a reported measurement as indicated by the reporting agency.
* [STRING]    `qualifier`
  - Sample values may have qualifiers that indicate why they are missing or that they are out of the ordinary. Types of qualifiers are: null data, exceptional event, natural events, and quality assurance. The highest ranking qualifier, if any, is described in this field.
* [STRING]    `method_type`
  - An indication of whether the method used to collect the data is a federal reference method (FRM), equivalent to a federal reference method, an approved regional method, or none of the above (non-federal reference method).
* [STRING]    `method_code`
  - An internal system code indicating the method (processes, equipment, and protocols) used in gathering and measuring the sample. The method name is in the next column.
* [STRING]    `method_name`
  - A short description of the processes, equipment, and protocols used in gathering and measuring the sample.
* [STRING]    `state_name`
  - The name of the state where the monitoring site is located.
* [STRING]    `county_name`
  - The name of the county where the monitoring site is located.
* [DATE]      `date_of_last_change`
  - The date the last time any numeric values in this record were updated in the AQS data system.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
