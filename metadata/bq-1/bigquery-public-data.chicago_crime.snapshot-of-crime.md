# `chicago_crime.snapshot-of-crime`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `unique_key`
  - Unique identifier for the record.
* [STRING]    `case_number`
  - The Chicago Police Department RD Number (Records Division Number), which is unique to the incident.
* [TIMESTAMP] `date`
  - Date when the incident occurred. this is sometimes a best estimate.
* [STRING]    `block`
  - The partially redacted address where the incident occurred, placing it on the same block as the actual address.
* [STRING]    `iucr`
  - The Illinois Unifrom Crime Reporting code. This is directly linked to the Primary Type and Description. See the list of IUCR codes at https://data.cityofchicago.org/d/c7ck-438e.
* [STRING]    `primary_type`
  - The primary description of the IUCR code.
* [STRING]    `description`
  - The secondary description of the IUCR code, a subcategory of the primary description.
* [STRING]    `location_description`
  - Description of the location where the incident occurred.
* [BOOLEAN]   `arrest`
  - Indicates whether an arrest was made.
* [BOOLEAN]   `domestic`
  - Indicates whether the incident was domestic-related as defined by the Illinois Domestic Violence Act.
* [INTEGER]   `beat`
  - Indicates the beat where the incident occurred. A beat is the smallest police geographic area – each beat has a dedicated police beat car. Three to five beats make up a police sector, and three sectors make up a police district. The Chicago Police Department has 22 police districts. See the beats at https://data.cityofchicago.org/d/aerh-rz74.
* [INTEGER]   `district`
  - Indicates the police district where the incident occurred. See the districts at https://data.cityofchicago.org/d/fthy-xz3r.
* [INTEGER]   `ward`
  - The ward (City Council district) where the incident occurred. See the wards at https://data.cityofchicago.org/d/sp34-6z76.
* [INTEGER]   `community_area`
  - Indicates the community area where the incident occurred. Chicago has 77 community areas. See the community areas at https://data.cityofchicago.org/d/cauq-8yn6.
* [STRING]    `fbi_code`
  - Indicates the crime classification as outlined in the FBI's National Incident-Based Reporting System (NIBRS). See the Chicago Police Department listing of these classifications at http://gis.chicagopolice.org/clearmap_crime_sums/crime_types.html.
* [FLOAT]     `x_coordinate`
  - The x coordinate of the location where the incident occurred in State Plane Illinois East NAD 1983 projection. This location is shifted from the actual location for partial redaction but falls on the same block.
* [FLOAT]     `y_coordinate`
  - The y coordinate of the location where the incident occurred in State Plane Illinois East NAD 1983 projection. This location is shifted from the actual location for partial redaction but falls on the same block.
* [INTEGER]   `year`
  - Year the incident occurred.
* [TIMESTAMP] `updated_on`
  - Date and time the record was last updated.
* [FLOAT]     `latitude`
  - The latitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.
* [FLOAT]     `longitude`
  - The longitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.
* [STRING]    `location`
  - The location where the incident occurred in a format that allows for creation of maps and other geographic operations on this data portal. This location is shifted from the actual location for partial redaction but falls on the same block.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
