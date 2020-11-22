# `san_francisco_transit_muni.fares`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `fare_id`
  - Unique identifier a fare class.
* [STRING]    `rider_id`
  - Unique identifier a rider category. Rider categories are used to assign different pricing to different groups of individuals
* [STRING]    `rider_desc`
  - Text description of the rider category
* [NUMERIC]   `price`
  - Contains the fare price, in USD
* [STRING]    `payment_method`
  - Indicates when the fare must be paid. The following are valid values for this field: -  during: Indicates the fare is paid when riders board -  before: Indicates fare must be paid before riders board
* [STRING]    `transfers_permitted`
  - Specifies the number of transfers permitted on this fare.  -  0: No transfers are permitted on this fare. -  1: One transfer is permitted on this fare. -  2: Two transfers are permitted on this fare. -  NULL: Unlimited transfers are permitted on this fare.
* [INTEGER]   `transfer_duration`
  - Specifies the length of time, in seconds, before a transfer expires. When used with a transfers_permitted value of 0, the transfer_duration field indicates how long a ticket is valid for a fare where no transfers are allowed.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
