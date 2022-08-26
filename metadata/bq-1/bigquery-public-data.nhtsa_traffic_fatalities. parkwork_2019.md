# `nhtsa_traffic_fatalities. parkwork_2019`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `state_number`
  - This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). For more info on the codes, please look at <C1/V1/D1/PC1/P1/NM1 State Number> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `state_name`
  - This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC).
* [INTEGER]   `consecutive_number`
  - This data element is the unique case number assigned to each crash. It appears on each data file and is used to merge information from the data files together. xxxxxx Two Characters for State Code followed by Four Characters for Case Number
* [INTEGER]   `vehicle_number`
  - This data element is the consecutive number assigned to each vehicle in the case. This data element appears on each vehicle level data file and is used in conjunction with the ST_CASE data element to merge information from vehicle level data files. 000-999 Assigned Number of Motor Vehicle
* [INTEGER]   `number_of_motor_vehicles_in_transport_mvit`
  - This data element is a count of the number of vehicles in-transport involved in the crash. Legally parked vehicles are not included. 001-999 Number of Vehicle Forms
* [INTEGER]   `number_of_occupants`
  - This data element is a count of the number of occupants in this vehicle.00 None 01-95 The Actual Number of Occupants in The Vehicle 96 96 Or More Occupants in The Vehicle 98 Not Reported 99 Unknown
* [STRING]    `number_of_occupants_name`
  - This data element is a count of the number of occupants in this vehicle.00 None 01-95 The Actual Number of Occupants in The Vehicle 96 96 Or More Occupants in The Vehicle 98 Not Reported 99 Unknown
* [INTEGER]   `day_of_crash`
  - This data element records the day of the month on which the crash occurred. 01-31 Day of the Month of the Crash
* [STRING]    `day_of_crash_name`
  - This data element records the day of the month on which the crash occurred. 01-31 Day of the Month of the Crash
* [INTEGER]   `month_of_crash`
  - This data element records the month in which the crash occurred.For more info on the codes, please look at <C8A Month of Crash> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `month_of_crash_name`
  - This data element records the month in which the crash occurred.For more info on the codes, please look at <C8A Month of Crash> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `hour_of_crash`
  - This data element records the hour at which the crash occurred.0-23 Hour 99 Unknown
* [STRING]    `hour_of_crash_name`
  - This data element records the hour at which the crash occurred.0-23 Hour 99 Unknown
* [INTEGER]   `minute_of_crash`
  - This data element records the minutes after the hour at which the crash occurred.0-59 Minute 99 Unknown
* [STRING]    `minute_of_crash_name`
  - This data element records the minutes after the hour at which the crash occurred.0-59 Minute 99 Unknown
* [INTEGER]   `first_harmful_event`
  - This data element describes the first injury or damage producing event of the crash.For more info on the codes, please look at <C19 First Harmful Event> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `first_harmful_event_name`
  - This data element describes the first injury or damage producing event of the crash.
* [INTEGER]   `manner_of_collision`
  - This data element describes the orientation of two motor vehicles in-transport when they are involved in the “First Harmful Event” of a collision crash. If the “First Harmful Event” is not a collision between two motor vehicles in-transport it is classified as such.For more info on the codes, please look at <C20 Manner of Collision> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `manner_of_collision_name`
  - This data element describes the orientation of two motor vehicles in-transport when they are involved in the “First Harmful Event” of a collision crash. If the “First Harmful Event” is not a collision between two motor vehicles in-transport it is classified as such.
* [INTEGER]   `unit_type`
  - This data element identifies the type of unit that applies to this motor vehicle at the time it became an involved vehicle in the crash and was reported as a unit on the PAR.2 Motor Vehicle Not in Transport Within the Trafficway 3 Motor Vehicle Not in Transport Outside the Trafficway 4 Working Motor Vehicle (Highway Construction, Maintenance, Utility Only)
* [STRING]    `unit_type_name`
  - This data element identifies the type of unit that applies to this motor vehicle at the time it became an involved vehicle in the crash and was reported as a unit on the PAR.2 Motor Vehicle Not in Transport Within the Trafficway 3 Motor Vehicle Not in Transport Outside the Trafficway 4 Working Motor Vehicle (Highway Construction, Maintenance, Utility Only)
