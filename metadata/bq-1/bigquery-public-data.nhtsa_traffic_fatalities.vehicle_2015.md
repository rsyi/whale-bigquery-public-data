# `nhtsa_traffic_fatalities.vehicle_2015`
`bq-1` | `bigquery-public-data`
This data file contains information describing the in-transport
motor vehicles and the drivers of in-transport motor vehicle who are involved in the
crash. There is one record per in-transport motor vehicle. Parked and working vehicle
information is in the Parkwork data file

## Column details
* [INTEGER]   `state_number`
  - This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). For more info on the codes, please look at <C1/V1/D1/PC1/P1/NM1 State Number> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `consecutive_number`
  - This data element is the unique case number assigned to each crash. It appears on each data file and is used to merge information from the data files together. xxxxxx Two Characters for State Code followed by Four Characters for Case Number
* [INTEGER]   `vehicle_number`
  - This data element is the consecutive number assigned to each vehicle in the case. This data element appears on each vehicle level data file and is used in conjunction with the ST_CASE data element to merge information from vehicle level data files. 000-999 Assigned Number of Motor Vehicle
* [INTEGER]   `number_of_motor_vehicles_in_transport_mvit`
  - This data element is a count of the number of vehicles in-transport involved in the crash. Legally parked vehicles are not included. 001-999 Number of Vehicle Forms
* [INTEGER]   `number_of_occupants`
  - This data element is a count of the number of occupants in this vehicle. 00 None 01-95 Actual Number of Occupants in The Vehicle 96 96 or More Occupants in The Vehicle -- Unknown – Only Injured Reported 98 Not Reported (2010 Only) 99 Unknown
* [INTEGER]   `day_of_crash`
  - This data element records the day of the month on which the crash occurred. 01-31 Day of the Month of the Crash -- Unknown
* [INTEGER]   `month_of_crash`
  - This data element records the month in which the crash occurred.For more info on the codes, please look at C8A Month of Crash section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `hour_of_crash`
  - This data element records the hour at which the crash occurred.0-23 Hour -- Not Applicable or Not Notified 99 Unknown
* [INTEGER]   `minute_of_crash`
  - This data element records the minutes after the hour at which the crash occurred. 00-59 Minute -- Not Applicable or Not Notified 99 Unknown
* [INTEGER]   `first_harmful_event`
  - This data element describes the first injury or damage producing event of the crash. For more info on the codes, please look at C19 First Harmful Event section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `first_harmful_event_name`
  - This data element describes the first injury or damage producing event of the crash.
* [INTEGER]   `manner_of_collision`
  - This data element describes the orientation of two motor vehicles in-transport when they are involved in the “First Harmful Event” of a collision crash. If the “First Harmful Event” is not a collision between two motor vehicles in-transport it is classified as such. For more info on the codes, please look at C20 Manner of Collision section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `unit_type`
  - This data element identifies the type of unit that applies to this motor vehicle at the time it became an involved vehicle in the crash and was reported as a unit on the PAR. -- Motor Vehicle in Transport 1 Motor Vehicle in Transport (Inside or Outside the Trafficway)
* [STRING]    `hit_and_run`
  - This data element identifies whether this vehicle was a contact vehicle in the crash that did not stop to render aid (this can include drivers who flee the scene on foot). Hit and run is coded when a motor vehicle in-transport, or its driver, departs from the scene; vehicles not intransport are excluded. It does not matter whether the hit-and-run vehicle was striking or struck. 0 No 1 Yes -- Not Reported 9 Unknown
* [INTEGER]   `registration_state`
  - This element identifies the state in which this vehicle was registered. For more info on the codes, please look at V7 Registration State section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `registration_state_name`
  - This element identifies the state in which this vehicle was registered.
* [INTEGER]   `registered_vehicle_owner`
  - This data element identifies the type of registered owner of the vehicle. 0 Not Applicable, Vehicle Not Registered 1 Driver (of This Vehicle) Was Registered Owner 2 Driver (of This Vehicle) Not Registered Owner (Other Private Owner) 3 Vehicle Registered as Business/Company/Government Vehicle 4 Vehicle Registered as Rental Vehicle 5 Vehicle Was Stolen (Reported By Police) -- Driverless Vehicle 6 Driverless/Motor Vehicle Parked/Stopped Off Roadway 9 Unknown
