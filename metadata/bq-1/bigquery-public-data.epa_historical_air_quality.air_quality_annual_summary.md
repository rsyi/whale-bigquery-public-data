# `epa_historical_air_quality.air_quality_annual_summary`
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
  - This is the 'Parameter Occurrence Code' used to distinguish different instruments that measure the same parameter at the same site.
* [FLOAT]     `latitude`
  - The monitoring site’s angular distance north of the equator measured in decimal degrees.
* [FLOAT]     `longitude`
  - The monitoring site’s angular distance east of the prime meridian measured in decimal degrees.
* [STRING]    `datum`
  - The Datum associated with the Latitude and Longitude measures.
* [STRING]    `parameter_name`
  - The name or description assigned in AQS to the parameter measured by the monitor. Parameters may be pollutants or non-pollutants.
* [STRING]    `sample_duration`
  - The length of time that air passes through the monitoring device before it is analyzed (measured). So, it represents an averaging period in the atmosphere (for example, a 24-hour sample duration draws ambient air over a collection filter for 24 straight hours). For continuous monitors, it can represent an averaging time of many samples (for example, a 1-hour value may be the average of four one-minute samples collected during each quarter of the hour).
* [STRING]    `pollutant_standard`
  - A description of the ambient air quality standard rules used to aggregate statistics. (See description at beginning of document.)
* [STRING]    `metric_used`
  - The base metric used in the calculation of the aggregate statistics presented in the remainder of the row. For example, if this is Daily Maximum, then the value in the Mean column is the mean of the daily maximums.
* [STRING]    `method_name`
  - A short description of the processes, equipment, and protocols used in gathering and measuring the sample.
* [INTEGER]   `year`
  - The year the annual summary data represents.
* [STRING]    `units_of_measure`
  - The unit of measure for the parameter. QAD always returns data in the standard units for the parameter. Submitters are allowed to report data in any unit and EPA converts to a standard unit so that we may use the data in calculations.
* [STRING]    `event_type`
  - Indicates whether data measured during exceptional events are included in the summary. A wildfire is an example of an exceptional event; it is something that affects air quality, but the local agency has no control over. No Events means no events occurred. Events Included means events occurred and the data from them is included in the summary. Events Excluded means that events occurred but data form them is excluded from the summary. Concurred Events Excluded means that events occurred but only EPA concurred exclusions are removed from the summary. If an event occurred for the parameter in question, the data will have multiple records for each monitor.
* [INTEGER]   `observation_count`
  - The number of observations (samples) taken during the year.
* [FLOAT]     `observation_percent`
  - The percent representing the number of observations taken with respect to the number scheduled to be taken during the year. This is only calculated for monitors where measurements are required (e.g., only certain parameters).
* [STRING]    `completeness_indicator`
  - An indication of whether the regulatory data completeness criteria for valid summary data have been met by the monitor for the year. Y means yes, N means no or that there are no regulatory completeness criteria for the parameter.
* [INTEGER]   `valid_day_count`
  - The number of days during the year where the daily monitoring criteria were met, if the calculation of the summaries is based on valid days.
* [INTEGER]   `required_day_count`
  - The number of days during the year which the monitor was scheduled to take samples if measurements are required.
* [INTEGER]   `exceptional_data_count`
  - The number of data points in the annual data set affected by exceptional air quality events (things outside the norm that affect air quality).
* [INTEGER]   `null_data_count`
  - The count of scheduled samples when no data was collected and the reason for no data was reported.
* [INTEGER]   `primary_exceedance_count`
  - The number of samples during the year that exceeded the primary air quality standard.
* [INTEGER]   `secondary_exceedance_count`
  - The number of samples during the year that exceeded the secondary air quality standard.
* [STRING]    `certification_indicator`
  - An indication whether the completeness and accuracy of the information on the annual summary record has been certified by the submitter. Certified means the submitter has certified the data (due May 01 the year after collection). Certification not required means that the parameter does not require certification or the deadline has not yet passed. Uncertified (past due) means that certification is required but is overdue. Requested but not yet concurred means the submitter has completed the process, but EPA has not yet acted to certify the data. Requested but denied means the submitter has completed the process, but EPA has denied the request for cause. Was certified but data changed means the data was certified but data was replaced and the process has not been repeated.
