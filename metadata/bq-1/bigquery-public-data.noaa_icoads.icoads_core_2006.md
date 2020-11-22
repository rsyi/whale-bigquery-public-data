# `noaa_icoads.icoads_core_2006`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `year`
  - Year of the actual time of observation at which the barometer is read. It is 4-digit
* [INTEGER]   `month`
  - Month of the actual time of observation at which the barometer is read. (1=January, 2=February, …, 12=December)
* [INTEGER]   `day`
  - Day of the actual time of observation at which the barometer is read. Days 1-31
* [FLOAT]     `hour`
  - Hour of the actual time of observation at which the barometer is read. Hours 0.00 to 23.99
* [FLOAT]     `latitude`
  - Position to hundredths of a degree +N or –S (measured north or south of the equator) and +E or −W (measured east or west of the Greenwich Meridian).
* [FLOAT]     `longitude`
  - Position to hundredths of a degree +N or –S (measured north or south of the equator) and +E or −W (measured east or west of the Greenwich Meridian).
* [INTEGER]   `imma_version`
  - IMMA Version: 0=2010, 1=2016
* [INTEGER]   `attm_count`
  - The attm count: 0 – abbreviated record (no attm) 1 – one attm 2 – two attms etc.
* [INTEGER]   `time_indicator`
  - Time indicator preserves the incoming precision of time fields: 0 – nearest whole hour 1 – hour to tenths 2 – hour plus minutes 3 – high resolution (e.g., hour to hundredths)
* [INTEGER]   `latlong_indicator`
  - Latlong indicator preserves the precision at which LAT and LON were recorded or translated from, or if they were derived later by interpolation between known positions: 0 – degrees and tenths 1 – whole degrees 2 – mixed precision 3 – interpolated 4 – degrees and minutes 5 – high resolution data (e.g., degrees to seconds) 6 – other
* [INTEGER]   `ship_course`
  - True direction of resultant displacement of the ship during the three hours preceding the time of observation (i.e., ship’s course (true) made good): 0 – stationary (ship hove to) 5 – SW 1 – NE 6 – W 2 – E 7 – NW 3 – SE 8 – N 4 – S 9 – unknown
* [INTEGER]   `ship_speed`
  - Ship’s average speed made good during the three hours preceding the time of observation (beginning 1 January 1968): 0 – 0 knots  1 – 1-5 knots 2 – 6-10 knots 3 – 11-15 knots 4 – 16-20 knots  5 – 21-25 knots 6 – 26-30 knots 7 – 31-35 knots 8 – 36-40 knots 9 – over 40 knots.    Prior to 1 January 1968 a different code for VS, also with range 0-9, applied (Met Office 1948): 0 – 0 knots 1 – 1-3 knots 2 – 4-6 knots 3 – 7-9 knots 4 – 10-12 knots 5 – 13-15 knots  6 – 16-18 knots 7 – 19-21 knots 8 – 22-24 knots 9 – over 24 knots
* [INTEGER]   `national_source_indicator`
  - A field available for national use in identifying data subsets.
* [INTEGER]   `id_indicator`
  - ID Indicator indicates whether a callsign or some other sort of identification is contained in the ID field (and in R3.0 data, II should always be extant when ID information exists; whereas II should always be missing if ID is missing): 0 – ID present, but unknown type 1 – ship, Ocean Station Vessel (OSV), or ice station callsign 2 – generic ID (e.g., SHIP, BUOY, RIGG, PLAT) 3 – WMO 5-digit buoy number 4 – other buoy number (e.g., Argos or national buoy number) 5 – Coastal-Marine Automated Network (C-MAN) ID (assigned by US NDBC or other organizations) 6 – station name or number 7 – oceanographic platform/cruise number 8 – fishing vessel psuedo-ID 9 – national ship number 10 – composite information from early ship data 11 – 7-digit buoy ID (proposed)
* [STRING]    `callsign`
  - Identification/Callsign
* [STRING]    `country_code`
  - The country that recruited a ship, which may differ from the country of immediate receipt (C2, field 15) and may also differ from the ship’s registry