* [STRING]    `registered_vehicle_owner_name`
  - This data element identifies the type of registered owner of the vehicle.
* [INTEGER]   `vehicle_make`
  - This data element identifies the make (manufacturer) of this vehicle. For more info on the codes, please look at V9 Vehicle Make section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `vehicle_make_name`
  - This data element identifies the make (manufacturer) of this vehicle
* [INTEGER]   `vehicle_model`
  - This data element identifies the model of this vehicle within a given make. For more info on the codes, please look at V10 Vehicle Model section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `make_model_combined`
  - This derived data element represents the 5-digit combination of two data elements, the 2-digit “Vehicle Make” code (MAKE) followed by the 3-digit “Vehicle Model” code (MODEL). For more info on the codes, please look at V100 Make Model Combined section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `body_type`
  - This data element identifies a classification of this vehicle based on its general body configuration, size, shape, doors, etc. For more info on the codes, please look at V11 Body Type section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `body_type_name`
  - This data element identifies a classification of this vehicle based on its general body configuration, size, shape, doors, etc.
* [INTEGER]   `vehicle_model_year`
  - This data element identifies the manufacturer's model year of this vehicle. 0000-9997 Actual year of vehicle manufacture 9998 Not Reported 9999 Unknown
* [STRING]    `vehicle_identification_number_vin`
  - This data element records the vehicle identification number (VIN) of this vehicle assigned by the vehicle manufacturer. The VIN contains information on the vehicle such as: manufacturer, model year, model, body type, restraint type, etc. -- First 10 Characters xxxxxxxxxxxx  First 12 Characters 000000000000 No VIN Required 888888888888 Not Reported 999999999999 Unknown
* [STRING]    `vin_character_1`
  - This data element represents the first character in the VIN string for this vehicle. x First Character in the VIN String
* [STRING]    `vin_character_2`
  - This data element represents the second character in the VIN string for this vehicle. x Second Character in the VIN String
* [STRING]    `vin_character_3`
  - This data element represents the third character in the VIN string for this vehicle. x Third Character in the VIN String
* [STRING]    `vin_character_4`
  - This data element represents the fourth character in the VIN string for this vehicle. x Fourth Character in the VIN String
* [STRING]    `vin_character_5`
  - This data element represents the fifth character in the VIN string for this vehicle. x Fifth Character in the VIN String
* [STRING]    `vin_character_6`
  - This data element represents the sixth character in the VIN string for this vehicle. x Sixth Character in the VIN String
* [STRING]    `vin_character_7`
  - This data element represents the seventh character in the VIN string for this vehicle. x Seventh Character in the VIN String
* [STRING]    `vin_character_8`
  - This data element represents the eighth character in the VIN string for this vehicle. x Eighth Character in the VIN String
* [STRING]    `vin_character_9`
  - This data element represents the ninth character in the VIN string for this vehicle. x Ninth Character in the VIN String
* [STRING]    `vin_character_10`
  - This data element represents the tenth character in the VIN string for this vehicle. x Tenth Character in the VIN String
* [STRING]    `vin_character_11`
  - This data element represents the eleventh character in the VIN string for this vehicle. x Eleventh Character in the VIN String
* [STRING]    `vin_character_12`
  - This data element represents the twelfth character in the VIN string for this vehicle. x Twelfth Character in the VIN String
* [STRING]    `vehicle_trailing`
  - This data element identifies whether this vehicle had any attached trailing units or was towing another motor vehicle. A trailing unit can be a horse trailer, fifth wheel trailer, camper, boat, truck trailer, towed vehicle or any other trailer. 0 No Trailing Unit 1 Yes, One Trailing Unit 2 Yes, Two Trailing Units 3 Yes, Three or More Trailing Units 4 Yes, Number of Trailing Units Unknown -- Vehicle Towing another Motor Vehicle 5 Vehicle Towing another Motor Vehicle – Fixed Linkage 6 Vehicle Towing another Motor Vehicle – Non-Fixed Linkage 9 Unknown
