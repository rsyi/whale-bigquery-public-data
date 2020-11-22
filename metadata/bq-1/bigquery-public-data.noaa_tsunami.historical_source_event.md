# `noaa_tsunami.historical_source_event`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - The unique numeric identifier of the record.
* [INTEGER]   `year`
  - Valid values: -2000 to Present Format +/-yyyy (-is B.C, +is A.D.)  The Date and Time are given in Universal Coordinated Time (also known as Greenwich Mean Time). The local date may be one day different.  Please see the Caveat and Uncertainties in the Significant Earthquake and Tsunami Databases in the Significant Earthquake Database Introduction for more information on the completeness and accuracy of this database.
* [INTEGER]   `month`
  - Valid values: 1-12 The Date and Time are given in Universal Coordinated Time (also known as Greenwich Mean Time). The local date may be one day different.
* [INTEGER]   `day`
  - Valid values: 1-31 (where months apply) The Date and Time are given in Universal Coordinated Time (also known as Greenwich Mean Time). The local date may be one day different.
* [DATETIME]  `timestamp`
  - Timestamp in UTC.
* [INTEGER]   `event_validity`
  - Valid values: -1 to 4 Validity of the actual tsunami occurrence is indicated by a numerical rating of the reports of that event:  4 = definite tsunami 3 = probable tsunami 2 = questionable tsunami 1 = very doubtful tsunami 0 = event that only caused a seiche or disturbance in an inland river -1 = erroneous entry
* [INTEGER]   `cause_code`
  - Valid values: 0 to 11 The source of the tsunami:  0 = Unknown 1 = Earthquake 2 = Questionable Earthquake 3 = Earthquake and Landslide 4 = Volcano and Earthquake 5 = Volcano, Earthquake, and Landslide 6 = Volcano 7 = Volcano and Landslide 8 = Landslide 9 = Meteorological 10 = Explosion 11 = Astronomical Tide
* [INTEGER]   `focal_depth`
  - Valid values: 0 to 700 km The depth of the earthquake is given in kilometers.
* [FLOAT]     `primary_magnitude`
  - Valid values: 0.0 to 9.9 The value in this column contains the primary earthquake magnitude. Magnitude measures the energy released at the source of the earthquake. Magnitude is determined from measurements on seismographs. For pre-instrumental events, the magnitudes are derived from intensities. There are several different scales for measuring earthquake magnitudes. The primary magnitude is chosen from the available magnitude scales in this order:  Mw Magnitude  Ms Magnitude  Mb Magnitude  Ml Magnitude  Mfa Magnitude  Unknown Magnitude
* [STRING]    `country`
  - The Country where the tsunami source occurred (For example enter: Japan or Russia)
* [STRING]    `state`
  - The two-letter State or Province abbreviation where the Earthquake occurred.
* [STRING]    `location_name`
  - The Country, State, Province or Island where the tsunami source occurred (For example enter: Japan or Honshu) This is only an approximate geographic location. Events prior to 1900 were not instrumentally located, therefore, the location given is based on the latitude and longitude of the city where the maximum effects occurred. If there are different spellings of a city name the additional names are in parentheses.
* [FLOAT]     `latitude`
  - Valid values: -90 to +90 Latitude: 0 to 90 (Northern Hemisphere) -90 to 0 (Southern Hemisphere)  Events prior to 1900 were not instrumentally located, therefore, the location given is based on the latitude and longitude of the city where the maximum effects occurred.  The event coordinates of over 800 tsunami sources in this database are not known and the latitude and longitude are listed as null. Therefore, to retrieve all the events from a particular country or state, leave the event coordinates search parameter blank and enter the country or select the region name.
* [FLOAT]     `longitude`
  - Valid values: -180 to +180 Longitude: 0 to 180 (Eastern Hemisphere) -180 to 0 (Western Hemisphere)  Events prior to 1900 were not instrumentally located, therefore, the location given is based on the latitude and longitude of the city where the maximum effects occurred.  The event coordinates of over 800 tsunami sources in this database are not known and the latitude and longitude are listed as null. Therefore, to retrieve all the events from a particular country or state, leave the event coordinates search parameter blank and enter the country or select the region name.
