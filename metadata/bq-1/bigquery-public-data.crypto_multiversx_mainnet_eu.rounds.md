# `crypto_multiversx_mainnet_eu.rounds`
`bq-1` | `bigquery-public-data`
Rounds info.

## Column details
* [STRING]    `_id`
  - A unique identifier (opaque). Round number is kept in the `round` field.
* [BOOLEAN]   `blockWasProposed`
  - Whether a block was proposed and executed in this round.
* [NUMERIC]   `epoch`
  - The epoch the round belongs to.
* [NUMERIC]   `round`
  - The number of the round.
* [NUMERIC]   `shardId`
  - The shard ID of the round entry. Each round will ideally produce 4 entries in this index.
* [NUMERIC]   `signersIndexes`
  - An array that contains the indices of the validators that should sign the block from this round.
* [TIMESTAMP] `timestamp`
  - The timestamp of the round.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
