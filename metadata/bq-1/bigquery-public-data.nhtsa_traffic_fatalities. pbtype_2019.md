# `nhtsa_traffic_fatalities. pbtype_2019`
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
* [INTEGER]   `person_number`
  - This data element is the consecutive number assigned to each person in the case (i.e., each occupant, pedestrian, or non-motorists involved in the crash). This data element appears on each person level data file and is used in conjunction with the ST_CASE data element (and sometimes the VEH_NO data element) to merge information from person level data files. 001-999 Assigned Person Number
* [INTEGER]   `person_type`
  - This data element describes the role of this person involved in the crash. For more info on the codes, please look at P7/NM7 Person Type section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `person_type_name`
  - This data element describes the role of this person involved in the crash. For more info on the codes, please look at P7/NM7 Person Type section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `age`
  - This data element identifies the person’s age, in years, with respect to the person's last birthday. 000 Less than One Year 001-120 Age of the Individual in Years 998 Not Reported 999 Unknown
* [STRING]    `age_name`
  - This data element identifies the person’s age, in years, with respect to the person's last birthday. 000 Less than One Year 001-120 Age of the Individual in Years 998 Not Reported 999 Unknown
* [STRING]    `sex`
  - This data element identifies the sex of the person involved in the crash. 1 Male 2 Female 8 Not Reported 9 Unknown
* [STRING]    `sex_name`
  - This data element identifies the sex of the person involved in the crash. 1 Male 2 Female 8 Not Reported 9 Unknown
* [STRING]    `marked_crosswalk_present`
  - This data element indicates if a marked crosswalk was present at the crash site. 0 None Noted 1 Yes 9 Unknown
* [STRING]    `marked_crosswalk_present_name`
  - This data element indicates if a marked crosswalk was present at the crash site. 0 None Noted 1 Yes 9 Unknown
* [STRING]    `sidewalk_present`
  - This data element indicates if a sidewalk was present at the crash site. 0 None Noted 1 Yes 9 Unknown
* [STRING]    `sidewalk_present_name`
  - This data element indicates if a sidewalk was present at the crash site. 0 None Noted 1 Yes 9 Unknown
* [STRING]    `school_zone`
  - This data element indicates if the crash occurred in a school zone. 0 None Noted 1 Yes 9 Unknown
* [STRING]    `school_zone_name`
  - This data element indicates if the crash occurred in a school zone. 0 None Noted 1 Yes 9 Unknown
* [INTEGER]   `crash_type_pedestrian`
  - This data element summarizes the circumstances of the crash for this pedestrian. For more info on the codes, please look at NM9-PB30 Crash Type – Pedestrian section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `crash_type_pedestrian_name`
  - This data element summarizes the circumstances of the crash for this pedestrian. For more info on the codes, please look at NM9-PB30 Crash Type – Pedestrian section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `crash_type_bicycle`
  - This data element summarizes the circumstances of the crash for this bicyclist. For more info on the codes, please look at NM9-PB30B Crash Type – Bicycle section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `crash_type_bicycle_name`
  - This data element summarizes the circumstances of the crash for this bicyclist. For more info on the codes, please look at NM9-PB30B Crash Type – Bicycle section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `crash_location_pedestrian`
  - This data element identifies where the pedestrian crash occurred with respect to an intersection. 1 At Intersection 2 Intersection-Related 3 Not At Intersection 4 Non-Trafficway Location 7 Not a Pedestrian 9 Unknown/Insufficient Information
* [STRING]    `crash_location_pedestrian_name`
  - This data element identifies where the pedestrian crash occurred with respect to an intersection. 1 At Intersection 2 Intersection-Related 3 Not At Intersection 4 Non-Trafficway Location 7 Not a Pedestrian 9 Unknown/Insufficient Information
* [STRING]    `crash_location_bicycle`
  - This data element identifies where the bicyclist crash occurred with respect to an intersection. 1 At Intersection 2 Intersection-Related 3 Not At Intersection 4 Non-Trafficway Location 7 Not a Cyclist 9 Unknown/Insufficient Information
* [STRING]    `crash_location_bicycle_name`
  - This data element identifies where the bicyclist crash occurred with respect to an intersection. 1 At Intersection 2 Intersection-Related 3 Not At Intersection 4 Non-Trafficway Location 7 Not a Cyclist 9 Unknown/Insufficient Information
* [STRING]    `pedestrian_position`
  - This data element identifies the position/location of the pedestrian with respect to the trafficway when contacted. 1 Intersection Area 2 Crosswalk Area 3 Travel Lane 4 Paved Shoulder/Bicycle Lane/Parking Lane 5 Sidewalk/Shared-Use Path/Driveway Access 6 Unpaved Right-of-Way 7 Non-Trafficway – Driveway 8 Non-Trafficway – Parking Lot/Other 9 Other/Unknown 77 Not a Pedestrian
* [STRING]    `pedestrian_position_name`
  - This data element identifies the position/location of the pedestrian with respect to the trafficway when contacted. 1 Intersection Area 2 Crosswalk Area 3 Travel Lane 4 Paved Shoulder/Bicycle Lane/Parking Lane 5 Sidewalk/Shared-Use Path/Driveway Access 6 Unpaved Right-of-Way 7 Non-Trafficway – Driveway 8 Non-Trafficway – Parking Lot/Other 9 Other/Unknown 77 Not a Pedestrian