* [INTEGER]   `region_code`
  - Regional boundaries are based on frequency of occurrence of tsunamigenic events, geophysical relations, risk in distant areas and political justification. 77 =	West Coast of Africa 78 =	Central Africa 73 =	Northeast Atlantic Ocean 72 =	Northwest Atlantic Ocean 70 =	Southeast Atlantic Ocean 71 =	Southwest Atlantic Ocean 75 =	E. Coast USA and Canada, St Pierre and Miquelon 76 =	Gulf of Mexico 74 =	Caribbean Sea 40 =	Black Sea and Caspian Sea 50 =	Mediterranean Sea 30 =	Red Sea and Persian Gulf 60 =	Indian Ocean (including west coast of Australia) 87 =	Alaska (including Aleutian Islands) 84 =	China, North and South Korea, Philippines, Taiwan 81 =	E. Coast Australia, New Zealand, South Pacific Is. 80 =	Hawaii, Johnston Atoll, Midway I 83 =	E. Indonesia (Pacific Ocean) and Malaysia 82 =	New Caledonia, New Guinea, Solomon Is., Vanuatu 86 =	Kamchatka and Kuril Islands 85 =	Japan 88 =	West Coast of North and Central America 89 =	West Coast of South America
* [FLOAT]     `maximum_water_height`
  - The maximum water height above sea level in meters for this event. If the type of measurement of the runup was a:  Tide Gauge - half of the maximum height (minus the normal tide)of a tsunami wave recorded at the coast by a tide gauge. Runup Height - the maximum elevation the wave reaches at the maximum inundation.
* [FLOAT]     `abe`
  - Valid values: -5 to 10 Abe defined two different tsunami magnitude amplitudes. His first tsunami magnitude (1979) is:  Mt = logH + B  where H is the maximum single crest or trough amplitude of the tsunami waves (in meters) and B a constant. The second definition (1981) is:  Mt = logH + alogR + D  where R is the distance in km from the earthquake epicenter to the tide station along the shortest oceanic path, and a and D are constants.
* [FLOAT]     `iida`
  - Valid values: -5 to 10 Tsunami magnitude (M) is defined by Iida and others (1967) as  M = log2h, where "h" is the maximum runup height of the wave.
* [FLOAT]     `soloviev`
  - Valid values: -5 to 10 Tsunami intensity is defined by Soloviev and Go (1974) as  I = log2(21/2 * h), where "h" is the maximum runup height of the wave.
* [INTEGER]   `warning_status`
  - Valid values: -1 to 4 Warning Status of the Tsunami:  -1=Status unknown 0=no warning issued 1=PTW - Pacific-wide Tsunami Warning issued by PTWC 2=RTW - Regional Tsunami Warning issued by PTWC for areas having no TWS 3=LTW - Local Tsunami Warning issued by regional or national TWC 4=TIB - Tsunami Information or Attention Bulletin issued by any agency
* [INTEGER]   `deaths`
  - If an actual number of deaths due to the tsunami is known, enter a number in this search field. If only a description is available such as "few", "some", or "many", the database can be searched using the search field:Death Description
* [INTEGER]   `deaths_description`
  - Valid values: 0 to 4 When a description was found in the historical literature instead of an actual number of deaths, this value was coded and listed in the Deaths De column. If the actual number of deaths was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 deaths) 2 = Some (~51 to 100 deaths) 3 = Many (~101 to 1000 deaths) 4 = Very Many (~1001 or more deaths)
* [INTEGER]   `missing`
  - Whenever possible, numbers of Missing from the tsunami are listed.
* [INTEGER]   `missing_description`
  - Valid values: 0 to 4 When a description was found in the historical literature instead of an actual number of missing, this value was coded and listed in the Missing De column. If the actual number of missing was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 missing) 2 = Some(~51 to 100 missing) 3 = Many (~101 to 1000 missing) 4 = Very Many (~1001 or more missing)
* [INTEGER]   `injuries`
  - Whenever possible, numbers of injuries from the tsunami are listed.
* [INTEGER]   `injuries_description`
  - Valid values: 0 to 4 When a description was found in the historical literature instead of an actual number of injuries, this value was coded and listed in the Injuries De column. If the actual number of injuries was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 injuries) 2 = Some(~51 to 100 injuries) 3 = Many (~101 to 1000 injuries) 4 = Very Many (~1001 or more injuries)
* [FLOAT]     `damage_millions_dollars`
  - The value in the Damage column should be multiplied by 1,000,000 to obtain the actual dollar amount.  If an actual number of dollars in damage due to the tsunami is known, enter a number in this search field. If only a description is available such as "limited", "moderate", or "severe", the database can be searched using the search field:Damage Description  When a dollar amount for damage was found in the literature, it was listed in the Damage column in millions of U.S. dollars. The dollar value listed is the value at the time of the event. To convert the damage to current dollar values, please use the Consumer Price Index Calculator. Monetary conversion tables for the time of the event were used to convert foreign currency to U.S. dollars.
* [INTEGER]   `damage_description`
  - Valid values: 0 to 4 For those events not offering a monetary evaluation of damage, the following five-level scale was used to classify damage (1990 dollars) and was listed in the Damage De column. If the actual dollar amount of damage was listed, a descriptor was also added for search purposes.  0 = NONE 1 = LIMITED (roughly corresponding to less than $1 million) 2 = MODERATE (~$1 to $5 million) 3 = SEVERE (~>$5 to $24 million) 4 = EXTREME (~$25 million or more)