* [STRING]    `jackknife`
  - This data element identifies whether this vehicle experienced a jackknife anytime during the unstabilized situation. 0 Not an Articulated Vehicle 1 No -- Yes 2 Yes, First Event 3 Yes, Subsequent Event
* [INTEGER]   `mcid_issuing_authority`
  - This data element records the issuing authority if applicable to this vehicle. 00 Not Applicable 01-56 FARS State Code 57 US DOT 58 MC/MX (ICC) 77 Not Reported 88 None 95 Canada 96 Mexico 99 Unknown
* [STRING]    `mcid_identification_number`
  - This data element records the motor carrier identification number if applicable to this vehicle. xxxxxxxxx Actual 9-Digit Number 000000000 Not Applicable 777777777 Not Reported 888888888 None 999999999 Unknown
* [STRING]    `motor_carrier_identification_number_mcid`
  - This data element records the issuing authority and motor carrier identification number if applicable to this vehicle. This data element is the combination of two data elements, MCARR_I1 and MCARR_I2. xxxxxxxxxxx 11-Character Combination of MCARR_I1 followed by MCARR_I2 00000000000 Not Applicable 77777777777 Not Reported 88888888888 None 99999999999 Unknown
* [STRING]    `gross_vehicle_weight_rating`
  - This data element identifies the gross vehicle weight rating of this vehicle if applicable. 0 Not Applicable 1 10,000 lbs or Less 2 10,001 lbs - 26,000 lbs 3 26,001 lbs or More 8 Not Reported 9 Unknown
* [INTEGER]   `vehicle_configuration`
  - This data element identifies the general configuration of this vehicle if applicable. For more info on the codes, please look at V18 Vehicle Configuration section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `vehicle_configuration_name`
  - This data element describes the general configuration of this vehicle if applicable
* [INTEGER]   `cargo_body_type`
  - This data element identifies the primary cargo carrying capability of this vehicle if applicable. For more info on the codes, please look at V19 Cargo Body Type section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `cargo_body_type_name`
  - This data element describes the primary cargo carrying capability of this vehicle if applicable.
* [STRING]    `hazardous_material_involvement`
  - This data element identifies whether this vehicle was carrying hazardous materials. 1 No 2 Yes
* [INTEGER]   `hazardous_material_placard`
  - This data element identifies the presence of hazardous materials for this vehicle and whether this vehicle displayed a hazardous materials placard. 0 Not Applicable 1 No 2 Yes 8 Not Reported
* [INTEGER]   `hazardous_material_identification_number`
  - This data element identifies the 4-digit hazardous material identification number for this vehicle. 0000 Not Applicable xxxx Actual 4-Digit Number 8888 Not Reported
* [INTEGER]   `hazardous_material_class_number`
  - This data element identifies the single-digit hazardous material class number for this vehicle. 0 Not Applicable 1-9 Actual Number 88 Not Reported
* [STRING]    `release_of_hazardous_material_from_the_cargo_compartment`
  - This data element identifies whether any hazardous cargo was released from the cargo tank or compartment of this vehicle. 0 Not Applicable 1 No 2 Yes 8 Not Reported
* [STRING]    `bus_use`
  - This data element describes the common type of bus service this vehicle was being used as at the time of the crash or the primary use for the bus if not in service at the time of the crash. 00 Not a Bus 01 School Bus 04 Intercity Bus 05 Charter/Tour Bus 06 Transit/Commuter Bus 07 Shuttle Bus 08 Modified for Personal/Private Use 98 Not Reported 99 Unknown
* [INTEGER]   `special_use`
  - This data element identifies any special use associated with this vehicle at the time of the crash. For more info on the codes, please look at V22 Special Use section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `special_use_name`
  - This data element identifies any special use associated with this vehicle at the time of the crash.
* [STRING]    `emergency_motor_vehicle_use`
  - This data element identifies whether this vehicle was engaged in emergency use. Emergency Use indicates operation of any motor vehicle that is legally authorized by a government authority to respond to emergencies with or without the use of emergency warning equipment, such as a police vehicle, fire truck or ambulance while actually engaged in such response. -- No 0 Not Applicable -- Yes 2 Non-Emergency, Non-Transport 3 Non-Emergency Transport 4 Emergency Operation, Emergency Warning Equipment Not In Use 5 Emergency Operation, Emergency Warning Equipment In Use 6 Emergency Operation, Emergency Warning Equipment In Use Unknown 8 Not Reported 9 Unknown
