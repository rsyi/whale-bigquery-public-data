# `san_francisco_sffd_service_calls.sffd_service_calls`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `call_number`
  - A unique 9-digit number assigned by the 911 Dispatch Center (DEM) to this call. These number are used for both Police and Fire calls
* [STRING]    `unit_id`
  - Unit Identifier. For example E01 for Engine 1 or T01 for Truck 1.
* [INTEGER]   `incident_number`
  - A unique 8-digit number assigned by DEM to this Fire incident.
* [STRING]    `call_type`
  - Type of call the incident falls into. See the list below.
* [DATE]      `call_date`
  - Date the call is received at the 911 Dispatch Center. Used for reporting purposes.
* [DATE]      `watch_date`
  - Watch date when the call is received. Watch date starts at 0800 each morning and ends at 0800 the next day.
* [DATETIME]  `received_timestamp`
  - Date and time of call is received at the 911 Dispatch Center.
* [DATETIME]  `entry_timestamp`
  - Date and time the 911 operator submits the entry of the initical call information into the CAD system
* [DATETIME]  `dispatch_timestamp`
  - Date and time the 911 operator dispatches this unit to the call.
* [DATETIME]  `response_timestamp`
  - Date and time this unit acknowledges the dispatch and records that the unit is en route to the location of the call.
* [DATETIME]  `on_scene_timestamp`
  - Date and time the unit records arriving to the location of the incident
* [DATETIME]  `transport_timestamp`
  - If this unit is an ambulance, date and time the unit begins the transport unit arrives to hospital
* [DATETIME]  `hospital_timestamp`
  - If this unit is an ambulance, date and time the unit arrives to the hospital.
* [STRING]    `call_final_disposition`
  - Disposition of the call (Code). For example TH2: Transport to Hospital - Code 2, FIR: Resolved by Fire Department
* [DATETIME]  `available_timestamp`
  - Date and time this unit is not longer assigned to this call and it is available for another dispatch.
* [STRING]    `address`
  - Address of midblock point associated with incident (obfuscated address to protect caller privacy)
* [STRING]    `city`
  - City of incident
* [STRING]    `zipcode_of_incident`
  - Zipcode of incident
* [STRING]    `battalion`
  - Emergency Response District (There are 9 Fire Emergency Response Districts)
* [STRING]    `station_area`
  - Fire Station First Response Area associated with the address of the incident
* [STRING]    `box`
  - Fire box associated with the address of the incident. A box is the smallest area used to divide the City. Each box is associated with a unique unit dispatch order. The City is divided into more than 2,400 boxes.
* [STRING]    `original_priority`
  - Initial call priority (Code 2: Non-Emergency or Code 3:Emergency).
* [STRING]    `priority`
  - Call priority (Code 2: Non-Emergency or Code 3:Emergency).
* [INTEGER]   `final_priority`
  - Final call priority (Code 2: Non-Emergency or Code 3:Emergency).
* [BOOLEAN]   `als_unit`
  - Does this unit includes ALS (Advance Life Support) resources? Is there a paramedic in this unit?
* [STRING]    `call_type_group`
  - Call types are divided into four main groups: Fire, Alarm, Potential Life Threatening and Non Life Threatening.
* [INTEGER]   `number_of_alarms`
  - Number of alarms associated with the incident. This is a number between 1 and 5.
* [STRING]    `unit_type`
  - Unit type
* [INTEGER]   `unit_sequence_in_call_dispatch`
  - A number that indicates the order this unit was assigned to this call
* [STRING]    `fire_prevention_district`
  - Bureau of Fire Prevention District associated with this address
* [STRING]    `supervisor_district`
  - Supervisor District associated with this address
* [STRING]    `row_id`
  - Unique identifier used for managing data updates. It is the concatenation of Call Number and Unit ID separated by a dash
* [FLOAT]     `latitude`
  - Latitude of the address
* [FLOAT]     `longitude`
  - Longitude of the address
* [STRING]    `neighborhood_name`
  - Text name of the neighborhood in which the incident occurred
* [GEOGRAPHY] `location_geom`
  - Latitude and longitude of address obfuscated either to the midblock, intersection or call box

-------------------------------------------------------------------------------
*Do not make edits above this line.*