* [INTEGER]   `houses_destroyed`
  - Whenever possible, number of houses destroyed by the tsunami are listed.
* [INTEGER]   `houses_destroyed_description`
  - Valid values: 0 to 4 For those events not offering an exact number of houses destroyed, the following four-level scale was used to classify the destruction and was listed in the Houses Destroyed De column. If the actual number of houses destroyed was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 houses) 2 = Some (~51 to 100 houses) 3 = Many (~101 to 1000 houses) 4 = Very Many (~1001 or more houses)
* [INTEGER]   `houses_damaged`
  - Whenever possible, number of houses damaged by the tsunami are listed.
* [INTEGER]   `houses_damaged_description`
  - Valid values: 0 to 4 For those events not offering an exact number of houses damaged, the following four-level scale was used to classify the damage and was listed in the Houses Damaged De column. If the actual number of houses damaged was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 houses) 2 = Some (~51 to 100 houses) 3 = Many (~101 to 1000 houses) 4 = Very Many (~1001 or more houses)
* [INTEGER]   `total_deaths`
  - Whenever possible, numbers of deaths from the tsunami and source event are listed.
* [INTEGER]   `total_deaths_description`
  - Valid values: 0 to 4 When a description was found in the historical literature instead of an actual number of deaths, this value was coded and listed in the Deaths De column. If the actual number of deaths was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 deaths) 2 = Some (~51 to 100 deaths) 3 = Many (~101 to 1000 deaths) 4 = Very Many (~1001 or more deaths)
* [INTEGER]   `total_missing`
  - Whenever possible, numbers of missing from the tsunami and source event are listed.
* [INTEGER]   `total_missing_description`
  - Valid values: 0 to 4 When a description was found in the historical literature instead of an actual number of missing, this value was coded and listed in the Missing De column. If the actual number of missing was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 missing) 2 = Some(~51 to 100 missing) 3 = Many (~101 to 1000 missing) 4 = Very Many (~1001 or more missing)
* [INTEGER]   `total_injuries`
  - Whenever possible, numbers of injuries from the tsunami and source event are listed.
* [INTEGER]   `total_injuries_description`
  - Valid values: 0 to 4 When a description was found in the historical literature instead of an actual number of injuries, this value was coded and listed in the Injuries De column. If the actual number of injuries was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 injuries) 2 = Some(~51 to 100 injuries) 3 = Many (~101 to 1000 injuries)) 4 = Very Many (~1001 or more injuries)
* [FLOAT]     `total_damage_in_millions_dollars`
  - The value in the Damage column should be multipled by 1,000,000 to obtain the actual dollar amount.  When a dollar amount for damage was found in the literature, it was listed in the Damage column in millions of U.S. dollars. The dollar value listed is the value at the time of the event. To convert the damage to current dollar values, please use the Consumer Price Index Calculator. Monetary conversion tables for the time of the event were used to convert foreign currency to U.S. dollars.
* [INTEGER]   `total_damage_description`
  - Valid values: 0 to 4 For those events not offering a monetary evaluation of damage, the following five-level scale was used to classify damage (1990 dollars) and was listed in the Damage De column. If the actual dollar amount of damage was listed, a descriptor was also added for search purposes.  0 = NONE 1 = LIMITED (roughly corresponding to less than $1 million) 2 = MODERATE (~$1 to $5 million) 3 = SEVERE (~$5 to $25 million) 4 = EXTREME (~$25 million or more)
* [INTEGER]   `total_houses_destroyed`
  - Whenever possible, number of houses destroyed by the tsunami and the source event are listed.
* [INTEGER]   `total_houses_destroyed_description`
  - Valid values: 0 to 4 For those events not offering an exact number of houses destroyed, the following four-level scale was used to classify the destruction and was listed in the Houses Destroyed De column. If the actual number of houses destroyed was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 houses) 2 = Some (~51 to 100 houses) 3 = Many (~101 to 1000 houses) 4 = Very Many (~1001 or more houses)
* [INTEGER]   `total_houses_damaged`
  - Whenever possible, number of houses damaged by the tsunami and the source event are listed.
* [INTEGER]   `total_houses_damaged_description`
  - Valid values: 0 to 4 For those events not offering an exact number of houses damaged, the following four-level scale was used to classify the damage and was listed in the Houses Damaged De column. If the actual number of houses damaged was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 houses) 2 = Some (~51 to 100 houses) 3 = Many (~101 to 1000 houses) 4 = Very Many (~1001 or more houses)

-------------------------------------------------------------------------------
*Do not make edits above this line.*
