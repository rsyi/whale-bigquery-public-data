# `nhtsa_traffic_fatalities.safetyeq_2016`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `state_number`
  - This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). For more info on the codes, please look at <C1/V1/D1/PC1/P1/NM1 State Number> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `consecutive_number`
  - This data element is the unique case number assigned to each crash. It appears on each data file and is used to merge information from the data files together. xxxxxx Two Characters for State Code followed by Four Characters for Case Number
* [INTEGER]   `vehicle_number`
  - This data element is the consecutive number assigned to each vehicle in the case. This data element appears on each vehicle level data file and is used in conjunction with the ST_CASE data element to merge information from vehicle level data files. 000-999 Assigned Number of Motor Vehicle
* [INTEGER]   `person_number`
  - This data element is the consecutive number assigned to each person in the case (i.e., each occupant, pedestrian, or non-motorists involved in the crash). This data element appears on each person level data file and is used in conjunction with the ST_CASE data element (and sometimes the VEH_NO data element) to merge information from person level data files. 001-999 Assigned Person Number
* [STRING]    `non_motorist_safety_equipment_use`
  - This data element indicates the safety equipment that was used by this nonmotorist involved in the crash. 1 None Used 2 Helmet -- Reflective Equipment/Clothing (Jacket, Backpack, etc.) 3 Reflective Clothing (Jacket, Backpack, etc.) 4 Protective Pads (Elbows, Knees, Shins, etc.) 5 Lighting 7 Other Safety Equipment 8 Not Reported 9 Unknown if Used

-------------------------------------------------------------------------------
*Do not make edits above this line.*
