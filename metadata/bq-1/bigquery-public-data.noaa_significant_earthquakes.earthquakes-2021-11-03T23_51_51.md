# `noaa_significant_earthquakes.earthquakes-2021-11-03T23_51_51`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
* [STRING]    `flag_tsunami`
  - If a tsunami was recorded.
* [INTEGER]   `year`
  - Century and year of the significant earthquake. Format +/-yyyy (-is B.C, +is A.D.). Valid values: -2000 to present. The Date and Time are given in Universal Coordinated Time.
* [INTEGER]   `month`
  - Month of the significant earthquake. Valid values: 1-12. The Date and Time are given in Universal Coordinated Time. The local date may be one day different.
* [INTEGER]   `day`
  - Day of the significant earthquake. Valid values: 1-31 (where months apply). The Date and Time are given in Universal Coordinated Time. The local date may be one day different.
* [INTEGER]   `hour`
  - Hour of the significant earthquake. Valid values: 0-23. The Date and Time are given in Universal Coordinated Time. The local date may be one day different.
* [INTEGER]   `minute`
  - Minute of the significant earthquake. Valid values: 0-59. The Date and Time are given in Universal Coordinated Time. The local date may be one day different.
* [FLOAT]     `second`
  - Second of the significant earthquake. Valid values: 0-59. The Date and Time are given in Universal Coordinated Time. The local date may be one day different.
* [INTEGER]   `focal_depth`
  - The depth of the earthquake is given in kilometers. Valid values 0 to 700 km.
* [FLOAT]     `eq_primary`
  - The primary earthquake magnitude is chosen from the available magnitude scales in this order: Mw Magnitude  Ms Magnitude  Mb Magnitude  Ml Magnitude  Mfa Magnitude  Unknown Magnitude
* [FLOAT]     `eq_mag_mw`
  - Earthquake magnitude Mw. Valid values 0 to 9.9 The Mw magnitude is based on the moment magnitude scale
* [FLOAT]     `eq_mag_ms`
  - Earthquake magnitude MS. Valid values 0 to 9.9 The Ms magnitude is the surface-wave magnitude of the earthquake.
* [FLOAT]     `eq_mag_mb`
  - Earthquake magnitude mb. Valid values 0 to 9.9 The Mb magnitude is the compressional body wave (P-wave) magnitude.
* [FLOAT]     `eq_mag_ml`
  - Earthquake magnitude ML. Valid values 0 to 9.9 The ML magnitude was the original magnitude relationship defined by Richter and Gutenberg for local earthquakes in 1935.
* [FLOAT]     `eq_mag_mfa`
  - Earthquake magnitude Mfa (based on felt area). Valid values 0 to 9.9 The Mfa magnitudes are computed from the felt area, for earthquakes that occurred before seismic instruments were in general use.
* [FLOAT]     `eq_mag_unk`
  - Earthquake magnitude type is Unknown. Valid values 0 to 9.9 The computational method for the earthquake magnitude was unknown and could not be determined from the published sources.
* [INTEGER]   `intensity`
  - The effect of an earthquake on the Earth's surface is called the intensity. The Modified Mercalli Intensity (MMI) is given in Roman Numerals (converted to numbers in the digital database)
* [STRING]    `country`
  - Country. The name of the country where earthquake was located.
* [STRING]    `state`
  - The State, Province or Prefecture of the earthquake was located.
* [STRING]    `location_name`
  - Earthquake Location Name. The location (city, state or island) where the earthquake was located.
* [FLOAT]     `latitude`
  - Latitude: Valid values: -90 to +90 Latitude: 0 to 90 (Northern Hemisphere), -90 to 0 (Southern Hemisphere). The latitude of the location (city, state or island) where the earthquake was located.
* [FLOAT]     `longitude`
  - Longitude. Valid values: -180 to +180 Longitude: 0 to 180 (Eastern Hemisphere), -180 to 0 (Western Hemisphere). The longitude of the location (city, state or island) where the earthquake was located.
* [INTEGER]   `region_code`
  - Region Name (Code). Regional boundaries were assigned based on the frequency of occurrence of earthquakes, geophysical relations, risk in distant areas and political justification. The codes are defined as: 10 = Central, Western and S. Africa 15 = Northern Africa 20 = Antarctica 30 = East Asia 40 = Central Asia and Caucasus 50 = Kamchatka and Kuril Islands 60 = S. and SE. Asia and Indian Ocean 70 = Atlantic Ocean 80 = Bering Sea 90 = Caribbean 100 = Central America 110 = Eastern Europe 120 = Northern and Western Europe 130 = Southern Europe 140 = Middle East 150 = North America and Hawaii 160 = South America 170 = Central and South Pacific
* [INTEGER]   `deaths`
  - Number of deaths from the earthquake, it may also include deaths caused by the secondary effects such as the tsunami, volcanic eruption or landslide that was triggered by the earthquake.
