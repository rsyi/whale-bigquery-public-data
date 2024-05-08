# `crypto_aptos_mainnet_us.resources`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `block_height`
  - The block height this resource write/delete occurred during.
* [TIMESTAMP] `block_timestamp`
  - The timestamp of the block this change occurred during.
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
  - The index of the change within the transaction.
* [STRING]    `address`
  - A hex encoded 32 byte Aptos account address.  This is represented in a string as a 64 character hex string, left padded with zeros.
* [STRING]    `state_key_hash`
  - The state key hash
* [STRING]    `change_type`
  - The type of change, either `delete_resource` or `write_resource`.
* [RECORD]    `struct_tag`
  - A struct tag representing the resource written.
* [STRING]    `struct_tag.address`
  - A hex encoded 32 byte Aptos account address represented as a 64 character string, left-padded with zeros.
* [STRING]    `struct_tag.module`
  - Module of the struct tag
* [STRING]    `struct_tag.name`
  - The name of the struct tag
* [STRING]    `struct_tag.generic_type_params`
  - List of the generic type parameters
* [STRING]    `type_str`
  - String representing the type of the resource.
* [JSON]      `resource`
  - Applicable when type is `write_resource`, the data representing the resource.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
