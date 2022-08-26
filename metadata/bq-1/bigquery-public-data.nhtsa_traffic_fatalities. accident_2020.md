# `nhtsa_traffic_fatalities. accident_2020`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `state_number`
  - This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). For more info on the codes, please look at <C1/V1/D1/PC1/P1/NM1 State Number> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `state_name`
  - This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC).
* [INTEGER]   `consecutive_number`
  - This data element is the unique case number assigned to each crash. It appears on each data file and is used to merge information from the data files together. xxxxxx Two Characters for State Code followed by Four Characters for Case Number
* [INTEGER]   `number_of_vehicle_forms_submitted_all`
  - number_of_vehicle_forms_submitted_all
* [INTEGER]   `number_of_motor_vehicles_in_transport_mvit`
  - This data element is a count of the number of vehicles in-transport involved in the crash. Legally parked vehicles are not included. 001-999 Number of Vehicle Forms
* [INTEGER]   `number_of_parked_working_vehicles`
  - This data element is a count of the number of parked and working vehicles involved in the crash. 0-999 Number of Parked/Working Vehicles in the Crash
* [INTEGER]   `number_of_forms_submitted_for_persons_not_in_motor_vehicles`
  - This data element is the number of Person Forms (Not a Motor Vehicle Occupant) that are applicable to this case (i.e., non-occupants). 00-99 Number of Persons Not in Motor Vehicles
* [INTEGER]   `number_of_forms_submitted_for_persons_in_motor_vehicles`
  - This data element is a count of the number of Person Level (Motor Vehicle Occupant) Forms that are applicable to this case (i.e., occupants). 000-999 Number of Person Forms
* [INTEGER]   `number_of_persons_in_motor_vehicles_in_transport_mvit`
  - This data element is a count of the number of motorists in the crash. A motorist is a driver, passenger or unknown occupant type of a motor vehicle in-transport. 0-999 Number of Persons in Motor Vehicles In-Transport
* [INTEGER]   `number_of_persons_not_in_motor_vehicles_in_transport_mvit`
  - This data element is a count of the number of non-motorists in the crash. A non-motorist is defined as a pedestrian, a cyclist, an occupant of a motor vehicle not intransport, a person riding a horse, an occupant of an animal drawn conveyance, person associated with non-motorist conveyance (e.g., baby carriage, skate board, wheelchair), or an other non-motorist (e.g., person outside a trafficway, person in a house). 0-98 Number of Persons Not in Motor Vehicles in Transport
* [INTEGER]   `county`
  - This data element records the location of the unstabilized event with regard to the County. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). 000 Not Applicable 001-996 Use GSA Geographical Codes 997 Other 998 Not Reported 999 Unknown
* [STRING]    `county_name`
  - This data element records the location of the unstabilized event with regard to the County. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). 000 Not Applicable 001-996 Use GSA Geographical Codes 997 Other 998 Not Reported 999 Unknown
* [INTEGER]   `city`
  - This data element records the location of the unstabilized event with regard to the City. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). 0000 Not Applicable 0001-9996 GSA Geographical Codes 9997 Other 9898 Not Reported 9999 Unknown
* [STRING]    `city_name`
  - This data element records the location of the unstabilized event with regard to the City. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). 0000 Not Applicable 0001-9996 GSA Geographical Codes 9997 Other 9898 Not Reported 9999 Unknown
* [INTEGER]   `day_of_crash`
  - This data element records the day of the month on which the crash occurred. 01-31 Day of the Month of the Crash -- Unknown
* [STRING]    `day_name`
  - This data element records the day of the month on which the crash occurred. 01-31 Day of the Month of the Crash -- Unknown
* [INTEGER]   `month_of_crash`
  - This data element records the month in which the crash occurred. For more info on the codes, please look at <C8A Month of Crash> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `month_of_crash_name`
  - This data element records the month in which the crash occurred. For more info on the codes, please look at <C8A Month of Crash> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `year_of_crash`
  - This data element records the year in which the crash occurred. xxxx Year of the Crash
* [INTEGER]   `day_of_week`
  - This data element records the day of the week on which the crash occurred. 1 Sunday 2 Monday 3 Tuesday 4 Wednesday 5 Thursday 6 Friday 7 Saturday -- Unknown