* [INTEGER]   `deaths_description`
  - Description of Deaths from the earthquake. Valid values: 0 to 4. When a description was found in the historical literature instead of an actual number of deaths, this value was coded and listed in the Deaths_amount_order column. If the actual number of deaths was listed, a descriptor was also added for search purposes according to the following definition. 0 = None 1 = Few (~1 to 50 deaths)  2 = Some (~51 to 100 deaths)  3 = Many (~101 to 1000 deaths) 4 = Very Many (~1001 or more deaths)
* [INTEGER]   `missing`
  - Number of missing from the earthquake, it may also include missing caused by the secondary effects such as the tsunami, volcanic eruption or landslide that was triggered by the earthquake.
* [INTEGER]   `missing_description`
  - Description of Deaths from the earthquake. Valid values: 0 to 4. When a description was found in the historical literature instead of an actual number of missing, this value was coded and listed in the Missing_amount_order column. If the actual number of missing was listed, a descriptor was also added for search purposes according to the following definition. 0 = None 1 = Few (~1 to 50 missing)  2 = Some (~51 to 100 missing)  3 = Many (~101 to 1000 missing) 4 = Very Many (~1001 or more missing)
* [INTEGER]   `injuries`
  - Number of injuries from the earthquake, it may also include deaths caused by a secondary effect such as the tsunami, volcanic eruption or landslide that was triggered by the earthquake.
* [INTEGER]   `injuries_description`
  - Description of injuries from the earthquake. Valid values: 0 to 4. When a description was found in the historical literature instead of an actual number of injuries, this value was coded and listed in the Injuries_amount_order column. If the actual number of injuries was listed, a descriptor was also added for search purposes according to the following definition. 0 = None 1 = Few (~1 to 50 injuries)  2 = Some (~51 to 100 injuries)  3 = Many (~101 to 1000 injuries) 4 = Very Many (~1001 or more injuries)
* [FLOAT]     `damage_millions_dollars`
  - Damage in Millions of Dollars from the earthquake. The damage amount may also include damage caused by a secondary effect such as a tsunami, volcanic eruption, or landslide that was triggered by the earthquake. The value in the Damage column should be multipled by 1,000,000 to obtain the actual dollar amount in U.S. dollars. The dollar value listed is the value at the time of the event.
* [INTEGER]   `damage_description`
  - Description of Damage from the earthquake. For those events not offering a monetary evaluation of damage, the following five-level scale was used to classify damage and was listed in the  Damage column.  If the actual dollar amount of damage was listed, a descriptor was also added for search purposes. 0 = NONE 1 = LIMITED (roughly corresponding to less than $1 million) 2 = MODERATE (~$1 to $5 million)  3 = SEVERE (~>$5 to $24 million) 4 = EXTREME (~$25 million or more) When possible, a rough estimate was made of the dollar amount of damage based upon the description provided, in order to choose the damage category. In many cases, only a single  descriptive term was available. These terms were converted to the damage categories based upon the author’s apparent use of the term elsewhere. In the absence of other information,  LIMITED is considered synonymous with slight, minor, and light, SEVERE as synonymous with major, extensive, and heavy, and EXTREME as synonymous with catastrophic.
* [INTEGER]   `houses_destroyed`
  - Number of Houses Destroyed. Whenever possible, number of houses destroyed by the earthquake are listed; it may also include houses destroyed caused by a secondary effect such as the tsunami, volcanic eruption, or landslide that was triggered by the earthquake.
* [INTEGER]   `houses_destroyed_description`
  - Description of Houses Destroyed by the Earthquake. For those earthquakes not offering an exact number of houses destroyed, the following four-level scale was used to classify the destruction and was listed in the Houses_amount_order column.  If the actual number of houses destroyed was listed, a descriptor was also added for search purposes.   0 = None 1 = Few (~1 to 50 houses)  2 = Some (~51 to 100 houses)  3 = Many (~101 to 1000 houses) 4 = Very Many (~1001 or more houses)
* [INTEGER]   `houses_damaged`
  - Number of Houses Damaged. Whenever possible, number of houses damaged by the earthquake are listed; it may also include houses damaged caused by a secondary effect such as the tsunami, volcanic eruption, or landslide that was triggered by the earthquake.
* [INTEGER]   `houses_damaged_description`
  - Description of Houses Damaged by the Earthquake. For those earthquakes not offering an exact number of houses damaged, the following four-level scale was used to classify the damage and was listed in the Houses_damaged_amount_order column.  If the actual number of houses destroyed was listed, a descriptor was also added for search purposes.   0 = None 1 = Few (~1 to 50 houses)  2 = Some (~51 to 100 houses)  3 = Many (~101 to 1000 houses) 4 = Very Many (~1001 or more houses)
