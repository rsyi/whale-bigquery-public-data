# `nhtsa_traffic_fatalities.nmimpair_2015`
`bq-1` | `bigquery-public-data`
This data file contains information about physical
impairments of people who are not occupants of motor vehicles. There is one record per
impairment and there is at least one record for each person who is not an occupant of a
motor vehicle.

## Column details
* [INTEGER]   `state_number`
  - This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). For more info on the codes, please look at <C1/V1/D1/PC1/P1/NM1 State Number> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `consecutive_number`
  - This data element is the unique case number assigned to each crash. It appears on each data file and is used to merge information from the data files together. xxxxxx Two Characters for State Code followed by Four Characters for Case Number
* [INTEGER]   `vehicle_number`
  - This data element is the consecutive number assigned to each vehicle in the case. This data element appears on each vehicle level data file and is used in conjunction with the ST_CASE data element to merge information from vehicle level data files. 000-999 Assigned Number of Motor Vehicle
* [INTEGER]   `person_number`
  - This data element is the consecutive number assigned to each person in the case (i.e., each occupant, pedestrian, or non-motorists involved in the crash). This data element appears on each person level data file and is used in conjunction with the ST_CASE data element (and sometimes the VEH_NO data element) to merge information from person level data files. 001-999 Assigned Person Number
* [INTEGER]   `condition_impairment_at_time_of_crash_non_motorist`
  - This data element identifies physical impairments to this non-motorist that may have contributed to the crash as identified by law enforcement. For more info on the codes, please look at <NM14 Condition (Impairment) at Time of Crash- Non-Motorist> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `condition_impairment_at_time_of_crash_non_motorist_name`
  - This data element identifies physical impairments to this non-motorist that may have contributed to the crash as identified by law enforcement.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