* [INTEGER]   `num_obs_below_mdl`
  - The number of samples reported during the year that were below the method detection limit (MDL) for the monitoring instrument. Sometimes these values are replaced by 1/2 the MDL in summary calculations.
* [FLOAT]     `arithmetic_mean`
  - The average (arithmetic mean) value for the year.
* [FLOAT]     `arithmetic_standard_dev`
  - The standard deviation about the mean of the values for the year.
* [FLOAT]     `first_max_value`
  - The highest value for the year.
* [TIMESTAMP] `first_max_datetime`
  - The date and time (on a 24-hour clock) when the highest value for the year (the previous field) was taken.
* [FLOAT]     `second_max_value`
  - The second highest value for the year.
* [TIMESTAMP] `second_max_datetime`
  - The date and time (on a 24-hour clock) when the second highest value for the year (the previous field) was taken.
* [FLOAT]     `third_max_value`
  - The third highest value for the year.
* [TIMESTAMP] `third_max_datetime`
  - The date and time (on a 24-hour clock) when the third highest value for the year (the previous field) was taken.
* [FLOAT]     `fourth_max_value`
  - The fourth highest value for the year.
* [TIMESTAMP] `fourth_max_datetime`
  - The date and time (on a 24-hour clock) when the fourth highest value for the year (the previous field) was taken.
* [FLOAT]     `first_max_non_overlapping_value`
  - For 8-hour CO averages, the highest value of the year.
* [TIMESTAMP] `first_no_max_datetime`
  - The date and time (on a 24-hour clock) when the first maximum non overlapping value for the year (the previous field) was taken.
* [FLOAT]     `second_max_non_overlapping_value`
  - For 8-hour CO averages, the second highest value of the year that does not share any hours with the 8-hour period of the first max non overlapping value.
* [TIMESTAMP] `second_no_max_datetime`
  - The date and time (on a 24-hour clock) when the second maximum non overlapping value for the year (the previous field) was taken.
* [FLOAT]     `ninety_nine_percentile`
  - The value from this monitor for which 99 per cent of the rest of the measured values for the year are equal to or less than.
* [FLOAT]     `ninety_eight_percentile`
  - The value from this monitor for which 98 per cent of the rest of the measured values for the year are equal to or less than.
* [FLOAT]     `ninety_five_percentile`
  - The value from this monitor for which 95 per cent of the rest of the measured values for the year are equal to or less than.
* [FLOAT]     `ninety_percentile`
  - The value from this monitor for which 90 per cent of the rest of the measured values for the year are equal to or less than.
* [FLOAT]     `seventy_five_percentile`
  - The value from this monitor for which 75 per cent of the rest of the measured values for the year are equal to or less than.
* [FLOAT]     `fifty_percentile`
  - The value from this monitor for which 50 per cent of the rest of the measured values for the year are equal to or less than (i.e., the median).
* [FLOAT]     `ten_percentile`
  - The value from this monitor for which 10 per cent of the rest of the measured values for the year are equal to or less than.
* [STRING]    `local_site_name`
  - The name of the site (if any) given by the State, local, or tribal air pollution control agency that operates it.
* [STRING]    `address`
  - The approximate street address of the monitoring site.
* [STRING]    `state_name`
  - The name of the state where the monitoring site is located.
* [STRING]    `county_name`
  - The name of the county where the monitoring site is located.
* [STRING]    `city_name`
  - The name of the city where the monitoring site is located. This represents the legal incorporated boundaries of cities and not urban areas.
* [STRING]    `cbsa_name`
  - The name of the core bases statistical area (metropolitan area) where the monitoring site is located.
* [DATE]      `date_of_last_change`
  - The date the last time any numeric values in this record were updated in the AQS data system.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