* [INTEGER]   `wind_direction_indicator`
  - Gives the compass (and approximate precision) used for reporting the wind direction: 0 – 36-point compass 1 – 32-point compass 2 – 16 of 36-point compass 3 – 16 of 32-point compass 4 – 8-point compass 5 – 360-point compass 6 – high resolution data (e.g., tenths of degrees)
* [INTEGER]   `wind_direction_true`
  - The direction (true) from which wind is blowing (or will blow), stored in whole degrees (i.e., 360-point compass; range: 1-360°), or special codes: 361 – calm 362 – variable, or all directions
* [INTEGER]   `wind_speed_indicator`
  - Wind speed is stored in tenths of a meter per second (to retain adequate precision for winds converted from knots, or high-resolution data). WI shows the units in which and/or the method by which W was originally recorded (0, 1, 3, 4 follow WMO Code 1855): 0 – meter per second, estimated 53 1 – meter per second, obtained from anemometer (measured) 2 – estimated (original units unknown) 3 – knot, estimated 4 – knot, obtained from anemometer (measured) 5 – Beaufort force (based on documentation) 6 – estimated (original units unknown)/unknown method 7 – measured (original units unknown) 8 – high-resolution measurement (e.g., hundredths of a meter per second)
* [FLOAT]     `wind_speed`
  - Wind speed which is stored in tenths of a meter per second (to retain adequate precision for winds converted from knots, or high-resolution data)
* [INTEGER]   `visibility_indicator`
  - shows whether visibility was: 0 – estimated (or unknown method of observation) 1 – measured 2 – fog present (obsolete)
* [INTEGER]   `visibility`
  - Visibility (horizontal visibility at the surface in kilometers) according to WMO Code 4377 from which, in reporting visibility at sea, WMO (2009a; Reg. 12.2.1.3.2) states that the decile 90-99 shall be used (moreover Reg. 12.2.1.3.1: when the horizontal visibility is not the same in different directions, the shortest distance shall be given for VV): 90 – less than 0.05 kilometer 91 – 0.05 92 – 0.2 93 – 0.5 94 – 1 95 – 2 96 – 4 97 – 10 98 – 20 99 – 50 or more
* [INTEGER]   `present_weather`
  - WMO Codes 4677 (Table D3) for WW, and 4561 for W1: 0 – Cloud covering 1/2 or less of the sky throughout the appropriate period 1 – Cloud covering more than 1/2 of the sky during part of the appropriate period and covering 1/2 or less during part of the period 2 – Cloud covering more than 1/2 of the sky throughout the appropriate period 54 3 – Sandstorm, duststorm or blowing snow 4 – Fog or ice fog or thick haze 5 – Drizzle 6 – Rain 7 – Snow, or rain and snow mixed 8 – Shower(s) 9 – Thunderstorm(s) with or without precipitation
* [INTEGER]   `past_weather`
  - WMO Codes 4677 (Table D3) for WW, and 4561 for W1: 0 – Cloud covering 1/2 or less of the sky throughout the appropriate period 1 – Cloud covering more than 1/2 of the sky during part of the appropriate period and covering 1/2 or less during part of the period 2 – Cloud covering more than 1/2 of the sky throughout the appropriate period 54 3 – Sandstorm, duststorm or blowing snow 4 – Fog or ice fog or thick haze 5 – Drizzle 6 – Rain 7 – Snow, or rain and snow mixed 8 – Shower(s) 9 – Thunderstorm(s) with or without precipitation
* [FLOAT]     `sea_level_pressure`
  - Amount of pressure tendency at station level during the three hours preceding the time of observation in tenths of hPa (i.e., millibars)
* [INTEGER]   `characteristic_of_ppp`
  - WMO Code 0200 for characteristic of pressure tendency during the three hours preceding the time of observation (A) (after WMO 2015).
* [FLOAT]     `amt_pressure_tend`
  - Amount of pressure tendency at station level during the three hours preceding the time of observation in tenths of hPa (i.e., millibars)
