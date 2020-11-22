# `nhtsa_traffic_fatalities.violatn_2015`
`bq-1` | `bigquery-public-data`
This data file contains information about violations which were
charged to drivers. There is at least one record per in-transport motor vehicle. Each
violation is a separate record.

## Column details
* [INTEGER]   `state_number`
  - This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). For more info on the codes, please look at <C1/V1/D1/PC1/P1/NM1 State Number> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [INTEGER]   `consecutive_number`
  - This data element is the unique case number assigned to each crash. It appears on each data file and is used to merge information from the data files together. xxxxxx Two Characters for State Code followed by Four Characters for Case Number
* [INTEGER]   `vehicle_number`
  - This data element is the consecutive number assigned to each vehicle in the case. This data element appears on each vehicle level data file and is used in conjunction with the ST_CASE data element to merge information from vehicle level data files. 000-999 Assigned Number of Motor Vehicle
* [STRING]    `violations_charged`
  - This data element identifies all violations charged to this driver. For more info on the codes, please look at <D21 Violations Charged> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `violations_charged_name`
  - This data element identifies all violations charged to this driver. For more info on the codes, please look at <D21 Violations Charged> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315

-------------------------------------------------------------------------------
*Do not make edits above this line.*