* [STRING]    `bicyclist_position`
  - This data element identifies the position/location of the bicyclist with respect to the trafficway when contacted. 1 Travel Lane 2 Bicycle Lane/Paved Shoulder/Parking Lane 3 Sidewalk/Crosswalk/Driveway Access 4 Shared-Use Path 5 Non-Trafficway – Driveway 6 Non-Trafficway – Parking Lot/Other 7 Not a Cyclist 8 Other 9 Unknown
* [STRING]    `bicyclist_position_name`
  - This data element identifies the position/location of the bicyclist with respect to the trafficway when contacted. 1 Travel Lane 2 Bicycle Lane/Paved Shoulder/Parking Lane 3 Sidewalk/Crosswalk/Driveway Access 4 Shared-Use Path 5 Non-Trafficway – Driveway 6 Non-Trafficway – Parking Lot/Other 7 Not a Cyclist 8 Other 9 Unknown
* [STRING]    `pedestrian_initial_direction_of_travel`
  - This data element identifies the initial direction of travel of the pedestrian prior to being contacted in the crash. 1 Northbound 2 Eastbound 3 Southbound 4 Westbound 7 Not a Pedestrian 8 Not Applicable 9 Unknown Initial Direction of Travel
* [STRING]    `pedestrian_initial_direction_of_travel_name`
  - This data element identifies the initial direction of travel of the pedestrian prior to being contacted in the crash. 1 Northbound 2 Eastbound 3 Southbound 4 Westbound 7 Not a Pedestrian 8 Not Applicable 9 Unknown Initial Direction of Travel
* [STRING]    `bicyclist_initial_direction_of_travel`
  - This data element identifies the initial travel direction of the bicyclist with respect to the flow of traffic prior to being contacted in the crash. 1 With Traffic 2 Facing Traffic 3 Not Applicable 7 Not a Cyclist 9 Unknown
* [STRING]    `bicyclist_initial_direction_of_travel_name`
  - This data element identifies the initial travel direction of the bicyclist with respect to the flow of traffic prior to being contacted in the crash. 1 With Traffic 2 Facing Traffic 3 Not Applicable 7 Not a Cyclist 9 Unknown
* [STRING]    `motorist_initial_direction_of_travel`
  - This data element identifies the initial direction of travel of the motorist prior to being involved in a pedestrian crash. 1 Northbound 2 Eastbound 3 Southbound 4 Westbound 7 Not a Pedestrian 8 Not Applicable 9 Unknown Initial Direction of Travel
* [STRING]    `motorist_initial_direction_of_travel_name`
  - This data element identifies the initial direction of travel of the motorist prior to being involved in a pedestrian crash. 1 Northbound 2 Eastbound 3 Southbound 4 Westbound 7 Not a Pedestrian 8 Not Applicable 9 Unknown Initial Direction of Travel
* [STRING]    `motorist_maneuver`
  - This data element identifies if the motorist was engaged in a turning maneuver at an intersection prior to being involved in a pedestrian crash. The data element indicates the maneuver being made by the motorist at the time of a pedestrian collision. 1 Left Turn 2 Right Turn 3 Straight Through 7 Not a Pedestrian 8 Not Applicable 9 Unknown Motorist Maneuver
* [STRING]    `motorist_maneuver_name`
  - This data element identifies if the motorist was engaged in a turning maneuver at an intersection prior to being involved in a pedestrian crash. The data element indicates the maneuver being made by the motorist at the time of a pedestrian collision. 1 Left Turn 2 Right Turn 3 Straight Through 7 Not a Pedestrian 8 Not Applicable 9 Unknown Motorist Maneuver
* [STRING]    `intersection_leg`
  - The data element identifies the leg of the intersection where the pedestrian crash occurred. 1 Nearside 2 Farside 7 Not a Pedestrian 8 Not Applicable 9 Unknown
* [STRING]    `intersection_leg_name`
  - The data element identifies the leg of the intersection where the pedestrian crash occurred. 1 Nearside 2 Farside 7 Not a Pedestrian 8 Not Applicable 9 Unknown
* [STRING]    `pedestrian_scenario`
  - This data element identifies the location and travel directions of the motorist and pedestrian for those crashes that occur at intersections. This data element summarizes the movements of the pedestrian and motorist in an intersection area. For more info on the codes, please look at NM9-PB37 Pedestrian Scenario section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `pedestrian_scenario_name`
  - This data element identifies the location and travel directions of the motorist and pedestrian for those crashes that occur at intersections. This data element summarizes the movements of the pedestrian and motorist in an intersection area. For more info on the codes, please look at NM9-PB37 Pedestrian Scenario section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `crash_group_pedestrian`
  - This data element provides general groupings of the more specific individual Pedestrian Crash Types. For more info on the codes, please look at NM9-PB38 Crash Group – Pedestrian section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `crash_group_pedestrian_name`
  - This data element provides general groupings of the more specific individual Pedestrian Crash Types. For more info on the codes, please look at NM9-PB38 Crash Group – Pedestrian section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `crash_group_bicycle`
  - This data element provides general groupings of the more specific individual Bicyclist Crash Types. For more info on the codes, please look at NM9-PB38B Crash Group – Bicycle section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `crash_group_bicycle_name`
  - This data element provides general groupings of the more specific individual Bicyclist Crash Types. For more info on the codes, please look at NM9-PB38B Crash Group – Bicycle section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315

-------------------------------------------------------------------------------
*Do not make edits above this line.*
