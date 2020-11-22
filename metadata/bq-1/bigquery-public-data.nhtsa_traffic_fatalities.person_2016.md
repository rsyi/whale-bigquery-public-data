# `nhtsa_traffic_fatalities.person_2016`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `state_number`
  - This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). For more info on the codes, please look at <C1/V1/D1/PC1/P1/NM1 State Number> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `consecutive_number`
  - This data element is the unique case number assigned to each crash. It appears on each data file and is used to merge information from the data files together. xxxxxx Two Characters for State Code followed by Four Characters for Case Number
* [INTEGER]   `number_of_motor_vehicles_in_transport_mvit`
  - This data element is a count of the number of vehicles in-transport involved in the crash. Legally parked vehicles are not included. 001-999 Number of Vehicle Forms
* [INTEGER]   `vehicle_number`
  - This data element is the consecutive number assigned to each vehicle in the case. This data element appears on each vehicle level data file and is used in conjunction with the ST_CASE data element to merge information from vehicle level data files. 000-999 Assigned Number of Motor Vehicle
* [INTEGER]   `person_number`
  - This data element is the consecutive number assigned to each person in the case (i.e., each occupant, pedestrian, or non-motorists involved in the crash). This data element appears on each person level data file and is used in conjunction with the ST_CASE data element (and sometimes the VEH_NO data element) to merge information from person level data files. 001-999 Assigned Person Number
* [INTEGER]   `number_of_motor_vehicle_striking_non_motorist`
  - This data element identifies the “Vehicle Number” (VEH_NO) of the in-transport vehicle that made contact with this non-motorist. 000 Occupant of a Motor Vehicle 001-998 Vehicle Number of Striking Vehicle 999 Unknown
* [INTEGER]   `county`
  - This data element records the location of the unstabilized event with regard to the County. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). 000 Not Applicable 001-996 Use GSA Geographical Codes 997 Other 998 Not Reported 999 Unknown
* [INTEGER]   `day_of_crash`
  - This data element records the day of the month on which the crash occurred. 01-31 Day of the Month of the Crash -- Unknown
* [INTEGER]   `month_of_crash`
  - This data element records the month in which the crash occurred. 01 January 02 February 03 March 04 April 05 May 06 June 07 July 08 August 09 September 10 October 11 November 12 December -- Unknown
* [INTEGER]   `hour_of_crash`
  - This data element records the hour at which the crash occurred. 00-23 Hour -- Not Applicable or Not Notified 99 Unknown
* [INTEGER]   `minute_of_crash`
  - This data element records the minutes after the hour at which the crash occurred. 00-59 Minute -- Not Applicable or Not Notified 99 Unknown
* [STRING]    `land_use`
  - 1 (Rural), 2 (Urban), 6 (Trafficway Not in State Inventory), 8 (Not Reported) and 9 (Unknown).
* [STRING]    `land_use_name`
  - 1 (Rural), 2 (Urban), 6 (Trafficway Not in State Inventory), 8 (Not Reported) and 9 (Unknown).
* [STRING]    `functional_system`
  - 01 (Interstate), 02 (Principal Arterial – Other Freeways and Expressways), 03 (Principal Arterial – Other), 04 (Minor Arterial), 05 (Major Collector), 06 (Minor Collector), 07 (Local), 96 (Trafficway Not in State Inventory), 98 (Not Reported), and 99 (Unknown).
* [STRING]    `functional_system_name`
  - 01 (Interstate), 02 (Principal Arterial – Other Freeways and Expressways), 03 (Principal Arterial – Other), 04 (Minor Arterial), 05 (Major Collector), 06 (Minor Collector), 07 (Local), 96 (Trafficway Not in State Inventory), 98 (Not Reported), and 99 (Unknown).
* [INTEGER]   `first_harmful_event`
  - This data element describes the first injury or damage producing event of the crash. For more info on the codes, please look at <C19 First Harmful Event> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `first_harmful_event_name`
  - This data element describes the first injury or damage producing event of the crash.