* [INTEGER]   `travel_speed`
  - This data element records the speed the vehicle was traveling prior to the occurrence of the crash as reported by the investigating officer. 000 Stopped Motor Vehicle in Transport 001-151 Reported Speed Up to 151 mph -- Speed Greater than 96 mph 997 Speed Greater than 151 mph 998 Not Reported 999 Unknown
* [INTEGER]   `underride_override`
  - This data element identifies this vehicle’s involvement in an underride or override during the crash. For more info on the codes, please look at V25 Underride/Override section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `rollover`
  - This data element identifies this vehicle’s involvement in a rollover or overturn during the crash. Rollover is defined as any vehicle rotation of 90 degrees or more about any true longitudinal or lateral axis. Rollover can occur at any time during the crash. 0 No Rollover -- First Event 1 Rollover, Tripped by Object/Vehicle -- Subsequent Event 2 Rollover, Untripped 9 Rollover, Unknown Type
* [STRING]    `location_of_rollover`
  - This data element identifies the location of the trip point or start of this vehicle's roll. 0 No Rollover 1 On Roadway 2 On Shoulder 3 On Median/Separator 4 In Gore 5 On Roadside 6 Outside of Trafficway 7 In Parking Lane/Zone 9 Unknown
* [INTEGER]   `initial_contact_point`
  - This data element identifies the area on this vehicle that produced the first instance of injury to non-motorists or occupants of this vehicle, or that resulted in the first instance of damage to other property or to this vehicle. For more info on the codes, please look at V28A Initial Contact Point section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `extent_of_damage`
  - This data element records the amount of damage sustained by this vehicle as indicated in the case materials based on an operational damage scale. 0 No Damage 2 Minor Damage 4 Functional Damage 6 Disabling Damage 8 Not Reported 9 Unknown
* [STRING]    `vehicle_removal`
  - This data element describes the mode by which this vehicle left the scene of the crash. -- Driven Away -- Towed Away 2 Towed Due to Disabling Damage -- Abandoned/Left Scene 3 Towed Not Due to Disabling Damage -- Not Towed Away -- Abandoned/Left at Scene 5 Not Towed 8 Not Reported 9 Unknown
* [INTEGER]   `most_harmful_event`
  - This data element describes the event that resulted in the most severe injury or, if no injury, the greatest property damage involving this vehicle. For more info on the codes, please look at V32 Most Harmful Event section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `related_factors_vehicle_level_1`
  - This data element records factors related to this vehicle expressed by the investigating officer. For more info on the codes, please look at V33 Related Factors- Vehicle Level section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `related_factors_vehicle_level_2`
  - This data element records factors related to this vehicle expressed by the investigating officer. For more info on the codes, please look at V33 Related Factors- Vehicle Level section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `fire_occurrence`
  - This data element identifies whether a fire in any way related to the crash occurred in this vehicle. -- No Fire 0 No or Not Reported -- Fire Occurred in This Vehicle during Crash 1 Yes -- Fire Occurred in This Vehicle and Initiated Fire/Explosion in Another Vehicle
* [STRING]    `driver_presence`
  - This data element identifies whether a driver was present in this vehicle at the onset of the unstabilized situation. 0 No Driver Present/Not Applicable -- Driver Operated Vehicle 1 Yes -- No Driver -- Driverless (No Driver) -- Driver Left Scene -- Motor Vehicle not In-Transport (Parked/Stopped Off Roadway/ Working Motor Vehicle/In Motion Outside Trafficway, 2008 Only) -- Motor Vehicle not In-Transport (Parked/Stopped Off Roadway/Working/ In Motion Outside Trafficway, 2005-2007) 9 Unknown
* [INTEGER]   `drivers_license_state`
  - This element identifies the state of issue for the license held by this driver. For more info on the codes, please look at D5 Driver’s License State section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `drivers_zip_code`
  - This data element records the zip code of the driver’s address as listed in the case material. 00000 Not a Resident of U. S. or Territories xxxxx Actual Zip Code, Five Numeric 99997 No Driver Present/Unknown if Driver Present 99999 Unknown
