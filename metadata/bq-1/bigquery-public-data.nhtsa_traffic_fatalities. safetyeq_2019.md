# `nhtsa_traffic_fatalities. safetyeq_2019`
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
* [STRING]    `nm_helmet`
  - This data element indicates if the non-motorist was wearing a safety helmet.
* [STRING]    `nm_helmet_name`
  - This data element indicates if the non-motorist was wearing a safety helmet.
* [STRING]    `nm_propad`
  - This data element indicates if the non-motorist was wearing padded, shaped attachments to protect specific areas of the body (e.g., elbows, knees, shins) from injury.
* [STRING]    `nm_propad_name`
  - This data element indicates if the non-motorist was wearing padded, shaped attachments to protect specific areas of the body (e.g., elbows, knees, shins) from injury.
* [STRING]    `nm_othpro`
  - This data element indicates if the non-motorist was using protective safety equipment other than a helmet or pads (e.g., eye wear/face shields, gloves, wrist guards).
* [STRING]    `nm_othpro_name`
  - This data element indicates if the non-motorist was using protective safety equipment other than a helmet or pads (e.g., eye wear/face shields, gloves, wrist guards).
* [STRING]    `nm_refclo`
  - This data element indicates if the non-motorist was wearing or carrying some type of reflective item (e.g., jacket, backpack, vest).
* [STRING]    `nm_refclo_name`
  - This data element indicates if the non-motorist was wearing or carrying some type of reflective item (e.g., jacket, backpack, vest).
* [STRING]    `nm_light`
  - This data element indicates if the non-motorist was using a light on his/her person or on a pedalcycle or personal conveyance for safety purposes, to include flashlights.
* [STRING]    `nm_light_name`
  - This data element indicates if the non-motorist was using a light on his/her person or on a pedalcycle or personal conveyance for safety purposes, to include flashlights.
* [STRING]    `nm_othpre`
  - This data element indicates if the non-motorist was using preventive safety equipment other than a reflective clothing/carried item or light (e.g., bicycle reflectors and flags, reflectors and triangles on a buggy, hi-glo orange clothing, rollerblade stoppers).
* [STRING]    `nm_othpre_name`
  - This data element indicates if the non-motorist was using preventive safety equipment other than a reflective clothing/carried item or light (e.g., bicycle reflectors and flags, reflectors and triangles on a buggy, hi-glo orange clothing, rollerblade stoppers).

-------------------------------------------------------------------------------
*Do not make edits above this line.*