* [INTEGER]   `manner_of_collision`
  - This data element describes the orientation of two motor vehicles in-transport when they are involved in the “First Harmful Event” of a collision crash. If the “First Harmful Event” is not a collision between two motor vehicles in-transport it is classified as such. For more info on the codes, please look at <C20 Manner of Collision> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `manner_of_collision_name`
  - This data element describes the orientation of two motor vehicles in-transport when they are involved in the “First Harmful Event” of a collision crash. If the “First Harmful Event” is not a collision between two motor vehicles in-transport it is classified as such.
* [STRING]    `school_bus_related`
  - This data element identifies if a school bus, or motor vehicle functioning as a school bus, is related to the crash. 0 No 1 Yes -- Not Reported
* [INTEGER]   `vehicle_make`
  - This data element identifies the make (manufacturer) of this vehicle. For more info on the codes, please look at <V9 Vehicle Make> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `vehicle_make_name`
  - This data element identifies the make (manufacturer) of this vehicle.
* [INTEGER]   `make_model_combined`
  - This derived data element represents the 5-digit combination of two data elements, the 2-digit “Vehicle Make” code (MAKE) followed by the 3-digit “Vehicle Model” code (MODEL). See the current FARS/NASS GES Coding and Validation Manual for vehicle make and model codes.
* [INTEGER]   `body_type`
  - This data element identifies a classification of this vehicle based on its general body configuration, size, shape, doors, etc. For more info on the codes, please look at <V11 Body Type> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `body_type_name`
  - This data element identifies a classification of this vehicle based on its general body configuration, size, shape, doors, etc.
* [STRING]    `vehicle_trailing`
  - This data element identifies whether this vehicle had any attached trailing units or was towing another motor vehicle. A trailing unit can be a horse trailer, fifth wheel trailer, camper, boat, truck trailer, towed vehicle or any other trailer. For more info on the codes, please look at <V14 Vehicle Trailing> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `special_use`
  - This data element identifies any special use associated with this vehicle at the time of the crash. For more info on the codes, please look at <V22 Special Use> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `special_use_name`
  - This data element identifies any special use associated with this vehicle at the time of the crash.
* [STRING]    `emergency_motor_vehicle_use`
  - This data element identifies whether this vehicle was engaged in emergency use. Emergency Use indicates operation of any motor vehicle that is legally authorized by a government authority to respond to emergencies with or without the use of emergency warning equipment, such as a police vehicle, fire truck or ambulance while actually engaged in such response. -- No 0 Not Applicable -- Yes 2 Non-Emergency, Non-Transport 3 Non-Emergency Transport 4 Emergency Operation, Emergency Warning Equipment Not In Use 5 Emergency Operation, Emergency Warning Equipment In Use 6 Emergency Operation, Emergency Warning Equipment In Use Unknown 8 Not Reported 9 Unknown
* [STRING]    `rollover`
  - This data element identifies this vehicle’s involvement in a rollover or overturn during the crash. Rollover is defined as any vehicle rotation of 90 degrees or more about any true longitudinal or lateral axis. Rollover can occur at any time during the crash. 0 No Rollover -- First Event 1 Rollover, Tripped by Object/Vehicle -- Subsequent Event 2 Rollover, Untripped 9 Rollover, Unknown Type
* [INTEGER]   `initial_contact_point`
  - This data element identifies the area on this vehicle that produced the first instance of injury to non-motorists or occupants of this vehicle, or that resulted in the first instance of damage to other property or to this vehicle. For more info on the codes, please look at <V28A Initial Contact Point> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `initial_contact_point_name`
  - This data element identifies the area on this vehicle that produced the first instance of injury to non-motorists or occupants of this vehicle, or that resulted in the first instance of damage to other property or to this vehicle.