* [INTEGER]   `indicator_for_temp`
  - Indicator provides information about the precision and/or units that the Core temperature elements were translated from: 0 – tenths °C 1 – half °C 2 – whole °C 3 – whole or tenths °C (mixed precision among temperature fields) 4 – tenths °F 5 – half °F 6 – whole °F 7 – whole or tenths °F (mixed precision among temperature fields) 8 – high resolution data (e.g., hundredths °C) 9 – other
* [FLOAT]     `air_temperature`
  - Air temperature, Celsius
* [INTEGER]   `wbt_indicator`
  - WBTI and DPTI indicate which of WBT or DPT was measured or computed, and ice bulb conditions: 0 – measured 1 – computed 2 – iced measured 3 – iced computed
* [FLOAT]     `wetbulb_temperature`
  - Wet-bulb temperature, Celsius
* [INTEGER]   `dpt_indicator`
  - WBTI and DPTI indicate which of WBT or DPT was measured or computed, and ice bulb conditions: 0 – measured 1 – computed 2 – iced measured 3 – iced computed
* [FLOAT]     `dewpoint_temperature`
  - Dew-point temperature, Celsius
* [INTEGER]   `sst_measurement_method`
  - Shows the method by which SST was taken: 0 – bucket 1 – condenser inlet (intake) 2 – trailing thermistor 3 – hull contact sensor 4 – through hull sensor 5 – radiation thermometer 6 – bait tanks thermometer 7 – others 9 – unknown or non-bucket 10 – “implied” bucket [note: applicable to early ICOADS data] 11 – reversing thermometer or mechanical sensor 12 – electronic sensor
* [FLOAT]     `sea_surface_temp`
  - Temperatures are stored in tenths of a degree Celsius.
* [INTEGER]   `total_cloud_amount`
  - Codes 0 to 9 (WMO Code 2700) show the total fraction of the celestial dome covered by clouds (irrespective of their genus). 0 – clear 1 – 1 okta or less, but not zero 2-6 – 2-6 oktas 7 – 7 oktas or more, but not 8 oktas 8 – 8 oktas 9 – sky obscured by fog and/or other meteorological phenomena
* [INTEGER]   `lower_cloud_amount`
  - 0 – clear 1 – 1 okta or less, but not zero 2-6 – 2-6 oktas 7 – 7 oktas or more, but not 8 oktas 8 – 8 oktas 9 – sky obscured by fog and/or other meteorological phenomena