* [INTEGER]   `hit_and_run`
  - This data element identifies whether this vehicle was a contact vehicle in the crash that did not stop to render aid (this can include drivers who flee the scene on foot). Hit and run is coded when a motor vehicle in-transport, or its driver, departs from the scene; vehicles not intransport are excluded. It does not matter whether the hit-and-run vehicle was striking or struck. 0 No / No Hit-and-Run -- Hit Motor Vehicle in Transport 1 Yes -- Hit Pedestrian or Non-Motorist -- Hit Parked Vehicle (Working Vehicle, Since 2004) or Object -- Other Involved Person, not a driver, left Scene (2005-2006) -- Hit-and-Run, Other Involved Person Left Scene (2007-2008) -- Not Reported 9 Unknown
* [STRING]    `hit_and_run_name`
  - This data element identifies whether this vehicle was a contact vehicle in the crash that did not stop to render aid (this can include drivers who flee the scene on foot). Hit and run is coded when a motor vehicle in-transport, or its driver, departs from the scene; vehicles not intransport are excluded. It does not matter whether the hit-and-run vehicle was striking or struck. 0 No / No Hit-and-Run -- Hit Motor Vehicle in Transport 1 Yes -- Hit Pedestrian or Non-Motorist -- Hit Parked Vehicle (Working Vehicle, Since 2004) or Object -- Other Involved Person, not a driver, left Scene (2005-2006) -- Hit-and-Run, Other Involved Person Left Scene (2007-2008) -- Not Reported 9 Unknown
* [INTEGER]   `registration_state`
  - This element identifies the state in which this vehicle was registered.For more info on the codes, please look at <V7 Registration State> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `registration_state_name`
  - This element identifies the state in which this vehicle was registered.
* [INTEGER]   `registered_vehicle_owner`
  - This data element identifies the type of registered owner of the vehicle.0 Not Applicable, Vehicle Not Registered 1 Driver (of This Vehicle) Was Registered Owner 2 Driver (of This Vehicle) Not Registered Owner (Other Private Owner) 3 Vehicle Registered as Business/Company/Government Vehicle 4 Vehicle Registered as Rental Vehicle 5 Vehicle Was Stolen (Reported By Police) -- Driverless Vehicle 6 Driverless/Motor Vehicle Parked/Stopped Off Roadway 9 Unknown
* [STRING]    `registered_vehicle_owner_name`
  - This data element identifies the type of registered owner of the vehicle.
* [INTEGER]   `vehicle_make`
  - This data element identifies the make (manufacturer) of this vehicle.For more info on the codes, please look at <V9 Vehicle Make> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `vehicle_make_name`
  - This data element identifies the make (manufacturer) of this vehicle.
* [INTEGER]   `vehicle_model`
  - This data element identifies the model of this vehicle within a given make.See the current FARS/NASS GES Coding and Validation Manual for vehicle model codes.
* [STRING]    `make_model_combined`
  - This derived data element represents the 5-digit combination of two data elements, the 2-digit “Vehicle Make” code (MAKE) followed by the 3-digit “Vehicle Model” code (MODEL).See the current FARS/NASS GES Coding and Validation Manual for vehicle make and model codes.
* [INTEGER]   `body_type`
  - This data element identifies a classification of this vehicle based on its general body configuration, size, shape, doors, etc.For more info on the codes, please look at <V11 Body Type> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `body_type_name`
  - This data element identifies a classification of this vehicle based on its general body configuration, size, shape, doors, etc.
* [INTEGER]   `vehicle_model_year`
  - This data element identifies the manufacturer's model year of this vehicle.0000-9997 Actual year of vehicle manufacture 9998 Not Reported 9999 Unknown
* [STRING]    `vehicle_model_year_name`
  - This data element identifies the manufacturer's model year of this vehicle.0000-9997 Actual year of vehicle manufacture 9998 Not Reported 9999 Unknown