* [INTEGER]   `total_deaths`
  - Number of deaths from the earthquake and secondary effects such as the tsunami, volcanic eruption or landslide.
* [INTEGER]   `total_deaths_description`
  - Description of Deaths from the earthquake and the secondary effects such as the tsunami, volcanic eruption or landslide. Valid values: 0 to 4. When a description was found in the historical literature instead of an actual number of deaths, this value was coded and listed in the Deaths_amount_order_total column. If the actual number of deaths was listed, a descriptor was also added for search purposes according to the following definition. 0 = None 1 = Few (~1 to 50 deaths)  2 = Some (~51 to 100 deaths)  3 = Many (~101 to 1000 deaths) 4 = Very Many (~1001 or more deaths)
* [INTEGER]   `total_missing`
  - Number of missing from the earthquake and secondary effects such as the tsunami, volcanic eruption or landslide.
* [INTEGER]   `total_missing_description`
  - Description of Deaths from the earthquake and secondary effects such as the tsunami, volcanic eruption or landslide. Valid values: 0 to 4. When a description was found in the historical literature instead of an actual number of missing, this value was coded and listed in the Missing_amount_order_total column. If the actual number of missing was listed, a descriptor was also added for search purposes according to the following definition. 0 = None 1 = Few (~1 to 50 missing)  2 = Some (~51 to 100 missing)  3 = Many (~101 to 1000 missing) 4 = Very Many (~1001 or more missing)
* [INTEGER]   `total_injuries`
  - Number of injuries from the earthquake and secondary effects such as the tsunami, volcanic eruption or landslide.
* [INTEGER]   `total_injuries_description`
  - Description of injuries from the earthquake and secondary effects such as the tsunami, volcanic eruption or landslide. Valid values: 0 to 4. When a description was found in the historical literature instead of an actual number of injuries, this value was coded and listed in the Injuries_amount_order_total column. If the actual number of injuries was listed, a descriptor was also added for search purposes according to the following definition. 0 = None 1 = Few (~1 to 50 injuries)  2 = Some (~51 to 100 injuries)  3 = Many (~101 to 1000 injuries) 4 = Very Many (~1001 or more injuries)
* [FLOAT]     `total_damage_millions_dollars`
  - Damage in Millions of Dollars from the earthquake and secondary effects such as the tsunami, volcanic eruption or landslide. The value in the Damage column should be multipled by 1,000,000 to obtain the actual dollar amount in U.S. dollars. The dollar value listed is the value at the time of the event.
* [INTEGER]   `total_damage_description`
  - For those events not offering a monetary evaluation of damage, the following five-level scale was used to classify damage and was listed in the Damage column.  If the actual dollar amount of damage was listed, a descriptor was also added for search purposes. 0 = NONE 1 = LIMITED (roughly corresponding to less than $1 million) 2 = MODERATE (~$1 to $5 million)  3 = SEVERE (~>$5 to $24 million) 4 = EXTREME (~$25 million or more) When possible, a rough estimate was made of the dollar amount of damage based upon the description provided, in order to choose the damage category. In many cases, only a single descriptive term was available. These terms were converted to the damage categories based upon the author’s apparent use of the term elsewhere. In the absence of other information, LIMITED is considered synonymous with slight, minor, and light, SEVERE as synonymous with major, extensive, and heavy, and EXTREME as synonymous with catastrophic.
* [INTEGER]   `total_houses_destroyed`
  - Number of Houses Destroyed by the earthquake and secondary effects such as the tsunami, volcanic eruption or landslide.
* [INTEGER]   `total_houses_destroyed_description`
  - Description of Houses Destroyed by the earthquake and secondary effects such as the tsunami, volcanic eruption or landslide. For those earthquakes not offering an exact number of houses destroyed, the following four-level scale was used to classify the destruction and was listed in the Houses_amount_order_total column.  If the actual number of houses destroyed was listed, a descriptor was also added for search purposes.   0 = None 1 = Few (~1 to 50 houses)  2 = Some (~51 to 100 houses)  3 = Many (~101 to 1000 houses) 4 = Very Many (~1001 or more houses)
* [INTEGER]   `total_houses_damaged`
  - Number of Houses Damaged by the earthquake and secondary effects such as the tsunami, volcanic eruption or landslide.
* [INTEGER]   `total_houses_damaged_description`
  - Description of Houses Damaged by the earthquake and secondary effects such as the tsunami, volcanic eruption or landslide. For those earthquakes not offering an exact number of houses damaged, the following four-level scale was used to classify the damage and was listed in the Houses_dam_amount_order_total column.  If the actual number of houses destroyed was listed, a descriptor was also added for search purposes.   0 = None 1 = Few (~1 to 50 houses)  2 = Some (~51 to 100 houses)  3 = Many (~101 to 1000 houses) 4 = Very Many (~1001 or more houses)

-------------------------------------------------------------------------------
*Do not make edits above this line.*
