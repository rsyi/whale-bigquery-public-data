# `san_francisco_transit_muni.calendar`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `service_id`
  - Unique identifier for a set of dates when service is available for one or more routes
* [STRING]    `service_desc`
  - Text description of service category
* [BOOLEAN]   `sunday`
  - Indicates whether the service is valid for all Sundays operating on the agency is using normal schedules and fare categories
* [BOOLEAN]   `monday`
  - Indicates whether the service is valid for all Sundays operating on the agency is using normal schedules and fare categories
* [BOOLEAN]   `tuesday`
  - Indicates whether the service is valid for all Sundays operating on the agency is using normal schedules and fare categories
* [BOOLEAN]   `wednesday`
  - Indicates whether the service is valid for all Sundays operating on the agency is using normal schedules and fare categories
* [BOOLEAN]   `thursday`
  - Indicates whether the service is valid for all Sundays operating on the agency is using normal schedules and fare categories
* [BOOLEAN]   `friday`
  - Indicates whether the service is valid for all Sundays operating on the agency is using normal schedules and fare categories
* [BOOLEAN]   `saturday`
  - Indicates whether the service is valid for all Sundays operating on the agency is using normal schedules and fare categories
* [DATE]      `exceptions`
  - Specifies a particular date when this service is not available. This is typically during holidays, special events, etc. If applicable, the operating service for the day is indicated in replacement_service. Format for the date is YYYY-MM-DD
* [BOOLEAN]   `exception_type`
  - Indicates whether service is available on the date specified in the exceptions field. The following are valid values for this field:  - TRUE: Service will be operating during the date listed in the column exceptions -  FALSE: Service will not be operating during the date listed in the column exceptions

-------------------------------------------------------------------------------
*Do not make edits above this line.*
