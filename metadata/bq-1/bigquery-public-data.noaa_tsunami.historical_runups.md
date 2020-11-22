# `noaa_tsunami.historical_runups`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - The unique numeric identifier of the record.
* [INTEGER]   `tsevent_id`
  - The unique numeric identifier of the tsunami source event record that links the runup with the event.
* [INTEGER]   `year`
  - Valid values: -2000 to Present Format +/-yyyy (-is B.C, +is A.D.)  The Date and Time are given in Universal Coordinated Time (also known as Greenwich Mean Time). The local date may be one day different.
* [INTEGER]   `month`
  - Valid values: 1-12 The Date and Time are given in Universal Coordinated Time (also known as Greenwich Mean Time). The local date may be one day different.
* [INTEGER]   `day`
  - Valid values: 1-31 (where months apply) The Date and Time are given in Universal Coordinated Time (also known as Greenwich Mean Time). The local date may be one day different.
* [DATETIME]  `timestamp`
  - Timestamp in UTC.
* [STRING]    `doubtful`
  - A "?" in the Doubtful column indicates a doubtful runup entry.  An "M" indicates the waves likely had a meteorologic source, and thus were not true tsunami waves.
* [STRING]    `country`
  - The country where the tsunami effects were observed.
* [STRING]    `state`
  - The State, Province or Prefecture where the tsunami effects were observed.
* [STRING]    `location_name`
  - The location (city, state or island) where the tsunami effects were observed.
* [FLOAT]     `latitude`
  - Valid values: -90 to +90 Latitude: 0 to 90 (Northern Hemisphere) -90 to 0 (Southern Hemisphere)  The latitude and longitude of the location (city, state or island) where the tsunami effects occurred.
* [FLOAT]     `longitude`
  - Valid values: -180 to +180 Longitude: 0 to 180 (Eastern Hemisphere) -180 to 0 (Western Hemisphere)  The latitude and longitude of the location (city, state or island) where the tsunami effects occurred.
* [INTEGER]   `region_code`
  - Regional boundaries are based on frequency of occurrence of tsunamigenic events, geophysical relations, risk in distant areas and political justification. 77 =	West Coast of Africa 78 =	Central Africa 73 =	Northeast Atlantic Ocean 72 =	Northwest Atlantic Ocean 70 =	Southeast Atlantic Ocean 71 =	Southwest Atlantic Ocean 75 =	E. Coast USA and Canada, St Pierre and Miquelon 76 =	Gulf of Mexico 74 =	Caribbean Sea and Bermuda 40 =	Black Sea and Caspian Sea 50 =	Mediterranean Sea 30 =	Red Sea and Persian Gulf 60 =	Indian Ocean (including west coast of Australia) 87 =	Alaska (including Aleutian Islands) 84 =	China, North and South Korea, Philippines, Taiwan 81 =	E Coast Australia, New Zealand, South Pacific Is. 80 =	Hawaii, Johnston Atoll, Midway I 83 =	E. Indonesia (Pacific Ocean) and Malaysia 82 =	New Caledonia, New Guinea, Solomon Is., Vanuatu 86 =	Kamchatka and Kuril Islands 85 =	Japan 88 =	West Coast of North and Central America 89 =	West Coast of South America
* [INTEGER]   `distance_from_source`
  - The distance from the tsunami event source to the runup location.
* [INTEGER]   `arr_day`
* [INTEGER]   `arr_hour`
* [INTEGER]   `arr_min`
* [INTEGER]   `travel_time_hours`
* [INTEGER]   `travel_time_minutes`
* [FLOAT]     `water_ht`
  - The maximum water height above sea level in meters. See image and text below for more information. If the type of measurement is:  Type 1: Water height - Eyewitness observation - the maximum elevation the wave. Type 2: Tide Gauge - half of the maximum height (minus the normal tide)of a tsunami wave recorded at the coast by a tide gauge. Type 3: Deep Ocean Gauge - half of the maximum height (minus the normal tide) of a tsunami wave recorded in the open ocean by a seafloor bottom pressure recording system. Type 4: Water height (Post-tsunami survey measurement)  Type 5: Runup Height (Post-tsunami survey measurement)  Type 8: Runup Height in Harbor (Post-tsunami survey measurement)  Type 10: Flow Depth (Post-tsunami survey measurement) depth of the water. Type 9: Splash mark (Post-tsunami survey measurement) Type 6: Atmospheric Wave  Type 7: Seiche
