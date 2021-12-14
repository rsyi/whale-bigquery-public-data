# `noaa_global_forecast_system.NOAA_GFS0P25`
`bq-1` | `bigquery-public-data`

## Column details
* [DATETIME]  `creation_time`
  - Creation time of the forecast
* [GEOGRAPHY] `geography`
  - WGS84 Point Geometry
* [GEOGRAPHY] `geography_polygon`
  - WGS84 Polygon Geometry
* [RECORD]    `forecast`
* [INTEGER]   `forecast.hours`
* [DATETIME]  `forecast.time`
* [FLOAT]     `forecast.temperature_2m_above_ground`
  - Temperature 2m above ground. C
* [FLOAT]     `forecast.specific_humidity_2m_above_ground`
  - Specific humidity 2m above ground. kg/kg
* [FLOAT]     `forecast.relative_humidity_2m_above_ground`
  - Relative humidity 2m above ground. %
* [FLOAT]     `forecast.u_component_of_wind_10m_above_ground`
  - U component of wind 10m above ground. m/s
* [FLOAT]     `forecast.v_component_of_wind_10m_above_ground`
  - V component of wind 10m above ground. m/s
* [FLOAT]     `forecast.total_precipitation_surface`
  - Until 2019-11-07 06:00:00, this field represents the precipitation at surface at the forecasted time. After that date, this field holds the cumulative precipitation at surface added together from all forecasts starting from hour 0 (only for assets with forecast_hours > 0). kg/m^2
* [FLOAT]     `forecast.precipitable_water_entire_atmosphere`
  - Precipitable water for entire atmosphere. kg/m^2
* [FLOAT]     `forecast.total_cloud_cover_entire_atmosphere`
  - Total cloud cover for entire atmosphere (only for assets with forecast_hours > 0). %
* [FLOAT]     `forecast.downward_shortwave_radiation_flux`
  - Downward shortwave radiation flux (only for assets with forecast_hours > 0). W/m^2

-------------------------------------------------------------------------------
*Do not make edits above this line.*