* [STRING]    `vehicle_identification_number_vin`
  - This data element records the vehicle identification number (VIN) of this vehicle assigned by the vehicle manufacturer. The VIN contains information on the vehicle such as: manufacturer, model year, model, body type, restraint type, etc.-- First 10 Characters xxxxxxxxxxxx First 12 Characters 000000000000 No VIN Required 888888888888 Not Reported 999999999999 Unknown
* [STRING]    `vehicle_identification_number_vin_name`
  - This data element records the vehicle identification number (VIN) of this vehicle assigned by the vehicle manufacturer. The VIN contains information on the vehicle such as: manufacturer, model year, model, body type, restraint type, etc.-- First 10 Characters xxxxxxxxxxxx First 12 Characters 000000000000 No VIN Required 888888888888 Not Reported 999999999999 Unknown
* [STRING]    `vin_character_1`
  - This data element represents the first character in the VIN string for this vehicle.x First Character in the VIN String
* [STRING]    `vin_character_2`
  - This data element represents the second character in the VIN string for this vehicle.x Second Character in the VIN String
* [STRING]    `vin_character_3`
  - This data element represents the third character in the VIN string for this vehicle.x Third Character in the VIN String
* [STRING]    `vin_character_4`
  - This data element represents the fourth character in the VIN string for this vehicle.x Fourth Character in the VIN String
* [STRING]    `vin_character_5`
  - This data element represents the fifth character in the VIN string for this vehicle.x Fifth Character in the VIN String
* [STRING]    `vin_character_6`
  - This data element represents the sixth character in the VIN string for this vehicle.x Sixth Character in the VIN String
* [STRING]    `vin_character_7`
  - This data element represents the seventh character in the VIN string for this vehicle.x Seventh Character in the VIN String
* [STRING]    `vin_character_8`
  - This data element represents the eighth character in the VIN string for this vehicle.x Eighth Character in the VIN String
* [STRING]    `vin_character_9`
  - This data element represents the ninth character in the VIN string for this vehicle.x Ninth Character in the VIN String
* [STRING]    `vin_character_10`
  - This data element represents the tenth character in the VIN string for this vehicle.x Tenth Character in the VIN String
* [STRING]    `vin_character_11`
  - This data element represents the eleventh character in the VIN string for this vehicle.x Eleventh Character in the VIN String
* [STRING]    `vin_character_12`
  - This data element represents the twelfth character in the VIN string for this vehicle.x Twelfth Character in the VIN String
* [INTEGER]   `vehicle_trailing`
  - This data element identifies whether this vehicle had any attached trailing units or was towing another motor vehicle. A trailing unit can be a horse trailer, fifth wheel trailer, camper, boat, truck trailer, towed vehicle or any other trailer.0 No Trailing Unit 1 Yes, One Trailing Unit 2 Yes, Two Trailing Units 3 Yes, Three or More Trailing Units 4 Yes, Number of Trailing Units Unknown -- Vehicle Towing another Motor Vehicle 5 Vehicle Towing another Motor Vehicle – Fixed Linkage 6 Vehicle Towing another Motor Vehicle – Non-Fixed Linkage 9 Unknown
* [STRING]    `vehicle_trailing_name`
  - This data element identifies whether this vehicle had any attached trailing units or was towing another motor vehicle. A trailing unit can be a horse trailer, fifth wheel trailer, camper, boat, truck trailer, towed vehicle or any other trailer.0 No Trailing Unit 1 Yes, One Trailing Unit 2 Yes, Two Trailing Units 3 Yes, Three or More Trailing Units 4 Yes, Number of Trailing Units Unknown -- Vehicle Towing another Motor Vehicle 5 Vehicle Towing another Motor Vehicle – Fixed Linkage 6 Vehicle Towing another Motor Vehicle – Non-Fixed Linkage 9 Unknown
* [INTEGER]   `mcid_issuing_authority`
  - This data element records the issuing authority if applicable to this vehicle.00 Not Applicable 01-56 FARS State Code 57 US DOT 58 MC/MX (ICC) 77 Not Reported 88 None 95 Canada 96 Mexico 99 Unknown
