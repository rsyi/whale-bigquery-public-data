# `san_francisco.311_service_requests`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `unique_key`
  - Unique case id
* [TIMESTAMP] `created_date`
  - The date and time when the service request was made
* [TIMESTAMP] `closed_date`
  - The date and time when the service request was closed
* [TIMESTAMP] `resolution_action_updated_date`
  - The date and time when the service request was last modified. For requests with status=closed, this will be the date the request was closed
* [STRING]    `status`
  - The current status of the service request.
* [STRING]    `status_notes`
  - Explanation of why status was changed to current state or more details on current status than conveyed with status alone
* [STRING]    `agency_name`
  - The agency responsible for fulfilling or otherwise addressing the service request.
* [STRING]    `category`
  - The Human readable name of the specific service request type (service_name)
* [STRING]    `complaint_type`
  - More specific description of the problem related to the Category
* [STRING]    `descriptor`
  - More specific description of the problem related to the Request Type
* [STRING]    `incident_address`
  - Human readable address or description of location
* [INTEGER]   `supervisor_district`
* [STRING]    `neighborhood`
* [STRING]    `location`
  - Latitude and longitude using the (WGS84) projection.
* [STRING]    `source`
  - How the service request was made
* [STRING]    `media_url`
  - Website URL
* [FLOAT]     `latitude`
  - Latitude using the (WGS84) projection.
* [FLOAT]     `longitude`
  - Longitude using the (WGS84) projection.
* [STRING]    `police_district`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
