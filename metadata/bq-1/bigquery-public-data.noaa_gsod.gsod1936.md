# `noaa_gsod.gsod1936`
`bq-1` | `bigquery-public-data`
Global summary of day data for 18 surface meteorological elements are derived from the synoptic/hourly observations

## Column details
* [STRING]    `stn`
  - Station number (WMO/DATSAV3 number) for the location
* [STRING]    `wban`
  - WBAN number where applicable--this is the historical "Weather Bureau Air Force Navy" number - with WBAN being the acronym
* [STRING]    `year`
  - The year
* [STRING]    `mo`
  - The month
* [STRING]    `da`
  - The day
* [FLOAT]     `temp`
  - Mean temperature for the day in degrees Fahrenheit to tenths. Missing = 9999.9
* [INTEGER]   `count_temp`
  - Number of observations used in calculating mean temperature
* [FLOAT]     `dewp`
  - Mean dew point for the day in degreesm Fahrenheit to tenths.  Missing = 9999.9
* [INTEGER]   `count_dewp`
  - Number of observations used in calculating mean dew point
* [FLOAT]     `slp`
  - Mean sea level pressure for the day in millibars to tenths. Missing = 9999.9
* [INTEGER]   `count_slp`
  - Number of observations used in calculating mean sea level pressure
* [FLOAT]     `stp`
  - Mean station pressure for the day in millibars to tenths. Missing = 9999.9
* [INTEGER]   `count_stp`
  - Number of observations used in calculating mean station pressure
* [FLOAT]     `visib`
  - Mean visibility for the day in miles to tenths.  Missing = 999.9
* [INTEGER]   `count_visib`
  - Number of observations used in calculating mean visibility
* [STRING]    `wdsp`
  - Mean wind speed for the day in knots to tenths. Missing = 999.9
* [STRING]    `count_wdsp`
  - Number of observations used in calculating mean wind speed
* [STRING]    `mxpsd`
  - Maximum sustained wind speed reported for the day in knots to tenths. Missing = 999.9
* [FLOAT]     `gust`
  - Maximum wind gust reported for the day in knots to tenths. Missing = 999.9
* [FLOAT]     `max`
  - Maximum temperature reported during the day in Fahrenheit to tenths--time of max temp report varies by country and region, so this will sometimes not be the max for the calendar day. Missing = 9999.9
* [STRING]    `flag_max`
  - Blank indicates max temp was taken from the explicit max temp report and not from the 'hourly' data.
* indicates max temp was  derived from the hourly data (i.e., highest hourly or synoptic-reported temperature)
* [FLOAT]     `min`
  - Minimum temperature reported during the day in Fahrenheit to tenths--time of min temp report varies by country and region, so this will sometimes not be the min for the calendar day. Missing = 9999.9
* [STRING]    `flag_min`
  - Blank indicates min temp was taken from the explicit min temp report and not from the 'hourly' data.
* indicates min temp was derived from the hourly data (i.e., lowest hourly or synoptic-reported temperature)
* [FLOAT]     `prcp`
  - Total precipitation (rain and/or melted snow) reported during the day in inches and hundredths; will usually not end with the midnight observation--i.e., may include latter part of previous day. 
.00 indicates no measurable precipitation (includes a trace).
Missing = 99.99
Note: Many stations do not report '0' on days with no precipitation--therefore, '99.99' will often appear on these days. Also, for example, a station may only report a 6-hour amount for the period during which rain fell. See Flag field for source of data
* [STRING]    `flag_prcp`
  - A = 1 report of 6-hour precipitation amount
B = Summation of 2 reports of 6-hour precipitation amount
C = Summation of 3 reports of 6-hour precipitation amount
D = Summation of 4 reports of 6-hour precipitation amount
E = 1 report of 12-hour precipitation amount
F = Summation of 2 reports of 12-hour precipitation amount
G = 1 report of 24-hour precipitation amount
H = Station reported '0' as the amount for the day (eg, from 6-hour reports), but also reported at least one occurrence of precipitation in hourly observations--this could indicate a trace occurred, but should be considered as incomplete data for the day.
I = Station did not report any precip data for the day and did not report any occurrences of precipitation in its hourly observations--it's still possible that precip occurred but was not reported
* [FLOAT]     `sndp`
  - Snow depth in inches to tenths--last report for the day if reported more thanonce. Missing = 999.9
Note: Most stations do not report '0' ondays with no snow on the ground--therefore, '999.9' will often appear on these days
* [STRING]    `fog`
  - Indicators (1 = yes, 0 = no/not reported) for the occurrence during the day
* [STRING]    `rain_drizzle`
  - Indicators (1 = yes, 0 = no/not reported) for the occurrence during the day
* [STRING]    `snow_ice_pellets`
  - Indicators (1 = yes, 0 = no/not reported) for the occurrence during the day
* [STRING]    `hail`
  - Indicators (1 = yes, 0 = no/not reported) for the occurrence during the day
* [STRING]    `thunder`
  - Indicators (1 = yes, 0 = no/not reported) for the occurrence during the day
* [STRING]    `tornado_funnel_cloud`
  - Indicators (1 = yes, 0 = no/not reported) for the occurrence during the day

-------------------------------------------------------------------------------
*Do not make edits above this line.*