* [STRING]    `day_of_week_name`
  - This data element records the day of the week on which the crash occurred. 1 Sunday 2 Monday 3 Tuesday 4 Wednesday 5 Thursday 6 Friday 7 Saturday -- Unknown
* [INTEGER]   `hour_of_crash`
  - This data element records the hour at which the crash occurred. 00-23 Hour -- Not Applicable or Not Notified 99 Unknown
* [STRING]    `hour_of_crash_name`
  - This data element records the hour at which the crash occurred. 00-23 Hour -- Not Applicable or Not Notified 99 Unknown
* [INTEGER]   `minute_of_crash`
  - This data element records the minutes after the hour at which the crash occurred. 00-59 Minute -- Not Applicable or Not Notified 99 Unknown
* [STRING]    `minute_of_crash_name`
  - This data element records the minutes after the hour at which the crash occurred. 00-59 Minute -- Not Applicable or Not Notified 99 Unknown
* [INTEGER]   `national_highway_system`
  - This data element identifies whether this crash occurred on a trafficway that is part of the National Highway System. 0 This Section is Not on the National Highway System 1 This Section is on the National Highway System 9 Unknown
* [STRING]    `national_highway_system_name`
  - This data element identifies whether this crash occurred on a trafficway that is part of the National Highway System. 0 This Section is Not on the National Highway System 1 This Section is on the National Highway System 9 Unknown
* [INTEGER]   `route_signing`
  - This data element identifies the route signing of the trafficway on which the crash occurred. 1 Interstate 2 U.S. Highway 3 State Highway 4 County Road 5 Local Street – Township 6 Local Street – Municipality 7 Local Street – Frontage Road (Since 1994) 8 Other 9 Unknown
* [STRING]    `route_signing_name`
  - This data element identifies the route signing of the trafficway on which the crash occurred.
* [STRING]    `trafficway_identifier`
  - This data element records the trafficway on which the crash occurred. xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx Actual Posted Number, Assigned Number, or Common Name (30 characters) 999999999999999999999999999999 Unknown
* [STRING]    `trafficway_identifier_2`
  - This data element records the trafficway on which the crash occurred. xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx Actual Posted Number, Assigned Number, or Common Name (30 characters) 999999999999999999999999999999 Unknown
* [INTEGER]   `land_use`
  - 1 (Rural), 2 (Urban), 6 (Trafficway Not in State Inventory), 8 (Not Reported) and 9 (Unknown).
* [STRING]    `land_use_name`
  - 1 (Rural), 2 (Urban), 6 (Trafficway Not in State Inventory), 8 (Not Reported) and 9 (Unknown).
* [INTEGER]   `functional_system`
  - 01 (Interstate), 02 (Principal Arterial – Other Freeways and Expressways), 03 (Principal Arterial – Other), 04 (Minor Arterial), 05 (Major Collector), 06 (Minor Collector), 07 (Local), 96 (Trafficway Not in State Inventory), 98 (Not Reported), and 99 (Unknown).
* [STRING]    `functional_system_name`
  - 01 (Interstate), 02 (Principal Arterial – Other Freeways and Expressways), 03 (Principal Arterial – Other), 04 (Minor Arterial), 05 (Major Collector), 06 (Minor Collector), 07 (Local), 96 (Trafficway Not in State Inventory), 98 (Not Reported), and 99 (Unknown).
* [INTEGER]   `ownership`
  - For more info on the codes, please look at <C13 Ownership> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `ownership_name`
  - For more info on the codes, please look at <C13 Ownership> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `milepoint`
  - This data element records the milepoint nearest to the location where the crash occurred. 00000 None xxxxx Actual to Nearest Tenth Mile (Assume decimal, e.g., 12345 = 1234.5) 99998 Not Reported 99999 Unknown
* [STRING]    `milepoint_name`
  - This data element records the milepoint nearest to the location where the crash occurred. 00000 None xxxxx Actual to Nearest Tenth Mile (Assume decimal, e.g., 12345 = 1234.5) 99998 Not Reported 99999 Unknown
* [FLOAT]     `latitude`
  - This element identifies the location of the crash using Global Position coordinates. This is the position of latitude. DDDDDD (DD.DDDD – Decimal Degrees) DD.DDDD Actual Degrees 77.7777 Not Reported 88.8888 Not Available (If State Exempt) 99.9999 Unknown
