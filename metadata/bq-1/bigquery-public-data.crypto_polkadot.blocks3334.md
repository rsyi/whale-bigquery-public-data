# `crypto_polkadot.blocks3334`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `hash`
  - Block hash
* [STRING]    `parent_hash`
  - Block hash of parent
* [INTEGER]   `number`
  - Block number
* [STRING]    `state_root`
  - State root of block
* [STRING]    `extrinsics_root`
  - Extrinsics root of block
* [TIMESTAMP] `block_time`
  - Unix timestamp (UTC) of block (from set timestamp extrinsic)
* [STRING]    `author_ss58`
  - Author/Collator of block (ss58) using blocks SS58 Prefix
* [STRING]    `author_pub_key`
  - Author/Collator of block (public key) using blocks SS58 Prefix
* [INTEGER]   `spec_version`
  - Spec version of block
* [INTEGER]   `relay_block_number`
  - Relay chain block number
* [STRING]    `relay_state_root`
  - Relay chain state root
* [INTEGER]   `extrinsic_count`
  - Total number of events loaded into the events{paraid} table for this block
* [INTEGER]   `event_count`
  - Total number of events loaded into the events{paraid} table for this block
* [INTEGER]   `transfer_count`
  - Total number of transfers loaded into the transfer{paraid} table for this block
* [INTEGER]   `trace_count`
  - Total number of traces loaded into the traces{paraid} table for this block

-------------------------------------------------------------------------------
*Do not make edits above this line.*