* [STRING]    `mcid_issuing_authority_name`
  - This data element records the issuing authority if applicable to this vehicle.00 Not Applicable 01-56 FARS State Code 57 US DOT 58 MC/MX (ICC) 77 Not Reported 88 None 95 Canada 96 Mexico 99 Unknown
* [STRING]    `mcid_identification_number`
  - This data element records the motor carrier identification number if applicable to this vehicle.xxxxxxxxx Actual 9-Digit Number 000000000 Not Applicable 777777777 Not Reported 888888888 None 999999999 Unknown
* [STRING]    `mcid_identification_number_name`
  - This data element records the motor carrier identification number if applicable to this vehicle.xxxxxxxxx Actual 9-Digit Number 000000000 Not Applicable 777777777 Not Reported 888888888 None 999999999 Unknown
* [STRING]    `motor_carrier_identification_number`
  - This data element records the issuing authority and motor carrier identification number if applicable to this vehicle. This data element is the combination of two data elements, MCARR_I1 and MCARR_I2.xxxxxxxxxxx 11-Character Combination of MCARR_I1 followed by MCARR_I2 00000000000 Not Applicable 77777777777 Not Reported 88888888888 None 99999999999 Unknown
* [STRING]    `motor_carrier_identification_number_name`
  - This data element records the issuing authority and motor carrier identification number if applicable to this vehicle. This data element is the combination of two data elements, MCARR_I1 and MCARR_I2.xxxxxxxxxxx 11-Character Combination of MCARR_I1 followed by MCARR_I2 00000000000 Not Applicable 77777777777 Not Reported 88888888888 None 99999999999 Unknown
* [INTEGER]   `gross_vehicle_weight_rating`
  - This data element identifies the gross vehicle weight rating of this vehicle if applicable.0 Not Applicable 1 10,000 lbs or Less 2 10,001 lbs - 26,000 lbs 3 26,001 lbs or More 8 Not Reported 9 Unknown
* [STRING]    `gross_vehicle_weight_rating_name`
  - This data element identifies the gross vehicle weight rating of this vehicle if applicable.0 Not Applicable 1 10,000 lbs or Less 2 10,001 lbs - 26,000 lbs 3 26,001 lbs or More 8 Not Reported 9 Unknown
* [INTEGER]   `vehicle_configuration`
  - This data element identifies the general configuration of this vehicle if applicable.For more info on the codes, please look at <V18 Vehicle Configuration> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `vehicle_configuration_name`
  - This data element identifies the general configuration of this vehicle if applicable.For more info on the codes, please look at <V18 Vehicle Configuration> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `cargo_body_type`
  - This data element identifies the primary cargo carrying capability of this vehicle if applicable.For more info on the codes, please look at <V19 Cargo Body Type> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `cargo_body_type_name`
  - This data element identifies the primary cargo carrying capability of this vehicle if applicable.For more info on the codes, please look at <V19 Cargo Body Type> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `hazardous_material_involvement`
  - This data element identifies whether this vehicle was carrying hazardous materials.1 No 2 Yes
* [STRING]    `hazardous_material_involvement_name`
  - This data element identifies whether this vehicle was carrying hazardous materials.1 No 2 Yes
* [INTEGER]   `hazardous_material_placard`
  - This data element identifies the presence of hazardous materials for this vehicle and whether this vehicle displayed a hazardous materials placard.0 Not Applicable 1 No 2 Yes 8 Not Reported
* [STRING]    `hazardous_material_placard_name`
  - This data element identifies the presence of hazardous materials for this vehicle and whether this vehicle displayed a hazardous materials placard.0 Not Applicable 1 No 2 Yes 8 Not Reported
* [INTEGER]   `hazardous_material_identification_number`
  - This data element identifies the 4-digit hazardous material identification number for this vehicle.0000 Not Applicable xxxx Actual 4-Digit Number 8888 Not Reported
* [STRING]    `hazardous_material_identification_number_name`
  - This data element identifies the 4-digit hazardous material identification number for this vehicle.0000 Not Applicable xxxx Actual 4-Digit Number 8888 Not Reported