* [INTEGER]   `non_cdl_license_status`
  - This data element identifies the status of the driver’s license at the time of the crash. For more info on the codes, please look at D7B Non-CDL License Status section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `non_cdl_license_type`
  - This data element identifies the type of license held by this driver at the time of the crash. 0 Not Licensed 1 Full Driver License 2 Intermediate Driver License 6 No Driver Present/Unknown if Driver Present 7 Learner’s Permit 8 Temporary License 9 Unknown License Type
* [INTEGER]   `commercial_motor_vehicle_license_status`
  - This data element indicates the status of the driver’s Commercial Driver’s License (CDL) if applicable. For more info on the codes, please look at D8 Commercial Motor Vehicle License Status section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `compliance_with_cdl_endorsements`
  - This data element identifies whether the vehicle driven at the time of the crash required endorsement(s) on a Commercial Driver’s License (CDL) and whether this driver was complying with the CDL endorsements. 0 No Endorsements Required For This Vehicle 1 Endorsement(s) Required, Complied With 2 Endorsement(s) Required, Not Complied With 3 Endorsement(s) Required, Compliance Unknown -- 7 No Driver Present/Unknown if Driver Present -- Not Reported 9 Unknown, if Required
* [STRING]    `license_compliance_with_class_of_vehicle`
  - This data element identifies the type of license possessed or not possessed by this driver for the class of vehicle being driven at the time of the crash. 0 Not Licensed 1 No License Required for This Class Vehicle 2 No Valid License for This Class Vehicle 3 Valid License for This Class Vehicle 6 No Driver Present/Unknown if Driver Present -- Not Reported 8 Unknown if CDL and/or CDL Endorsement Required for This Vehicle 9 Unknown
* [INTEGER]   `compliance_with_license_restrictions`
  - This data element indicates whether this driver was compliant with restrictions on their license. 0 No Restrictions or Not Applicable 1 Restrictions Complied With 2 Restrictions Not Complied With 3 Restrictions, Compliance Unknown 7 No Driver Present/Unknown if Driver Present -- Not Reported 9 Unknown
* [INTEGER]   `driver_height`
  - This data element identifies this driver's height (in inches). 24-107 Actual Height in Inches 998 No Driver Present/Unknown if Driver Present 999 Unknown
* [INTEGER]   `driver_weight`
  - This data element identifies this driver's weight (in pounds). 40-700 Actual Weight in Pounds 997 No Driver Present/Unknown if Driver Present 998 Other 999 Unknown
* [INTEGER]   `previous_recorded_crashes`
  - This data element records any previous crashes for this driver that occurred within five* years of the crash date. 00 None 01-97 Actual Value -- CDL Disqualified 98 Not Reported on Driving Record 99 Unknown 998 No Driver Present/Unknown if Driver Present
* [INTEGER]   `previous_recorded_suspensions_and_revocations`
  - This data element records any previous license suspensions or revocations for this driver that occurred within five* years of the crash date. 00 None 1-97 Actual Value -- CDL Disqualified 99 Unknown 998 No Driver Present/Unknown if Driver Present
* [INTEGER]   `previous_dwi_convictions`
  - This data element records any previous DWI convictions for this driver that occurred within five* years of the crash date. 00 None 01-97 Actual Value -- CDL Disqualified 99 Unknown 998 No Driver Present/Unknown if Driver Present
* [INTEGER]   `previous_speeding_convictions`
  - This data element records any previous speeding convictions for this driver that occurred within five* years of the crash date. 00 None 01-97 Actual Value -- CDL Disqualified 99 Unknown 998 No Driver Present/Unknown if Driver Present
* [INTEGER]   `previous_other_moving_violation_convictions`
  - This data element records any other previous moving violations or convictions for this driver that occurred within five* years of the crash date. 00 None 01-97 Actual Value -- CDL Disqualified 99 Unknown 998 No Driver Present/Unknown if Driver Present