* [STRING]    `fire_occurrence`
  - This data element identifies whether a fire in any way related to the crash occurred in this vehicle. -- No Fire 0 No or Not Reported -- Fire Occurred in This Vehicle during Crash 1 Yes -- Fire Occurred in This Vehicle and Initiated Fire/Explosion in Another Vehicle
* [INTEGER]   `age`
  - This data element identifies this person’s age at the time of the crash, in years, with respect to their last birthday. 000 Less than One Year 001-120 Age of the Individual in Years 998 Not Reported 999 Unknown
* [STRING]    `sex`
  - This data element identifies the sex of this person involved in the crash. 1 Male 2 Female 8 Not Reported 9 Unknown
* [INTEGER]   `person_type`
  - This data element describes the role of this person involved in the crash. For more info on the codes, please look at <P7/NM7 Person Type> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `person_type_name`
  - This data element describes the role of this person involved in the crash.
* [INTEGER]   `injury_severity`
  - This data element describes the severity of the injury to this person in the crash using the KABCO scale. For more info on the codes, please look at <P8/NM8 Injury Severity> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `injury_severity_name`
  - This data element describes the severity of the injury to this person in the crash using the KABCO scale.
* [INTEGER]   `seating_position`
  - This data element identifies the location of this person in or on the vehicle. For more info on the codes, please look at <P9 Seating Position> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `seating_position_name`
  - This data element identifies the location of this person in or on the vehicle.
* [INTEGER]   `restraint_system_helmet_use`
  - This data element records the restraint equipment in use by the occupant, or the helmet in use by a motorcyclist, at the time of the crash. For more info on the codes, please look at <P10 Restraint System/Helmet Use> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `restraint_system_helmet_use_name`
  - This data element records the restraint equipment in use by the occupant, or the helmet in use by a motorcyclist, at the time of the crash.
* [STRING]    `indication_of_misuse_of_restraint_system_helmet`
  - This data element indicates any misuse of the restraint system or helmet used by this person. 0 No 1 Yes 8 Not a Motor Vehicle Occupant
* [INTEGER]   `air_bag_deployed`
  - This data element records air bag availability and deployment for this person as reported in the case materials. For more info on the codes, please look at <P12 Air Bag Deployed> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `air_bag_deployed_name`
  - This data element records air bag availability and deployment for this person as reported in the case materials.
* [INTEGER]   `ejection`
  - This data element describes the ejection status and degree of ejection for this person, excluding motorcycle occupants. 0 Not Ejected 1 Totally Ejected 2 Partially Ejected 3 Ejected – Unknown Degree (Since 2008) 7 Not Reported 8 Not Applicable -- Unknown (2007-2008) 9 Unknown if Ejected (Since 2009)
* [STRING]    `ejection_name`
  - This data element describes the ejection status and degree of ejection for this person, excluding motorcycle occupants.
* [INTEGER]   `ejection_path`
  - This data element identifies the path by which this person was ejected from the vehicle. For more info on the codes, please look at <P14 Ejection Path> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `ejection_path_name`
  - This data element identifies the path by which this person was ejected from the vehicle.
* [STRING]    `extrication`
  - This data element identifies if equipment or other force was used to remove this person from the vehicle. 0 Not Extricated/Not Applicable 1 Extricated 9 Unknown
* [STRING]    `police_reported_alcohol_involvement`
  - This data element records whether alcohol was involved for this person and reflects the judgment of law enforcement. 0 No (Alcohol Not Involved) 1 Yes (Alcohol Involved) 8 Not Reported 9 Unknown (Police Reported)
* [STRING]    `method_of_alcohol_determination_by_police`
  - This data element describes the method by which the police made the determination as to whether alcohol was involved for this person. 1 Evidential Test (Breath, Blood, Urine) 2 Preliminary Breath Test (PBT) 3 Behavioral 4 Passive Alcohol Sensor (PAS) 5 Observed 8 Other (e.g., Saliva Test) 9 Not Reported
* [STRING]    `alcohol_test_status1`
  - This data element identifies whether an alcohol test was given to this person. 0 Test Not Given 1 Test Refused 2 Test Given 8 Not Reported -- Unknown if Tested/Not Reported 9 Unknown if Tested