* [STRING]    `latitude_name`
  - This element identifies the location of the crash using Global Position coordinates. This is the position of latitude. DDDDDD (DD.DDDD – Decimal Degrees) DD.DDDD Actual Degrees 77.7777 Not Reported 88.8888 Not Available (If State Exempt) 99.9999 Unknown
* [FLOAT]     `longitude`
  - This element identifies the location of the crash using Global Position coordinates. This is the position of longitude. DDDDDDD (DDD.DDDD – Decimal Degrees) DDD.DDDD Actual Degrees 777.7777 Not Reported 888.8888 Not Available (If State Exempt) 999.9999 Unknown
* [STRING]    `longitude_name`
  - This element identifies the location of the crash using Global Position coordinates. This is the position of longitude. DDDDDDD (DDD.DDDD – Decimal Degrees) DDD.DDDD Actual Degrees 777.7777 Not Reported 888.8888 Not Available (If State Exempt) 999.9999 Unknown
* [INTEGER]   `special_jurisdiction`
  - This data element identifies if the location on the trafficway where the crash occurred qualifies as a Special Jurisdiction even though it may be patrolled by state, county or local police (e.g., all State highways running through Indian reservations are under the jurisdiction of the Indian reservation). 0 No Special Jurisdiction (Includes National Forests Since 2008) 1 National Park Service 2 Military 3 Indian Reservation 4 College/University Campus 5 Other Federal Properties (Since 1977) 8 Other (Since 1976) 9 Unknown
* [STRING]    `special_jurisdiction_name`
  - This data element identifies if the location on the trafficway where the crash occurred qualifies as a Special Jurisdiction even though it may be patrolled by state, county or local police (e.g., all State highways running through Indian reservations are under the jurisdiction of the Indian reservation).
* [INTEGER]   `first_harmful_event`
  - This data element describes the first injury or damage producing event of the crash. For more info on the codes, please look at <C19 First Harmful Event> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `first_harmful_event_name`
  - This data element describes the first injury or damage producing event of the crash.
* [INTEGER]   `manner_of_collision`
  - This data element describes the orientation of two motor vehicles in-transport when they are involved in the “First Harmful Event” of a collision crash. If the “First Harmful Event” is not a collision between two motor vehicles in-transport it is classified as such. For more info on the codes, please look at <C20 Manner of Collision> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `manner_of_collision_name`
  - This data element describes the orientation of two motor vehicles in-transport when they are involved in the “First Harmful Event” of a collision crash. If the “First Harmful Event” is not a collision between two motor vehicles in-transport it is classified as such.
* [INTEGER]   `relation_to_junction_within_interchange_area`
  - This data element identifies the crash's location with respect to presence in an interchange area. The coding of this data element is done in two sub-fields (see also C20B) and is based on the location of the “First Harmful Event” of the crash. 0 No 1 Yes 8 Not Reported 9 Unknown
* [STRING]    `relation_to_junction_within_interchange_area_name`
  - This data element identifies the crash's location with respect to presence in an interchange area. The coding of this data element is done in two sub-fields (see also C20B) and is based on the location of the “First Harmful Event” of the crash. 0 No 1 Yes 8 Not Reported 9 Unknown
* [INTEGER]   `relation_to_junction_specific_location`
  - This data element identifies the crash's location with respect to presence in or proximity to components typically in junction or interchange areas. The coding of this data element is done in two sub-fields (see also C20A) and is based on the location of the “First Harmful Event” of the crash. For more info on the codes, please look at <C21B Relation to Junction- Specific Location> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `relation_to_junction_specific_location_name`
  - This data element identifies the crash's location with respect to presence in or proximity to components typically in junction or interchange areas. The coding of this data element is done in two sub-fields (see also C20A) and is based on the location of the “First Harmful Event” of the crash.
* [INTEGER]   `type_of_intersection`
  - This data element identifies and allows separation of various intersection types. 1 Not an Intersection 2 Four-Way Intersection 3 T-Intersection 4 Y-Intersection 5 Traffic Circle 6 Roundabout 7 Five-Point, or More 10 L-Intersection 98 Not Reported 99 Unknown
