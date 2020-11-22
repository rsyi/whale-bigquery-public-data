# `samples.gsod`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `station_number`
  - The World Meteorological Organization (WMO) / DATSAV3 station number where the data was collected.
* [INTEGER]   `wban_number`
  - The Weather-Bureau-Army-Navy (WBAN) station number where the data was collected.
* [INTEGER]   `year`
  - The year the data was collected in
* [INTEGER]   `month`
  - The month the data was collected in
* [INTEGER]   `day`
  - The day the data was collected in.
* [FLOAT]     `mean_temp`
  - The mean temperature of the day in degrees Fahrenheit, accurate to one tenth of a degree.
* [INTEGER]   `num_mean_temp_samples`
  - The number of observations used to calculate mean_temp.
* [FLOAT]     `mean_dew_point`
  - The mean dew point of the day in degrees Fahrenheit, accurate to one tenth of a degree.
* [INTEGER]   `num_mean_dew_point_samples`
  - The number of observations used to calculate mean_dew_point.
* [FLOAT]     `mean_sealevel_pressure`
  - The mean sea level pressure of the day in millibars, accurate to one tenth of a millibar
* [INTEGER]   `num_mean_sealevel_pressure_samples`
  - The number of observations used to calculate mean_sealevel_pressure.
* [FLOAT]     `mean_station_pressure`
  - The mean station pressure of the day in millibars, accurate to one tenth of a millibar.
* [INTEGER]   `num_mean_station_pressure_samples`
  - The number of observations used to calculate mean_station_pressure.
* [FLOAT]     `mean_visibility`
  - The mean visibility of the day in miles, accurate to one tenth of a mile.
* [INTEGER]   `num_mean_visibility_samples`
  - The number of observations used to calculate mean_visibility.
* [FLOAT]     `mean_wind_speed`
  - The mean wind speed of the day in knots, accurate to one tenth of a knot.
* [INTEGER]   `num_mean_wind_speed_samples`
  - The number of observations used to calculate mean_wind_speed.
* [FLOAT]     `max_sustained_wind_speed`
  - The maximum sustained wind speed reported on the day in knots, accurate to one tenth of a knot.
* [FLOAT]     `max_gust_wind_speed`
  - The maximum wind gust speed reported on the day in knots, accurate to one tenth of a knot
* [FLOAT]     `max_temperature`
  - The maximum temperature of the day in degrees Fahrenheit, accurate to one tenth of a degree. The time that this value is reported differs by country and region, so this value will sometimes not be the maximum for the calendar day.
* [BOOLEAN]   `max_temperature_explicit`
  - Indicates the source of max_temperature.
* [FLOAT]     `min_temperature`
  - The minimum temperature of the day in degrees Fahrenheit, accurate to one tenth of a degree. The time that this value is reported differs by country and region, so this value will sometimes not be the minimum for the calendar day.
* [BOOLEAN]   `min_temperature_explicit`
  - Indicates the source of min_temperature.
* [FLOAT]     `total_precipitation`
  - The total precipitation of the day in inches, accurate to one hundredth of an inch.
* [FLOAT]     `snow_depth`
  - The snow depth of the day in inches, accurate to one tenth of an inch.
* [BOOLEAN]   `fog`
  - Indicates if fog was reported on this day.
* [BOOLEAN]   `rain`
  - Indicates if rain was reported on this day.
* [BOOLEAN]   `snow`
  - Indicates if snow was reported on this day.
* [BOOLEAN]   `hail`
  - Indicates if hail was reported on this day.
* [BOOLEAN]   `thunder`
  - Indicates if thunder was reported on this day.
* [BOOLEAN]   `tornado`
  - Indicates if a tornado was reported on this day.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
