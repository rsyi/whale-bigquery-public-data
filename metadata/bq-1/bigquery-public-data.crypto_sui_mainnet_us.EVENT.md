# `crypto_sui_mainnet_us.EVENT`
`bq-1` | `bigquery-public-data`
Partitioned by Integer range. Clustered by transaction_digest & event_index.

## Column details
* [STRING]    `transaction_digest`
* [INTEGER]   `event_index`
* [INTEGER]   `checkpoint`
* [INTEGER]   `epoch`
* [INTEGER]   `timestamp_ms`
* [STRING]    `sender`
* [STRING]    `package`
* [STRING]    `module`
* [STRING]    `event_type`
* [STRING]    `bcs`
* [JSON]      `event_json`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
