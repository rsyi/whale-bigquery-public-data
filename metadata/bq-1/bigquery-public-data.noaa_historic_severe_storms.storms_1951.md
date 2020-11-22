# `noaa_historic_severe_storms.storms_1951`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `episode_id`
  - ID assigned by NWS to denote the storm episode; links the event details file with the information within location file
* [STRING]    `event_id`
  - ID assigned by NWS to note a single, small part that goes into a specific storm episode; links the storm episode between the three files downloaded from SPC’s website
* [STRING]    `state`
  - The full text state name where the event occurred
* [STRING]    `state_fips_code`
  - "Unique FIPS code identifier assigned to each state.   State names and their corresponding FIPS codes are available as a BigQuery Public Dataset: bigquery-public-data.census_fips_codes.states_2016  The geographic polygons that define the perimeter of each state are available as a BigQuery Public Dataset: bigquery-public-data.geo_us_boundaries.us_states "
* [STRING]    `event_type`
  - The only events permitted in Storm Data are listed in Table 1 of Section 2.1.1 of NWS Directive 10-1605 at http://www.nws.noaa.gov/directives/sym/pd01016005curr.pdf. The chosen event type is the one that most accurately describes the meteorological event leading to fatalities, injuries, damage, etc. However, significant events, such as tornadoes, having no impact or causing no damage, are also included in Storm Data.
* [STRING]    `cz_type`
  - "Indicates whether the event happened in   - C: County/Parish  - Z: NWS zone  - M: Marine"
* [STRING]    `cz_fips_code`
  - "Unique FIPS code identifier assigned to each county.   State names and their corresponding FIPS codes are available as a BigQuery Public Dataset: bigquery-public-data.census_fips_codes.counties_2016  The geographic polygons that define the perimeter of each state are available as a BigQuery Public Dataset: bigquery-public-data.geo_us_boundaries.us_counties "
* [STRING]    `cz_name`
  - "(County/Parish, Zone or Marine Name assigned to the county FIPS number or NWS Forecast Zone  NWS Forecast Zones are available as a BigQuery Public Dataset: bigquery-public-data.noaa_historic_severe_storms.nws_forecast_zones        "
* [STRING]    `wfo`
  - National Weather Service Forecast Office’s area of responsibility (County Warning Area) in which the event occurred
* [DATETIME]  `event_begin_time`
  - The date and time that the event began. Note that episodes and events may have different start and end times if multiple events occured in the same episode
* [STRING]    `event_timezone`
  - The time zone in which the event_begin_time and the event_end_time is recorded.
* [DATETIME]  `event_end_time`
  - The date and time that the event ended. Note that episodes and events may have different start and end times if multiple events occured in the same episode
* [INTEGER]   `injuries_direct`
  - The number of injuries directly related to the weather event
* [INTEGER]   `injuries_indirect`
  - The number of injuries indirectly related to the weather event
* [INTEGER]   `deaths_direct`
  - The number of deathes directly related to the weather event
* [INTEGER]   `deaths_indirect`
  - The number of deathes indirectly related to the weather event
* [INTEGER]   `damage_property`
  - "The estimated amount of damage to property incurred by the weather event, in USD at the time of the event. Values are not adjusted for inflation  Note: Values listed as 0 do not necessarily mean that no property damage occurred as a result of the event"
* [INTEGER]   `damage_crops`
  - "The estimated amount of damage to crops incurred by the weather event, in USD at the time of the storm. Values are not adjusted for inflation  Note: Values listed as 0 do not necessarily mean that no property damage occurred as a result of the event"
* [STRING]    `source`
  - "Source reporting the weather event  Note: This can be any entry. Values are not restricted to specific categories"
* [FLOAT]     `magnitude`
  - "Measured extent of the magnitude type. This is only used for wind speeds and hail size.   Wind speeds are in MPH; Hail sizes are in inches"
* [STRING]    `magnitude_type`
  - "Differentiates between the type of mangitude measured.    - EG = Wind Estimated Gust  - ES = Estimated Sustained Wind  - MS = Measured Sustained Wind  - MG = Measured Wind Gust  No magnitude type is included for hail"
* [STRING]    `flood_cause`
  - Reported or estimated cause of the flood
* [STRING]    `tor_f_scale`
  - "Enhanced Fujita Scale describes the strength of the tornado based on the amount and type of damage caused by the tornado. The F-scale of damage will vary in the destruction area; therefore, the highest value of the F-scale is recorded for each event.    - EF0 – Light Damage (40 – 72 mph)   - EF1 – Moderate Damage (73 – 112 mph)   - EF2 – Significant damage (113 – 157 mph)   - EF3 – Severe Damage (158 – 206 mph)   - EF4 – Devastating Damage (207 – 260 mph)   - EF5 – Incredible Damage (261 – 318 mph)"
* [STRING]    `tor_length`
  - Length of the tornado or tornado segment while on the ground (minimal of tenths of miles)
* [STRING]    `tor_width`
  - Width of the tornado or tornado segment while on the ground (in feet)
* [STRING]    `tor_other_wfo`
  - Indicates the continuation of a tornado segment as it crossed from one National Weather Service Forecast Office to another. The subsequent WFO identifier is provided within this field.
* [STRING]    `location_index`
  - Number assigned by NWS to specific locations within the same Storm event. Each event’s sequentially increasing location index number will have a corresponding lat/lon point
* [FLOAT]     `event_range`
  - A hydro-meteorological event will be referenced, minimally, to the nearest tenth of a mile, to the geographical center (not from the village/city boundaries or limits) of a particular village/city, airport, or inland lake, providing that the reference point is documented in the Storm Data software location database.
* [STRING]    `event_azimuth`
  - 16-point compass direction from a particular village/city, airport, or inland lake, providing that the reference point is documented in the Storm Data software location database of > 130,000 locations.
* [STRING]    `reference_location`
  - Reference location of the center from which the range is calculated and the azimuth is determined
* [FLOAT]     `event_latitude`
  - The latitude where the event occurred (rounded to the hundredths in decimal degrees; includes an ‘-‘ if it’s S of the Equator)
* [FLOAT]     `event_longitude`
  - The longitude where the event occurred (rounded to the hundredths in decimal degrees; includes an ‘-‘ if it’s W of the Prime Meridian)
* [GEOGRAPHY] `event_point`
  - Geographic representation of the event_longitude and latitude

-------------------------------------------------------------------------------
*Do not make edits above this line.*
