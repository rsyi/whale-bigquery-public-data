# `crypto_aptos_mainnet_us.modules`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `block_height`
  - The block height when the module was written/modified/deleted.
* [TIMESTAMP] `block_timestamp`
  - The timestamp of when the block that contains the module was written/modified/deleted.
* [RECORD]    `block_unixtimestamp`
  - The unix timestamp of when the block was finalized.
* [INTEGER]   `block_unixtimestamp.seconds`
  - The number of seconds since the unix epoch.
* [INTEGER]   `block_unixtimestamp.nanos`
  - The number of nanoseconds that have elapsed since the beginning of the second specified in the seconds field.
* [INTEGER]   `tx_version`
  - The transaction version when the written/modified/deleted.
* [STRING]    `tx_hash`
  - The hash of the transaction when the module was written/modified/deleted.
* [INTEGER]   `change_index`
  - The index of the change in the transaction where the module was written/modified/deleted.
* [BYTES]     `bytecode`
  - The bytecode associated with this module.
* [STRING]    `address`
  - A hex encoded 32 byte Aptos account address represented as a 64 character string, left-padded with zeros.
* [STRING]    `name`
  - The name of the module, may not be available if missing ABI info.
* [RECORD]    `friends`
  - Friends of the module, may be empty if missing ABI info.
* [STRING]    `friends.address`
  - A hex encoded 32 byte Aptos account address represented as a 64 character string, left-padded with zeros.
* [STRING]    `friends.name`
  - The name of the friend.
* [RECORD]    `exposed_functions`
  - Records of the public functions of the modules, may be empty if missing ABI info.
* [STRING]    `exposed_functions.name`
  - The name of the exposed function.
* [STRING]    `exposed_functions.visibility`
  - Move function visibility.  Should be `private`, `public`, or `friend`.
* [BOOLEAN]   `exposed_functions.is_entry`
  - Whether the function can be called as an entry function directly in a transaction.
* [RECORD]    `exposed_functions.generic_type_params`
  - The generic type parameters' constraints.
* [STRING]    `exposed_functions.generic_type_params.constraints`
  - The constraints associated with the parameter.
* [STRING]    `exposed_functions.params`
  - Parameters associated with the move function.
* [STRING]    `exposed_functions.return`
  - Return type of the function.
* [RECORD]    `structs`
  - Structs of the module, may be empty if missing ABI info.
* [STRING]    `structs.name`
  - Name of the struct in the module.
* [BOOLEAN]   `structs.is_native`
  - Whether the struct is native struct of the module.
* [STRING]    `structs.abilities`
  - Abilities associated with the struct in the module.
* [RECORD]    `structs.generic_type_params`
  - The generic type parameters' constraints.
* [STRING]    `structs.generic_type_params.constraints`
  - The constraints associated with the parameter.
* [BOOLEAN]   `structs.generic_type_params.is_phantom`
  - Whether represents a phantom field
* [RECORD]    `structs.fields`
  - Field names associated with the struct in the module.
* [STRING]    `structs.fields.name`
  - The name of the field.
* [STRING]    `structs.fields.type`
  - The field type.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