* [STRING]    `type_of_intersection_name`
  - This data element identifies and allows separation of various intersection types. 1 Not an Intersection 2 Four-Way Intersection 3 T-Intersection 4 Y-Intersection 5 Traffic Circle 6 Roundabout 7 Five-Point, or More 10 L-Intersection 98 Not Reported 99 Unknown
* [INTEGER]   `work_zone`
  - This data element identifies a motor vehicle traffic crash in which the first harmful event occurs within the boundaries of a work zone or on an approach to or exit from a work zone, resulting from an activity, behavior, or control related to the movement of the traffic units through the work zone. 0 None 1 Construction 2 Maintenance -- Construction or Maintenance 3 Utility 4 Work Zone, Type Unknown -- Not Reported
* [STRING]    `work_zone_name`
  - This data element identifies a motor vehicle traffic crash in which the first harmful event occurs within the boundaries of a work zone or on an approach to or exit from a work zone, resulting from an activity, behavior, or control related to the movement of the traffic units through the work zone. 0 None 1 Construction 2 Maintenance -- Construction or Maintenance 3 Utility 4 Work Zone, Type Unknown -- Not Reported
* [INTEGER]   `relation_to_trafficway`
  - This data element identifies the location of the crash as it relates to its position within or outside the trafficway based on the “First Harmful Event.” For more info on the codes, please look at <C23 Relation to Trafficway> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `relation_to_trafficway_name`
  - This data element identifies the location of the crash as it relates to its position within or outside the trafficway based on the “First Harmful Event.”
* [INTEGER]   `light_condition`
  - This data element records the type/level of light that existed at the time of the crash as indicated in the case material. For more info on the codes, please look at <C25 Light Condition> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `light_condition_name`
  - This data element records the type/level of light that existed at the time of the crash as indicated in the case material.
* [INTEGER]   `atmospheric_conditions_1`
  - This data element records the prevailing atmospheric conditions that existed at the time of the crash as indicated in the case material. For more info on the codes, please look at <C26 Atmospheric Conditions> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `atmospheric_conditions_1_name`
  - This data element records the prevailing atmospheric conditions that existed at the time of the crash as indicated in the case material.
* [INTEGER]   `atmospheric_conditions_2`
  - This data element records the prevailing atmospheric conditions that existed at the time of the crash as indicated in the case material. For more info on the codes, please look at <C26 Atmospheric Conditions> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `atmospheric_conditions_2_name`
  - This data element records the prevailing atmospheric conditions that existed at the time of the crash as indicated in the case material.
* [STRING]    `rail_grade_crossing_identifier`
  - This data element identifies if the crash occurred in or near a rail grade crossing. 0000000 Not Applicable xxxxxxA Six Digits Followed by One Alphabetic Valid F.R.A. Code 9999999 Unknown
* [STRING]    `rail_grade_crossing_identifier_name`
  - This data element identifies if the crash occurred in or near a rail grade crossing. 0000000 Not Applicable xxxxxxA Six Digits Followed by One Alphabetic Valid F.R.A. Code 9999999 Unknown
* [INTEGER]   `hour_of_notification`
  - This data element records the hour that emergency medical service was notified. 00-23 Hour -- Not Applicable or Not Notified (when NOT_MIN = 00) 88 Not Applicable or Not Notified 99 Unknown Hour 99 Unknown if Notified (when NOT_MIN = 98)
* [STRING]    `hour_of_notification_name`
  - This data element records the hour that emergency medical service was notified. 00-23 Hour -- Not Applicable or Not Notified (when NOT_MIN = 00) 88 Not Applicable or Not Notified 99 Unknown Hour 99 Unknown if Notified (when NOT_MIN = 98)
* [INTEGER]   `minute_of_notification`
  - This data element records the minutes after the hour that emergency medical service was notified. 00-59 Minute -- Not Applicable or Not Notified (when NOT_HOUR = 00) 88 Not Applicable or Not Notified 98 Unknown if Notified 99 Unknown Minutes
* [STRING]    `minute_of_notification_name`
  - This data element records the minutes after the hour that emergency medical service was notified. 00-59 Minute -- Not Applicable or Not Notified (when NOT_HOUR = 00) 88 Not Applicable or Not Notified 98 Unknown if Notified 99 Unknown Minutes
