# `san_francisco_bikeshare.bikeshare_station_status`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `station_id`
  - Unique identifier of a station
* [INTEGER]   `num_bikes_available`
  - Number of bikes available for rental
* [INTEGER]   `num_bikes_disabled`
  - Number of disabled bikes at the station. Vendors who do not want to publicize the number of disabled bikes or docks in their system can opt to omit station capacity (in station_information), num_bikes_disabled and num_docks_disabled. If station capacity is published then broken docks/bikes can be inferred (though not specifically whether the decreased capacity is a broken bike or dock)
* [INTEGER]   `num_docks_available`
  - Number of docks accepting bike returns
* [INTEGER]   `num_docks_disabled`
  - Number of empty but disabled dock points at the station. This value remains as part of the spec as it is possibly useful during development
* [BOOLEAN]   `is_installed`
  - 1/0 boolean - is the station currently on the street
* [BOOLEAN]   `is_renting`
  - 1/0 boolean - is the station currently renting bikes (even if the station is empty, if it is set to allow rentals this value should be 1)
* [BOOLEAN]   `is_returning`
  - 1/0 boolean - is the station accepting bike returns (if a station is full but would allow a return if it was not full then this value should be 1)
* [INTEGER]   `last_reported`
  - Integer POSIX timestamp indicating the last time this station reported its status to the backend
* [INTEGER]   `num_ebikes_available`
* [BOOLEAN]   `eightd_has_available_keys`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
