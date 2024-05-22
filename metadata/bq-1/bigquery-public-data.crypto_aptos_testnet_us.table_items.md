# `crypto_aptos_testnet_us.table_items`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `block_height`
  - The block height this table write/delete occurred during.
* [TIMESTAMP] `block_timestamp`
  - The timestamp of the block this table write/delete occurred during.
* [RECORD]    `block_unixtimestamp`
  - The unix timestamp of when the block was finalized.
* [INTEGER]   `block_unixtimestamp.seconds`
  - The number of seconds since the unix epoch.
* [INTEGER]   `block_unixtimestamp.nanos`
  - The number of nanoseconds that have elapsed since the beginning of the second specified in the seconds field.
* [INTEGER]   `tx_version`
  - The version of the transaction containing the change.
* [STRING]    `tx_hash`
  - The hash of the transaction containing the change.
* [INTEGER]   `tx_sequence_number`
  - Only applicable with changes occuring during a `user` transactions, represents the `n` transaction committed by the account, and is incremented each time an account commits a transaction.  Can be used as an unique identifier for a transaction among a singular user.
* [INTEGER]   `change_index`
  - The index of the change within the transaction in which this table item write/delete occurred.
* [STRING]    `change_type`
  - The type of change: `delete_table_item`, or `write_table_item`.
* [STRING]    `address`
  - A hex encoded 32 byte Aptos account address.  This is represented in a string as a 64 character hex string, left padded with zeros.
* [STRING]    `state_key_hash`
  - The state key hash.
* [RECORD]    `key`
  - The key when writing/deleting a table item.
* [STRING]    `key.name`
  - The key's name.
* [STRING]    `key.type`
  - The key's type.
* [RECORD]    `value`
  - The value when writing a table item, only applicable when change_type is `write_table_item`.
* [STRING]    `value.content`
  - The value's content.
* [STRING]    `value.type`
  - The value's type.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
