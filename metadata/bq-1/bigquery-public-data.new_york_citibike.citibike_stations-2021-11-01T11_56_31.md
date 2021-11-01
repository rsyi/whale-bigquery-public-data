# `new_york_citibike.citibike_stations-2021-11-01T11_56_31`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `station_id`
  - Unique identifier of a station.
* [STRING]    `name`
  - Public name of the station.
* [STRING]    `short_name`
  - Short name or other type of identifier, as used by the data publisher.
* [FLOAT]     `latitude`
  - The latitude of station. The field value must be a valid WGS 84 latitude in decimal degrees format.
* [FLOAT]     `longitude`
  - The longitude of station. The field value must be a valid WGS 84 longitude in decimal degrees format.
* [INTEGER]   `region_id`
  - ID of the region where station is located.
* [STRING]    `rental_methods`
  - Array of enumerables containing the payment methods accepted at this station.
* [INTEGER]   `capacity`
  - ANumber of total docking points installed at this station, both available and unavailable.
* [BOOLEAN]   `eightd_has_key_dispenser`
* [INTEGER]   `num_bikes_available`
  - Number of bikes available for rental.
* [INTEGER]   `num_bikes_disabled`
  - Number of disabled bikes at the station.
* [INTEGER]   `num_docks_available`
  - Number of docks accepting bike returns.
* [INTEGER]   `num_docks_disabled`
  - Number of empty but disabled dock points at the station.
* [BOOLEAN]   `is_installed`
  - Is the station currently on the street?
* [BOOLEAN]   `is_renting`
  - Is the station currently renting bikes?
* [BOOLEAN]   `is_returning`
  - Is the station accepting bike returns?
* [BOOLEAN]   `eightd_has_available_keys`
* [DATETIME]  `last_reported`
  - Timestamp indicating the last time this station reported its status to the backend, in NYC local time.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