* [INTEGER]   `month_of_first_crash_suspension_or_conviction`
  - This data element records the month of the first crash, suspension, or conviction for this driver that occurred within five* years of the crash date. For more info on the codes, please look at D19A Month of First Crash, Suspension or Conviction section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `year_of_first_crash_suspension_or_conviction`
  - This data element records the year of the first crash, suspension, or conviction for this driver that occurred within five* years of the crash date. 0000 No Record xxxx Actual Year 9998 No Driver Present/Unknown if Driver Present 9999 Unknown
* [INTEGER]   `month_of_last_crash_suspension_or_conviction`
  - This data element records the month of the last crash, suspension, or conviction for this driver that occurred within five* years of the crash date. For more info on the codes, please look at D20A Month of Last Crash, Suspension or Conviction section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `year_of_last_crash_suspension_or_conviction`
  - This data element records the year of the last crash, suspension, or conviction for this driver that occurred within five* years of the crash date. 0000 No Record xxxx Actual Year 9998 No Driver Present/Unknown if Driver Present 9999 Unknown
* [STRING]    `speeding_related`
  - This data element records whether the driver's speed was related to the crash as indicated by law enforcement. 0 No -- Yes 2 Yes, Racing 3 Yes, Exceeded Speed Limit 4 Yes, Too Fast for Conditions 5 Yes, Specifics Unknown 8 No Driver Present/Unknown if Driver Present 9 Unknown
* [INTEGER]   `related_factors_driver_level_1`
  - This data element records factors related to this driver expressed by the investigating officer. For more info on the codes, please look at D24 Related Factors- Driver Level section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `related_factors_driver_level_2`
  - This data element records factors related to this driver expressed by the investigating officer. For more info on the codes, please look at D24 Related Factors- Driver Level section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `related_factors_driver_level_3`
  - This data element records factors related to this driver expressed by the investigating officer. For more info on the codes, please look at D24 Related Factors- Driver Level section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `related_factors_driver_level_4`
  - This data element records factors related to this driver expressed by the investigating officer. For more info on the codes, please look at D24 Related Factors- Driver Level section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `trafficway_description`
  - This data element identifies the attribute that best describes the trafficway flow just prior to this vehicle’s critical precrash event. -- Non-Trafficway Area 0 Non-Trafficway or Driveway Access 1 Two-Way, Not Divided 2 Two-Way, Divided, Unprotected (Painted > 4 Feet) Median 3 Two-Way, Divided, Positive Median Barrier 4 One-Way Trafficway 5 Two-Way, Not Divided With a Continuous Left-Turn Lane 6 Entrance/Exit Ramp 8 Not Reported 9 Unknown
* [INTEGER]   `total_lanes_in_roadway`
  - This data element identifies the attribute that best describes the number of travel lanes just prior to this vehicle’s critical precrash event. For more info on the codes, please look at PC6 Total Lanes in Roadway section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `speed_limit`
  - This data element identifies the attribute that best represents the speed limit just prior to this vehicle’s critical precrash event. -- No Statutory Limit/Non-Trafficway Area 0 No Statutory Limit/Non-Trafficway or Driveway Access -- Speed Limit (mph) 5-80 Speed Limit (5 mph Increments) 98 Not Reported 99 Unknown
* [STRING]    `roadway_alignment`
  - This data element identifies the attribute that best represents the roadway alignment prior to this vehicle’s critical precrash event. -- Non-Trafficway Area 0 Non-Trafficway or Driveway Access 1 Straight 2 Curve Right 3 Curve Left 4 Curve – Unknown Direction 8 Not Reported 9 Unknown
* [STRING]    `roadway_grade`
  - This data element identifies the attribute that best represents the roadway grade prior to this vehicle’s critical precrash event. -- Non-Trafficway Area 0 Non-Trafficway or Driveway Access 1 Level 2 Grade, Unknown Slope 3 Hillcrest 4 Sag (Bottom) 5 Uphill 6 Downhill 8 Not Reported 9 Unknown
* [STRING]    `roadway_surface_type`
  - This data element identifies the attribute that best represents the roadway surface type prior to this vehicle’s critical precrash event. -- Non-Trafficway Area 0 Non-Trafficway or Driveway Access 1 Concrete 2 Blacktop, Bituminous, or Asphalt 3 Brick or Block 4 Slag, Gravel or Stone 5 Dirt 7 Other 8 Not Reported 9 Unknown