* [STRING]    `alcohol_test_status2`
  - This data element identifies the type of alcohol test that was given to this person. For more info on the codes, please look at <P18B/NM17B Alcohol Test Type> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `alcohol_test_status3`
  - This data element identifies the alcohol test result for this person. 000-939 Actual Value of BAC Test 940 0.94 or Greater (The value should be interpreted as  0.94 or greater, since 1995)  Test Refused (1991-2008) 995 Not Reported 996 None Given 997 AC Test Performed, Results Unknown 998 PBT Positive Reading with No Actual Value (Since 2004) -- Unknown if Tested/Not Reported 999 Unknown if Tested
* [STRING]    `alcohol_test_status3_name`
  - This data element identifies the alcohol test result for this person. 000-939 Actual Value of BAC Test 940 0.94 or Greater (The value should be interpreted as  0.94 or greater, since 1995)  Test Refused (1991-2008) 995 Not Reported 996 None Given 997 AC Test Performed, Results Unknown 998 PBT Positive Reading with No Actual Value (Since 2004) -- Unknown if Tested/Not Reported 999 Unknown if Tested
* [STRING]    `police_reported_drug_involvement`
  - This data element records whether drugs were involved for this person and reflects the judgment of law enforcement.0 No (Drugs Not Involved) 1 Yes (Drugs Involved) 8 Not Reported 9 Unknown (Police Reported)
* [STRING]    `method_of_drug_determination_by_police`
  - This data element identifies the method by which the police made the determination as to whether drugs were involved for this person. 1 Evidential Test (Blood, Urine) 2 Drug Recognition Technician (DRT) Determination 3 Behavioral 7 Other 8 Not Reported
* [STRING]    `drug_test_status`
  - This data element identifies whether a drug test was given to this person. 0 Test Not Given 1 Test Refused 2 Test Given 8 Not Reported -- Unknown if Tested/Not Reported 9 Unknown if Tested
* [STRING]    `drug_test_type1`
  - This data element identifies the type of drug test that was given to this person. 0 Test Not Given 1 Blood Test 2 Urine Test 3 Both Blood and Urine Tests 6 Not Reported 7 Unknown Test Type 8 Other Test Type -- Unknown if Tested/Not Reported 9 Unknown if Tested
* [STRING]    `drug_test_type2`
  - This data element identifies the type of drug test that was given to this person. 0 Test Not Given 1 Blood Test 2 Urine Test 3 Both Blood and Urine Tests 6 Not Reported 7 Unknown Test Type 8 Other Test Type -- Unknown if Tested/Not Reported 9 Unknown if Tested
* [STRING]    `drug_test_type3`
  - This data element identifies the type of drug test that was given to this person. 0 Test Not Given 1 Blood Test 2 Urine Test 3 Both Blood and Urine Tests 6 Not Reported 7 Unknown Test Type 8 Other Test Type -- Unknown if Tested/Not Reported 9 Unknown if Tested
* [INTEGER]   `drug_test_type4`
  - This data element identifies the drug test result for this person. For more info on the codes, please look at <P21C/NM20C Drug Test Result> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `drug_test_type4_name`
  - This data element identifies the drug test result for this person. For more info on the codes, please look at <P21C/NM20C Drug Test Result> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `drug_test_type5`
  - This data element identifies the drug test result for this person. For more info on the codes, please look at <P21C/NM20C Drug Test Result> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `drug_test_type5_name`
  - This data element identifies the drug test result for this person. For more info on the codes, please look at <P21C/NM20C Drug Test Result> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `drug_test_type6`
  - This data element identifies the drug test result for this person. For more info on the codes, please look at <P21C/NM20C Drug Test Result> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `drug_test_type6_name`
  - This data element identifies the drug test result for this person. For more info on the codes, please look at <P21C/NM20C Drug Test Result> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `transported_to_first_treatment_facility`
  - This data element identifies the mode of transportation to a hospital or medical facility provided for this person. For more info on the codes, please look at <P22/NM21 Transported to First Treatment Facility> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `transported_to_first_treatment_facility_name`
  - This data element identifies the mode of transportation to a hospital or medical facility provided for this person.
