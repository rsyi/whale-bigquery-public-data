# `austin_311.311_service_requests-2021-11-12T14_28_57`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `unique_key`
  - The service request tracking number.
* [STRING]    `complaint_type`
* [STRING]    `complaint_description`
  - Service request type
* [STRING]    `owning_department`
  - Owning department of Service request type.
* [STRING]    `source`
  - Contact method Service request was received from. Mass entry requests are submitted by dept. in groups after work is completed.
* [STRING]    `status`
  - Service request status. Duplicate statuses indicate that issue had previously been reported recently.
* [TIMESTAMP] `status_change_date`
  - Date of last Service request status change. Status changes occur when service request moves from one status to another. I.E. new to open, open to closed.
* [TIMESTAMP] `created_date`
  - Date Service request was created.
* [TIMESTAMP] `last_update_date`
  - Date Service request was updated. Last date Service request received updates. Updates may include creation, status changes, or changes to data in Service request.
* [TIMESTAMP] `close_date`
  - Date Service request was closed.
* [STRING]    `incident_address`
  - Service location of Service request.
* [STRING]    `street_number`
  - Parsed location information. Street number.
* [STRING]    `street_name`
  - Parsed location information. Street name.
* [STRING]    `city`
  - Parsed location information. City.
* [INTEGER]   `incident_zip`
  - Parsed location information. Zip code.
* [STRING]    `county`
  - Parsed location information. County.
* [STRING]    `state_plane_x_coordinate`
  - State plane X coordinate.
* [FLOAT]     `state_plane_y_coordinate`
  - State plane Y coordinate.
* [FLOAT]     `latitude`
  - Service request location latitude coordinate.
* [FLOAT]     `longitude`
  - Service request location longitude coordinate.
* [STRING]    `location`
  - Service request location latitude and longitude coordinates.
* [INTEGER]   `council_district_code`
  - Council district corresponding to Service request location. Locations outside of the City of Austin jurisdiction will not have a council district.
* [STRING]    `map_page`
  - Service request location corresponding map page.
* [STRING]    `map_tile`
  - Service request location corresponding map tile.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