* [STRING]    `low_cloud_type`
  - Codes 0 to 10 [A in base36 encoding] show characteristics observed of clouds of the genera Stratocumulus, Stratus, Cumulus, and Cumulonimbus (WMO Code 0513
* [INTEGER]   `cloud_height_indicator`
  - Shows if cloud height H was: 0 – estimated 1 – measured
* [STRING]    `cloud_height`
  - Codes 0 to 9 and “A” (following WMO Code 1600) show the height above surface of the base of the lowest cloud seen (such that a height exactly equal to one of the values at  60 the ends of the ranges shall be coded in the higher range, e.g., a height of 600 m shall be reported by code 5): 0 – 0 to 50 m 1 – 50 to 100 m 2 – 100 to 200 m 3 – 200 to 300 m 4 – 300 to 600 m 5 – 600 to 1000 m 6 – 1000 to 1500 m 7 – 1500 to 2000 m 8 – 2000 to 2500 m 9 – 2500 m or more, or no clouds 10 [A in base36 encoding] – height of base of cloud not known or base of clouds at a level lower and tops at a level higher than that of the station
* [STRING]    `middle_cloud_type`
  - Codes 0 to 10 [A in base36 encoding] show characteristics observed of clouds of the genera Altocumulus, Altostratus, and Nimbostratus (WMO Code 0515).
* [STRING]    `high_cloud_type`
  - Codes 0 to 10 [A in base36 encoding] show characteristics observed of clouds of the genera Cirrus, Cirrocumulus and Cirrostratus (WMO Code 0509).
* [INTEGER]   `wave_direction`
  - Starting in 1968, WD was no longer reported in the SHIP code. Codes 00 to 36 (note: leading zero is omitted in IMMA) show the direction (if any) from which (wind) waves come, in tens of degrees (following WMO Code 0877; ref. Code and Range columns in Table D2). Codes 37 and 38 show: 37 – waves confused, direction indeterminate (WH ≤ 4.75 m) 38 – waves confused, direction indeterminate (WH > 4.75 m; or irrespective of wave height, corresponding to 99 in WMO Code 0877)
* [INTEGER]   `wave_period`
  - Period of wind waves, in seconds. Starting in 1968, WP was reported in seconds; prior to 1968 the period was reported as a code, which was converted into whole seconds following Table D5a, with WX (C1, field 13) set accordingly.
* [FLOAT]     `wave_height`
  - Height of wind waves, in metres.
* [INTEGER]   `swell_direction`
  - Starting in 1968, SD was no longer reported in the SHIP code. Codes 00 to 36 (note: leading zero is omitted in IMMA) show the direction (if any) from which (wind) waves come, in tens of degrees (following WMO Code 0877; ref. Code and Range columns in Table D2). Codes 37 and 38 show: 37 – waves confused, direction indeterminate (SH ≤ 4.75 m) 38 – waves confused, direction indeterminate (SH > 4.75 m; or irrespective of wave height, corresponding to 99 in WMO Code 0877)
* [INTEGER]   `swell_period`
  - Period of wind waves, in seconds. Starting in 1968, SP was reported in seconds; prior to 1968 the period was reported as a code, which was converted into whole seconds following Table D5a, with WX (C1, field 13) set accordingly.
* [FLOAT]     `swell_height`
  - Height of wind waves, in metres.
* [STRING]    `box_system_indicator`
  - The box system indicator is currently unused.
* [INTEGER]   `ten_degree_box_number`
  - 10° box numbers (see Release 1, supp. G; http://icoads.noaa.gov/Release_1/suppG.html) are available e.g., for use in sorting operations
* [INTEGER]   `one_degree_box_number`
  - 1° box numbers (see Release 1, supp. G; http://icoads.noaa.gov/Release_1/suppG.html) are available e.g., for use in sorting operations
* [INTEGER]   `deck`
  - Number of the deck from which the report came (Table D6a), with Tables D6b and D6c providing additional information about selected DCK ranges. “Deck” originally referred to a punched card deck, but is now used as the primary field to track ICOADS data collections.
* [INTEGER]   `source_id`
  - Number of the source ID from which the report came (Table D7). Each SID may contain a single deck or a mixture of decks, but each SID is generally constrained to a single input format.
* [INTEGER]   `platform_type`
  - The type of observing platform: 0 – US Navy or “deck” log, or unknown 1 – merchant ship or foreign military 2 – ocean station vessel—off station or station proximity unknown 3 – ocean station vessel—on station 4 – lightship 5 – ship 6 – moored buoy 7 – drifting buoy 8 – ice buoy [note: currently unused] 9 – ice station (manned, including ships overwintering in ice) 10 – oceanographic station data (bottle and low-resolution CTD/XCTD data) 11 – mechanical/digital/micro bathythermograph (MBT) 12 – expendable bathythermograph (XBT) 13 – Coastal-Marine Automated Network (C-MAN) (NDBC operated) 14 – other coastal/island station 15 – fixed (or mobile) ocean platform (plat, rig) 16 – tide gauge 17 – high-resolution Conductivity-Temp.-Depth (CTD)/Expendable CTD (XCTD) 74 18 – profiling float 19 – undulating oceanographic recorder 20 – autonomous pinneped bathythermograph 21 – glider
* [INTEGER]   `dup_status`
  - Indicates duplicate status. 0 unique 1 best duplicate 2 best duplicate with substitution
* [INTEGER]   `dup_check`
  - The presence of a duplicate match between a Global Telecommunication System (GTS) and logbook (or other delayed-mode) report may provide some location verification, with greater credibility if SLP and SST match under “allowances.” DUPC indicates whether such matches were detected during duplicate elimination processing (either the GTS or delayed-mode report is retained in the output data mixture), in case users might wish to make use of this information for independent quality control purposes: 0 – GTS and logbook match with SLP and SST match 1 – GTS and logbook match without SLP and SST match 2 – no GTS and logbook match was encountered
* [INTEGER]   `track_check`
  - Indicates if a report was: 0 – not track checked 1 – track checked
* [INTEGER]   `pressure_bias`
  - Indicates questionable sea level pressure data: 0 – questionable SLP: level 0: individual platform (unused) 1 – questionable SLP: level 1: deck 2 – questionable SLP: level 2: deck
* [INTEGER]   `wave_period_indicator`
  - Indicates that the wave and swell periods were converted from code into whole seconds: 1 – period converted from code into whole seconds
* [INTEGER]   `swell_period_indicator`
  - Indicates that the wave and swell periods were converted from code into whole seconds: 1 – period converted from code into whole seconds
* [INTEGER]   `second_country_code`
  - The country of immediate receipt (C2), which may differ from the recruiting country (C1) and may also differ from the ship’s registry.
* [STRING]    `adaptive_qc_flags`
  - SQZ indicates the relationship of SST to “adaptive” QC limits in 0.5σ (standard deviation) increments, and SQZ provides a measure of the reliability of the QC
* [INTEGER]   `nightday_flag`
  - The night/day report flag was set to indicate whether the report fell in local nighttime or daytime, as determined according to Slutz et al. 1 = report time is local nighttime 2 = report time is local daytime
* [STRING]    `trimming_flags`
  - These flags indicate the relationship of a given observational data value to the legacy trimming limits, or to indicate if those limits, which were calculated separately for three historical periods are unavailable, or other conditions.
* [STRING]    `ncdc_qc_flags`
  - Possible NCDC-QC flag values, where “–” indicates an undefined flag value, or letters included in the table indicate a defined flag value. For the letters, lower-case “x” indicates a flag value not utilized, whereas upper-case flag values were utilized, in preparing enhanced or standard trimmed data
* [INTEGER]   `external`
  - The single extant value of the external flags is defined as 1 = erroneous (based on external OSD buoy quality control) They range from 0-63
* [INTEGER]   `landlocked_flag`
  - The single extant value of the landlocked flag (LZ) is defined as 1 = report over land If LZ is missing, this indicates that the report falls over an ocean or coastal region as defined by a “landlocked” file at 2°×2° resolution
* [INTEGER]   `source_exclusion_flags`
  - The single extant value of the source exclusion flags is defined as 1 = data automatically disqualified from statistics They range from 0-31
* [STRING]    `unique_report_id`
  - A unique ID for each record in ICOADS represented as a base36 number of length 6.
* [INTEGER]   `release_no_primary`
  - First of the three elements that make up the full release number associated with the record. For example, Release 3.0.1 is represented with RN1=3, RN2=0, and RN3=1
* [INTEGER]   `release_no_secondary`
  - Second of the three elements that make up the full release number associated with the record. For example, Release 3.0.1 is represented with RN1=3, RN2=0, and RN3=1
* [INTEGER]   `release_no_tertiary`
  - Third of the three elements that make up the full release number associated with the record. For example, Release 3.0.1 is represented with RN1=3, RN2=0, and RN3=1
* [INTEGER]   `release_status_indicator`
  - An indicator that specifies whether the record is: 0 – Preliminary (Not yet included in an official ICOADS Release) 1 – Auxiliary (Records provided in separate data files in addition to ICOADS official Releases and Preliminary data. This also includes new data sources received, but awaiting blending into an official ICOADS Release) 2 – Full (A record included in an official ICOADS Release)
* [INTEGER]   `intermediate_reject_flag`
  - 0=Retain in Intermediate, Reject from Final dataset;  1=Retain in both Intermediate and Final datasets;  2=Reject from both Intermediate and Final datasets
* [TIMESTAMP] `timestamp`
  - Converted UTC timestamp for the actual time of observation at which the barometer is read

-------------------------------------------------------------------------------
*Do not make edits above this line.*
