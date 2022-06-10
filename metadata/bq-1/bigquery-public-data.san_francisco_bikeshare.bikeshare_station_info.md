# `san_francisco_bikeshare.bikeshare_station_info`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `station_id`
  - Unique identifier of a station.
* [STRING]    `name`
  - Public name of the station
* [STRING]    `short_name`
  - Short name or other type of identifier, as used by the data publisher
* [FLOAT]     `lat`
  - The latitude of station. The field value must be a valid WGS 84 latitude in decimal degrees format. See: http://en.wikipedia.org/wiki/World_Geodetic_System, https://en.wikipedia.org/wiki/Decimal_degrees
* [FLOAT]     `lon`
  - The longitude of station. The field value must be a valid WGS 84 longitude in decimal degrees format. See: http://en.wikipedia.org/wiki/World_Geodetic_System, https://en.wikipedia.org/wiki/Decimal_degrees
* [INTEGER]   `region_id`
  - ID of the region where station is located
* [STRING]    `rental_methods`
  - Array of enumerables containing the payment methods accepted at this station.  Current valid values (in CAPS) are: KEY (i.e. operator issued bike key / fob / card) CREDITCARD PAYPASS APPLEPAY ANDROIDPAY TRANSITCARD ACCOUNTNUMBER PHONE This list is intended to be as comprehensive at the time of publication as possible but is subject to change, as defined in File Requirements above
* [INTEGER]   `capacity`
  - Number of total docking points installed at this station, both available and unavailable
* [STRING]    `external_id`
* [BOOLEAN]   `eightd_has_key_dispenser`
* [BOOLEAN]   `has_kiosk`
* [GEOGRAPHY] `station_geom`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