* [INTEGER]   `hazardous_material_class_number`
  - This data element identifies the single-digit hazardous material class number for this vehicle.0 Not Applicable 1-9 Actual Number 88 Not Reported
* [STRING]    `hazardous_material_class_number_name`
  - This data element identifies the single-digit hazardous material class number for this vehicle.0 Not Applicable 1-9 Actual Number 88 Not Reported
* [INTEGER]   `release_of_hazardous_material_from_the_cargo_compartment`
  - This data element identifies whether any hazardous cargo was released from the cargo tank or compartment of this vehicle.0 Not Applicable 1 No 2 Yes 8 Not Reported
* [STRING]    `release_of_hazardous_material_from_the_cargo_compartment_name`
  - This data element identifies whether any hazardous cargo was released from the cargo tank or compartment of this vehicle.0 Not Applicable 1 No 2 Yes 8 Not Reported
* [INTEGER]   `bus_use`
  - This data element describes the common type of bus service this vehicle was being used as at the time of the crash or the primary use for the bus if not in service at the time of the crash.00 Not a Bus 01 School Bus 04 Intercity Bus 05 Charter/Tour Bus 06 Transit/Commuter Bus 07 Shuttle Bus 08 Modified for Personal/Private Use 98 Not Reported 99 Unknown
* [STRING]    `bus_use_name`
  - This data element describes the common type of bus service this vehicle was being used as at the time of the crash or the primary use for the bus if not in service at the time of the crash.00 Not a Bus 01 School Bus 04 Intercity Bus 05 Charter/Tour Bus 06 Transit/Commuter Bus 07 Shuttle Bus 08 Modified for Personal/Private Use 98 Not Reported 99 Unknown
* [INTEGER]   `special_use`
  - This data element identifies any special use associated with this vehicle at the time of the crash.For more info on the codes, please look at <V22 Special Use> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `special_use_name`
  - This data element identifies any special use associated with this vehicle at the time of the crash.
* [INTEGER]   `emergency_motor_vehicle_use`
  - This data element identifies whether this vehicle was engaged in emergency use. Emergency Use indicates operation of any motor vehicle that is legally authorized by a government authority to respond to emergencies with or without the use of emergency warning equipment, such as a police vehicle, fire truck or ambulance while actually engaged in such response.-- No 0 Not Applicable -- Yes 2 Non-Emergency, Non-Transport 3 Non-Emergency Transport 4 Emergency Operation, Emergency Warning Equipment Not In Use 5 Emergency Operation, Emergency Warning Equipment In Use 6 Emergency Operation, Emergency Warning Equipment In Use Unknown 8 Not Reported 9 Unknown
* [STRING]    `emergency_motor_vehicle_use_name`
  - This data element identifies whether this vehicle was engaged in emergency use. Emergency Use indicates operation of any motor vehicle that is legally authorized by a government authority to respond to emergencies with or without the use of emergency warning equipment, such as a police vehicle, fire truck or ambulance while actually engaged in such response.-- No 0 Not Applicable -- Yes 2 Non-Emergency, Non-Transport 3 Non-Emergency Transport 4 Emergency Operation, Emergency Warning Equipment Not In Use 5 Emergency Operation, Emergency Warning Equipment In Use 6 Emergency Operation, Emergency Warning Equipment In Use Unknown 8 Not Reported 9 Unknown
* [INTEGER]   `underride_override`
  - This data element identifies this vehicle’s involvement in an underride or override during the crash.For more info on the codes, please look at <V25 Underride/Override> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `underride_override_name`
  - This data element identifies this vehicle’s involvement in an underride or override during the crash.
* [INTEGER]   `initial_contact_point`
  - This data element identifies the area on this vehicle that produced the first instance of injury to non-motorists or occupants of this vehicle, or that resulted in the first instance of damage to other property or to this vehicle.For more info on the codes, please look at <V28A Initial Contact Point> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `initial_contact_point_name`
  - This data element identifies the area on this vehicle that produced the first instance of injury to non-motorists or occupants of this vehicle, or that resulted in the first instance of damage to other property or to this vehicle.For more info on the codes, please look at <V28A Initial Contact Point> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `extent_of_damage`
  - This data element records the amount of damage sustained by this vehicle as indicated on the PAR based on an operational damage scale.0 No Damage 2 Minor Damage 4 Functional Damage 6 Disabling Damage 8 Not Reported 9 Unknown
