# `nasa_wildfire.past_week`
`bq-1` | `bigquery-public-data`

## Column details
* [FLOAT]     `latitude`
  - Center of nominal 375 m fire pixel
* [FLOAT]     `longitude`
  - Center of nominal 375 m fire pixel
* [FLOAT]     `bright_ti4`
  - Brightness temperature I-4: VIIRS I-4 channel brightness temperature of the fire pixel measured in Kelvin.
* [FLOAT]     `scan`
  - The algorithm produces approximately 375 m pixels at nadir. Scan and track reflect actual pixel size.
* [FLOAT]     `track`
  - The algorithm produces approximately 375 m pixels at nadir. Scan and track reflect actual pixel size.
* [DATE]      `acq_date`
  - Date of VIIRS acquisition.
* [TIME]      `acq_time`
  - Time of acquisition/overpass of the satellite (in UTC).
* [STRING]    `satellite`
  - N= Suomi National Polar-orbiting Partnership (Suomi-NPP)
* [STRING]    `confidence`
  - This value is based on a collection of intermediate algorithm quantities used in the detection process. It is intended to help users gauge the quality of individual hotspot/fire pixels. Confidence values are set to low, nominal and high. Low confidence daytime fire pixels are typically associated with areas of sun glint and lower relative temperature anomaly (<15K) in the mid-infrared channel I4. Nominal confidence pixels are those free of potential sun glint contamination during the day and marked by strong (>15K) temperature anomaly in either day or nighttime data. High confidence fire pixels are associated with day or nighttime saturated pixels.
* [STRING]    `version`
  - Version identifies the collection (e.g. VIIRS Collection 1) and source of data processing: Near Real-Time (NRT suffix added to collection) or Standard Processing (collection only). 1.0NRT - Collection 1 NRT processing. 1.0 - Collection 1 Standard processing
* [FLOAT]     `bright_ti5`
  - Brightness temperature I-5: I-5 Channel brightness temperature of the fire pixel measured in Kelvin.
* [FLOAT]     `frp`
  - Fire Radiative Power: FRP depicts the pixel-integrated fire radiative power in MW (megawatts). FRP depicts the pixel-integrated fire radiative power in MW (megawatts). Given the unique spatial and spectral resolution of the data, the VIIRS 375 m fire detection algorithm was customized and tuned in order to optimize its response over small fires while balancing the occurrence of false alarms. Frequent saturation of the mid-infrared I4 channel (3.55-3.93 µm) driving the detection of active fires requires additional tests and procedures to avoid pixel classification errors. As a result, sub-pixel fire characterization (e.g., fire radiative power [FRP] retrieval) is only viable across small and/or low-intensity fires. Systematic FRP retrievals are based on a hybrid approach combining 375 and 750 m data. In fact, starting in 2015 the algorithm incorporated additional VIIRS channel M13 (3.973-4.128 µm) 750 m data in both aggregated and unaggregated format.
* [STRING]    `daynight`
  - D= Daytime fire, N= Nighttime fire
* [TIMESTAMP] `acquisition_timestamp`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