* [FLOAT]     `horizontal_inundation`
  - The maximum horizontal distance of inland flooding (in meters)
* [INTEGER]   `type_measurement_id`
  - Valid values: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10  See text below for more information. 1 = Eyewitness measurement 5 = Runup Height, Post-tsunami survey measurement 4 = Water height, Post-tsunami survey measurement 8 = Water height in harbor, Post-tsunami survey measurement 10 = Flow Depth, Post-tsunami survey measurement 9 = Splash mark, Post-tsunami survey measurement 2 = Tide-gauge measurement 3 = Deep ocean gauge 6 = Atmospheric Wave 7 = Seiche
* [FLOAT]     `period`
  - The period is in minutes and, when available, is the period of the first cycle.
* [STRING]    `first_motion`
  - The first motion of the wave whether rise or fall.  R = Rise F = Fall
* [INTEGER]   `deaths`
  - Deaths from the tsunami at the specific runup location.
* [INTEGER]   `deaths_description`
  - Valid values: 0 to 4 When a description was found in the historical literature instead of an actual number of deaths, this value was coded and listed in the Deaths De column. If the actual number of deaths was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 deaths) 2 = Some (~51 to 100 deaths) 3 = Many (~101 to 1000 deaths) 4 = Very Many (~1001 or more deaths)
* [INTEGER]   `injuries`
  - Whenever possible, numbers of injuries from the tsunami at the specific runup location are listed; may also include injuries from the earthquake that triggered the tsunami.
* [INTEGER]   `injuries_description`
  - Valid values: 0 to 4 When a description was found in the historical literature instead of an actual number of injuries, this value was coded and listed in the Injuries De column. If the actual number of injuries was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 injuries) 2 = Some(~51 to 100 injuries) 3 = Many (~101 to 1000 injuries) 4 = Very Many (~1001 or more injuries)
* [FLOAT]     `damage_millions_dollars`
  - The value in the Damage column should be multipled by 1,000,000 to obtain the actual dollar amount.  When a dollar amount for damage was found in the literature, it was listed in the Damage column in millions of U.S. dollars. The dollar value listed is the value at the time of the event. To convert the damage to current dollar values today, please use the Consumer Price Index Calculator. Monetary conversion tables for the time of the event were used to convert foreign currency to U.S. dollars.
* [INTEGER]   `damage_description`
  - For those events not offering a monetary evaluation of damage, the following five-level scale was used to classify damage (1990 dollars) and was listed in the Damage De column. If the actual dollar amount of damage was listed, a descriptor was also added for search purposes.  0 = NONE 1 = LIMITED (roughly corresponding to less than $1 million) 2 = MODERATE (~$1 to $5 million) 3 = SEVERE (~>$5 to $24 million) 4 = EXTREME (~$25 million or more)
* [INTEGER]   `houses_damaged`
  - Valid values: 0 to Whenever possible, number of houses damaged by the tsunami at the specific runup location are listed; may also include houses damaged by the earthquake that triggered the tsunami.
* [INTEGER]   `houses_damaged_description`
  - Valid values: 0 to 4 For those events not offering an exact number of houses damaged, the following four-level scale was used to classify the damage and was listed in the Houses Damaged De column. If the actual number of houses damaged was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 houses) 2 = Some (~51 to 100 houses) 3 = Many (~101 to 1000 houses) 4 = Very Many (~1001 or more houses)
* [INTEGER]   `houses_destroyed`
  - Whenever possible, number of houses destroyed by the tsunami at the specific runup location are listed; may also include houses destroyed by the earthquake that triggered the tsunami.
* [INTEGER]   `houses_destroyed_description`
  - Valid values: 0 to 4 For those events not offering an exact number of houses destroyed, the following four-level scale was used to classify the destruction and was listed in the Houses Destroyed De column. If the actual number of houses destroyed was listed, a descriptor was also added for search purposes.  0 = None 1 = Few (~1 to 50 houses) 2 = Some (~51 to 100 houses) 3 = Many (~101 to 1000 houses) 4 = Very Many (~1001 or more houses)

-------------------------------------------------------------------------------
*Do not make edits above this line.*