* [INTEGER]   `hour_of_arrival_at_scene`
  - This data element records the hour that emergency medical service arrived on the crash scene. 00-23 Hour -- Not Notified or Officially Cancelled (when ARR_MIN = 00) -- Not Notified (when ARR_MIN = 00) 88 Not Applicable or Not Notified 99 Unknown Hour 99 Officially Cancelled (when ARR_MIN = 97) 99 Unknown if Arrived (when ARR_MIN = 98)
* [STRING]    `hour_of_arrival_at_scene_name`
  - This data element records the hour that emergency medical service arrived on the crash scene. 00-23 Hour -- Not Notified or Officially Cancelled (when ARR_MIN = 00) -- Not Notified (when ARR_MIN = 00) 88 Not Applicable or Not Notified 99 Unknown Hour 99 Officially Cancelled (when ARR_MIN = 97) 99 Unknown if Arrived (when ARR_MIN = 98)
* [INTEGER]   `minute_of_arrival_at_scene`
  - This data element records the minutes after the hour that emergency medical service arrived on the crash scene. 00-59 Minute 00 -- Not Notified or Officially Cancelled (when ARR_HOUR = 00) -- Not Notified (when ARR_HOUR = 00) 88 Not Applicable or Not Notified 97 Officially Cancelled 98 Unknown if Arrived 99 Unknown Minutes
* [STRING]    `minute_of_arrival_at_scene_name`
  - This data element records the minutes after the hour that emergency medical service arrived on the crash scene. 00-59 Minute 00 -- Not Notified or Officially Cancelled (when ARR_HOUR = 00) -- Not Notified (when ARR_HOUR = 00) 88 Not Applicable or Not Notified 97 Officially Cancelled 98 Unknown if Arrived 99 Unknown Minutes
* [INTEGER]   `hour_of_ems_arrival_at_hospital`
  - This data element records the hour that emergency medical service arrived at the treatment facility to which it was transporting victims of the crash. 00-23 Hour -- Not Notified, Officially Cancelled or Not Transported (when HOSP_MIN = 00) -- Not Notified or Not Transported (when HOSP_MIN = 00) 88 Not Applicable or Not Notified 99 Unknown Hour 99 Officially Cancelled (when HOSP_MIN = 97) 99 Unknown if Transported (when HOSP_MIN = 98)
* [STRING]    `hour_of_ems_arrival_at_hospital_name`
  - This data element records the hour that emergency medical service arrived at the treatment facility to which it was transporting victims of the crash. 00-23 Hour -- Not Notified, Officially Cancelled or Not Transported (when HOSP_MIN = 00) -- Not Notified or Not Transported (when HOSP_MIN = 00) 88 Not Applicable or Not Notified 99 Unknown Hour 99 Officially Cancelled (when HOSP_MIN = 97) 99 Unknown if Transported (when HOSP_MIN = 98)
* [INTEGER]   `minute_of_ems_arrival_at_hospital`
  - This data element records the minutes after the hour that emergency medical service arrived at the treatment facility to which it was transporting victims of the crash. 00-59 Minute -- Not Notified, Officially Cancelled or Not Transported (when HOSP_HR = 00) -- Not Notified or Not Transported (when HOSP_HR = 00) 88 Not Applicable or Not Notified 96 Terminated Transport 97 Officially Cancelled 98 Unknown if Transported 99 Unknown Minutes
* [STRING]    `minute_of_ems_arrival_at_hospital_name`
  - This data element records the minutes after the hour that emergency medical service arrived at the treatment facility to which it was transporting victims of the crash. 00-59 Minute -- Not Notified, Officially Cancelled or Not Transported (when HOSP_HR = 00) -- Not Notified or Not Transported (when HOSP_HR = 00) 88 Not Applicable or Not Notified 96 Terminated Transport 97 Officially Cancelled 98 Unknown if Transported 99 Unknown Minutes
* [INTEGER]   `number_of_fatalities`
  - This data element records the number of fatally injured persons in the crash. 01-99 Number of Fatalities that Occurred in the Crash.
* [INTEGER]   `number_of_drunk_drivers`
  - This data element records the number of drunk drivers involved in the crash. 00-99 Number of Drunk Drivers Involved in the Fatal Crash.
* [TIMESTAMP] `timestamp_of_crash`
  - This data element records the date and time on which the crash occurred.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
