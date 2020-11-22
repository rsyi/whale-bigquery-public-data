# `epa_historical_air_quality.so2_daily_summary`
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
* [STRING]    `sample_duration`
  - The length of time that air passes through the monitoring device before it is analyzed (measured). So, it represents an averaging period in the atmosphere (for example, a 24-hour sample duration draws ambient air over a collection filter for 24 straight hours). For continuous monitors, it can represent an averaging time of many samples (for example, a 1-hour value may be the average of four one-minute samples collected during each quarter of the hour).
* [STRING]    `pollutant_standard`
  - A description of the ambient air quality standard rules used to aggregate statistics. (See description at beginning of document.)
* [DATE]      `date_local`
  - The calendar date for the summary. All daily summaries are for the local standard day (midnight to midnight) at the monitor.
* [STRING]    `units_of_measure`
  - The unit of measure for the parameter. QAD always returns data in the standard units for the parameter. Submitters are allowed to report data in any unit and EPA converts to a standard unit so that we may use the data in calculations.
* [STRING]    `event_type`
  - Indicates whether data measured during exceptional events are included in the summary. A wildfire is an example of an exceptional event; it is something that affects air quality, but the local agency has no control over. No Events means no events occurred. Events Included means events occurred and the data from them is included in the summary. Events Excluded means that events occurred but data form them is excluded from the summary. Concurred Events Excluded means that events occurred but only EPA concurred exclusions are removed from the summary. If an event occurred for the parameter in question, the data will have multiple records for each monitor.
* [INTEGER]   `observation_count`
  - The number of observations (samples) taken during the day.
* [FLOAT]     `observation_percent`
  - The percent representing the number of observations taken with respect to the number scheduled to be taken during the day. This is only calculated for monitors where measurements are required (e.g., only certain parameters).
* [FLOAT]     `arithmetic_mean`
  - The average (arithmetic mean) value for the day.
* [FLOAT]     `first_max_value`
  - The highest value for the day.
* [INTEGER]   `first_max_hour`
  - The hour (on a 24-hour clock) when the highest value for the day (the previous field) was taken.
* [INTEGER]   `aqi`
  - The Air Quality Index for the day for the pollutant, if applicable.
* [INTEGER]   `method_code`
  - An internal system code indicating the method (processes, equipment, and protocols) used in gathering and measuring the sample. The method name is in the next column.
* [STRING]    `method_name`
  - A short description of the processes, equipment, and protocols used in gathering and measuring the sample.
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
