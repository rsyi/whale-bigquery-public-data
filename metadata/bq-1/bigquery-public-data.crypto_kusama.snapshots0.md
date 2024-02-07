# `crypto_kusama.snapshots0`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `chain_name`
* [TIMESTAMP] `ts`
  - timestamp when the snapshot is taken
* [INTEGER]   `block_number`
  - block_number when the snapshot is taken
* [STRING]    `block_hash`
  - block_hash when the snapshot is taken
* [STRING]    `address_ss58`
  - ss58 of the snaptshot state address if available
* [STRING]    `address_pubkey`
  - pubkey of the snaptshot state address if available
* [STRING]    `section`
  - section of the snapshot
* [STRING]    `storage`
  - storag of the snapshot
* [STRING]    `track`
  - optional identifier for the snapshot state
* [STRING]    `track_val`
  - optional val associated with track
* [JSON]      `kv`
  - generic snapshot value from the key
* [JSON]      `pv`
  - generic snapshot value from storage
* [STRING]    `source`
  - source that generates this snapshot

-------------------------------------------------------------------------------
*Do not make edits above this line.*