* [STRING]    `extent_of_damage_name`
  - This data element records the amount of damage sustained by this vehicle as indicated on the PAR based on an operational damage scale.0 No Damage 2 Minor Damage 4 Functional Damage 6 Disabling Damage 8 Not Reported 9 Unknown
* [INTEGER]   `vehicle_removal`
  - This data element describes the mode by which this vehicle left the scene of the crash.-- Driven Away -- Towed Away 2 Towed Due to Disabling Damage -- Abandoned/Left Scene 3 Towed Not Due to Disabling Damage -- Abandoned/Left Scene 5 Not Towed 8 Not Reported 9 Unknown
* [STRING]    `vehicle_removal_name`
  - This data element describes the mode by which this vehicle left the scene of the crash.-- Driven Away -- Towed Away 2 Towed Due to Disabling Damage -- Abandoned/Left Scene 3 Towed Not Due to Disabling Damage -- Abandoned/Left Scene 5 Not Towed 8 Not Reported 9 Unknown
* [INTEGER]   `most_harmful_event`
  - This data element describes the event that resulted in the most severe injury or, if no injury, the greatest property damage involving this vehicle.For more info on the codes, please look at <V32 Most Harmful Event> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `most_harmful_event_name`
  - This data element describes the event that resulted in the most severe injury or, if no injury, the greatest property damage involving this vehicle.For more info on the codes, please look at <V32 Most Harmful Event> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `related_factors_vehicle_level1`
  - This data element records factors related to this vehicle expressed by the investigating officer.For more info on the codes, please look at <V33 Related Factors – Vehicle Level> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `related_factors_vehicle_level1_name`
  - This data element records factors related to this vehicle expressed by the investigating officer.For more info on the codes, please look at <V33 Related Factors – Vehicle Level> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `related_factors_vehicle_level2`
  - This data element records factors related to this vehicle expressed by the investigating officer.For more info on the codes, please look at <V33 Related Factors – Vehicle Level> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `related_factors_vehicle_level2_name`
  - This data element records factors related to this vehicle expressed by the investigating officer.For more info on the codes, please look at <V33 Related Factors – Vehicle Level> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `fire_occurrence`
  - This data element identifies whether a fire in any way related to the crash occurred in this vehicle.-- No Fire 0 No or Not Reported -- Fire Occurred in This Vehicle during Crash 1 Yes -- Fire Occurred in This Vehicle and Initiated Fire/Explosion in Another Vehicle
* [STRING]    `fire_occurrence_name`
  - This data element identifies whether a fire in any way related to the crash occurred in this vehicle.-- No Fire 0 No or Not Reported -- Fire Occurred in This Vehicle during Crash 1 Yes -- Fire Occurred in This Vehicle and Initiated Fire/Explosion in Another Vehicle
* [INTEGER]   `fatalities_in_vehicle`
  - This derived data element records the number of fatalities that occurred in this vehicle and is derived by counting all persons with “Injury Severity” of 4 in the vehicle.00-99 Number of Fatalities that Occurred in the Vehicle.
* [STRING]    `ptrlr1vin`
  - This data element records the vehicle identification number (VIN) of any trailing units of a combination vehicle.
* [STRING]    `ptrlr1vinname`
  - This data element records the vehicle identification number (VIN) of any trailing units of a combination vehicle.
* [STRING]    `ptrlr2vin`
  - This data element records the vehicle identification number (VIN) of any trailing units of a combination vehicle.
* [STRING]    `ptrlr2vinname`
  - This data element records the vehicle identification number (VIN) of any trailing units of a combination vehicle.
* [STRING]    `ptrlr3vin`
  - This data element records the vehicle identification number (VIN) of any trailing units of a combination vehicle.
* [STRING]    `ptrlr3vinname`
  - This data element records the vehicle identification number (VIN) of any trailing units of a combination vehicle.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
