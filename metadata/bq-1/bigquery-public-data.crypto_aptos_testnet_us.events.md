# `crypto_aptos_testnet_us.events`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `block_height`
  - The block height this event occurred during.
* [TIMESTAMP] `block_timestamp`
  - The timestamp of when the block this event occurred during was finalized.
* [RECORD]    `block_unixtimestamp`
  - The unix timestamp of when the block was finalized.
* [INTEGER]   `block_unixtimestamp.seconds`
  - The number of seconds since the unix epoch.
* [INTEGER]   `block_unixtimestamp.nanos`
  - The number of nanoseconds that have elapsed since the beginning of the second specified in the seconds field.
* [INTEGER]   `tx_version`
  - The transaction version that this event occurred during.
* [STRING]    `tx_hash`
  - The transaction hash that this event occurred during.
* [INTEGER]   `tx_sequence_number`
  - Only applicable with changes occuring during a `user` transactions, represents the `n` transaction committed by the account, and is incremented each time an account commits a transaction.  Can be used as an unique identifier for a transaction among a singular user. 
* [INTEGER]   `event_index`
  - The index of the events within the transaction.
* [STRING]    `address`
  - A hex encoded 32 byte Aptos account address represented as a 64 character string, left-padded with zeros.
* [INTEGER]   `creation_num`
  - 64bit unsigned incremental integer for events on each address.
* [INTEGER]   `sequence_number`
  - Sequence number as an unsigned integer within an event.
* [STRING]    `event_type`
  - String representation of an on-chain Move type tag that is exposed in transaction payload. Values: `bool`, `u8`, `u16`, `u32`, `u64`, `u128`, `u256`, `address`, `signer`, vectors as `vector<{non-reference MoveTypeId}>`, and structs as `{address}::{module_name}::{struct_name}::<{generic types}>`.  Note addresses will be standardized to a 64 character string, left-padded with zeros.
* [JSON]      `data`
  - The event data.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