* [STRING]    `died_at_scene_en_route`
  - This data element identifies if this person died at the scene of the crash or en route to a hospital/medical facility. 0 Not Applicable 7 Died at Scene 8 Died En Route 9 Unknown
* [INTEGER]   `day_of_death`
  - This data element records the day of the month of this person’s death. 88 Not Applicable (Non-Fatal) 01-31 Day of the Month of the Death 99 Unknown (Since 2008)
* [INTEGER]   `month_of_death`
  - This data element records the month of this person’s death. For more info on the codes, please look at <P24A/NM23A Month of Death> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `year_of_death`
  - This data element records the year of this person’s death. 8888 Not Applicable (Non-Fatal) xxxx Year of the Death 9999 Unknown
* [INTEGER]   `hour_of_death`
  - This data element records the hour of this person’s death utilizing the 24-hour clock format. 00-23 Valid Military Times 88 Not Applicable 99 Unknown
* [INTEGER]   `minute_of_death`
  - This data element records the minutes after the hour of this person’s death. 00-59 Valid Military Times 88 Not Applicable 99 Unknown
* [INTEGER]   `death_time`
  - This data element records the hour and minute of this person’s death utilizing the 24-hour clock format. 0000 For Midnight 0001-2359 Time of Death in HHMM format 8888 Not Applicable (Non-Fatal) 9999 Unknown
* [INTEGER]   `lag_hours`
  - This data element records the hours between the time of the crash and this person’s time of death. 00-719 Hours 999 Unknown
* [INTEGER]   `lag_minutes`
  - This data element records the minutes, in addition to hours (“Lag Hours”), between the time of the crash and this person’s time of death. 00-59 Minutes 99 Unknown
* [INTEGER]   `related_factors_person_level1`
  - This data element records factors related to motor vehicle occupants other than drivers and persons not in motor vehicles as expressed by the investigating officer. For more info on the codes, please look at <P26/NM25 Related Factors- Person Level> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `related_factors_person_level2`
  - This data element records factors related to motor vehicle occupants other than drivers and persons not in motor vehicles as expressed by the investigating officer. For more info on the codes, please look at <P26/NM25 Related Factors- Person Level> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `related_factors_person_level3`
  - This data element records factors related to motor vehicle occupants other than drivers and persons not in motor vehicles as expressed by the investigating officer. For more info on the codes, please look at <P26/NM25 Related Factors- Person Level> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `fatal_injury_at_work`
  - This data element records whether the death certificate indicated this person was "at work" at the time of the crash. 0 No (The Injury Was Not At Work) 1 Yes (The Injury Was At Work) 8 Not Applicable (Not A Fatality) 9 Unknown
* [INTEGER]   `hispanic_origin`
  - This data element records the Hispanic origin of this person from the death certificate. For more info on the codes, please look at <SP3B Hispanic Origin> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `hispanic_origin_name`
  - This data element records the Hispanic origin of this person from the death certificate.
* [INTEGER]   `race`
  - This data element records the race of this person from the death certificate. For more info on the codes, please look at <SP3A Race> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `race_name`
  - This data element records the race of this person from the death certificate.
* [INTEGER]   `non_motorist_location_at_time_of_crash`
  - This data element identifies the attribute which best describes the location of this non-motorist with respect to the roadway at the time of the crash. For more info on the codes, please look at <NM10 Non-Motorist Location at Time of Crash> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `non_motorist_location_at_time_of_crash_name`
  - This data element identifies the attribute which best describes the location of this non-motorist with respect to the roadway at the time of the crash.
* [TIMESTAMP] `timestamp_of_crash`
  - This data element records the date and time on which the crash occurred.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