* [INTEGER]   `roadway_surface_condition`
  - This data element identifies the attribute that best represents the roadway surface condition prior to this vehicle’s critical precrash event. For more info on the codes, please look at PC11 Roadway Surface Condition section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `roadway_surface_condition_name`
  - This data element identifies the attribute that best represents the roadway surface condition prior to this vehicle’s critical precrash event.
* [INTEGER]   `traffic_control_device`
  - This data element identifies the attribute that best describes the traffic controls in the vehicle's environment just prior to this vehicle's critical precrash event. For more info on the codes, please look at PC12 Traffic Control Device section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `traffic_control_device_functioning`
  - This data element identifies the functionality of the traffic control device recorded for this vehicle in the data element “Traffic Control Device.” 0 No Controls 1 Device Not Functioning 2 Device Functioning – Functioning Improperly 3 Device Functioning Properly 8 Not Reported 9 Unknown
* [INTEGER]   `pre_event_movement_prior_to_recognition_of_critical_event`
  - This data element identifies the attribute that best describes this vehicle's activity prior to the driver's realization of an impending critical event or just prior to impact if the driver took no action or had no time to attempt any evasive maneuvers. For more info on the codes, please look at PC17 Pre-Event Movement (Prior To Recognition of Critical Event) section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `critical_event_precrash`
  - This data element identifies the attribute that best describes the critical event which made this crash imminent (i.e., something occurred which made the collision possible). For more info on the codes, please look at PC19 Critical Event- Precrash section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `critical_event_precrash_name`
  - This data element identifies the attribute that best describes the critical event which made this crash imminent (i.e., something occurred which made the collision possible).
* [INTEGER]   `attempted_avoidance_maneuver`
  - This data element identifies the attribute that best describes the movements/actions taken by this driver, within a critical crash envelope, in response to the “Critical Precrash Event.” For more info on the codes, please look at PC20 Attempted Avoidance Maneuver section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `attempted_avoidance_maneuver_name`
  - This data element identifies the attribute that best describes the movements/actions taken by this driver, within a critical crash envelope, in response to the “Critical Precrash Event.”
* [STRING]    `pre_impact_stability`
  - This data element identifies the attribute that best describes the stability of this vehicle after the “Critical Precrash Event,” but before the impact. -- No Driver Present 0 No Driver Present/Unknown if Driver Present 1 Tracking 2 Skidding Longitudinally – Rotation Less Than 30 Degrees 3 Skidding Laterally – Clockwise Rotation 4 Skidding Laterally – Counterclockwise Rotation 5 Skidding Laterally – Rotation Direction Unknown 7 Other Vehicle Loss-of-Control 9 Precrash Stability Unknown
* [INTEGER]   `pre_impact_location`
  - This data element identifies the attribute that best describes the location of this vehicle after the “Critical Precrash Event,” but before the impact. -- No Driver Present 0 No Driver Present/Unknown if Driver Present 1 Stayed In Original Travel Lane 2 Stayed On Roadway, But Left Original Travel Lane 3 Stayed On Roadway, Not Known if Left Original Travel Lane 4 Departed Roadway 5 Remained Off Roadway 6 Returned to Roadway 7 Entered Roadway 9 Unknown
* [INTEGER]   `crash_type`
  - This data element identifies the attribute that best describes the type of crash this vehicle was involved in based on the “First Harmful Event” and the precrash circumstances. For more info on the codes, please look at PC23 Crash Type section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `crash_type_name`
  - This data element identifies the attribute that best describes the type of crash this vehicle was involved in based on the “First Harmful Event” and the precrash circumstances. For graphic descriptions of possible values see Appendix A: PC23 Crash Type Diagram
* [INTEGER]   `fatalities_in_vehicle`
  - This data element records the number of fatalities that occurred in this vehicle. 01-99 Number of Fatalities that Occurred in the Vehicle.
* [STRING]    `driver_drinking`
  - This data element records whether the driver was drinking and is derived from data elements in the Vehicle and Person data files. 0 No Drinking 1 Drinking -- Unknown
* [TIMESTAMP] `timestamp_of_crash`
  - This data element records the date and time on which the crash occurred.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
