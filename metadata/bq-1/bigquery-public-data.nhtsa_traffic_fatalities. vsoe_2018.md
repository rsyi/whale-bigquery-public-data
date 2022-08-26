# `nhtsa_traffic_fatalities. vsoe_2018`
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
* [INTEGER]   `vehicle_event_number`
  - This data element is the consecutive number assigned to each harmful and nonharmful event for this vehicle, in chronological order. 001-999 Vehicle Event Number
* [INTEGER]   `sequence_of_events`
  - This data element describes this event. A motor vehicle traffic crash is a series of events resulting from an unstabilized situation. This series of harmful and non-harmful events is recorded in chronological order based on the PAR narrative and diagram. For more info on the codes, please look at <V31 Sequence of Events> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `sequence_of_events_name`
  - This data element describes this event. A motor vehicle traffic crash is a series of events resulting from an unstabilized situation. This series of harmful and non-harmful events is recorded in chronological order based on the PAR narrative and diagram. For more info on the codes, please look at <V31 Sequence of Events> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `area_of_Impact_associated_with_the_event`
  - This data element identifies the impact point, if any, on this in-transport motor vehicle that produced property damage or personal injury in this event. For more info on the codes, please look at <C18 Area of Impact Associated with the Event> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `area_of_Impact_associated_with_the_event_name`
  - This data element identifies the impact point, if any, on this in-transport motor vehicle that produced property damage or personal injury in this event. For more info on the codes, please look at <C18 Area of Impact Associated with the Event> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315

-------------------------------------------------------------------------------
*Do not make edits above this line.*
