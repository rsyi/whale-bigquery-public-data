# `crypto_aptos_mainnet_us.transactions`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `block_height`
  - The height of the block containing this transaction.
* [TIMESTAMP] `block_timestamp`
  - Timestamp of when the block containing this transaction was finalized.
* [RECORD]    `block_unixtimestamp`
  - The unix timestamp of when the block was finalized.
* [INTEGER]   `block_unixtimestamp.seconds`
  - The number of seconds since the unix epoch.
* [INTEGER]   `block_unixtimestamp.nanos`
  - The number of nanoseconds that have elapsed since the beginning of the second specified in the seconds field.
* [STRING]    `tx_type`
  - The type of the transaction, limited to `user`, `genesis`, `block_metadata`, and `state_checkpoint`.  No `pending` transactions are added.
* [INTEGER]   `tx_version`
  - An unique identifier for a transaction.
* [STRING]    `tx_hash`
  - A hash representing this transaction.
* [STRING]    `state_change_hash`
  - A hash representing the changes of the blockchain state after the transaction
* [STRING]    `event_root_hash`
  - The event root hash of the transaction.
* [STRING]    `state_checkpoint_hash`
  - A hash representing the state of the blockchain at the moment of this transaction.
* [INTEGER]   `gas_used`
  - The amount of computational resources consumed to process this transaction, measured in Octa (APT = Octa / 1E8).
* [BOOLEAN]   `success`
  - Whether the transaction was successful.
* [STRING]    `vm_status`
  - The VM status of the transaction; can be useful during failure.
* [STRING]    `accumulator_root_hash`
  - The root hash of the Merkle accumulator.
* [INTEGER]   `sequence_number`
  - Only applicable with `user` transactions, represents the `n` transaction committed by the account, and is incremented each time an account commits a transaction.  Can be used as an unique identifier for a transaction among a singular user.
* [INTEGER]   `max_gas_amount`
  - The maximum amount of gas that a sender is willing to pay for a transaction. Gas charges are equal to the base gas cost covered by computation and IO multiplied by the gas price. Gas costs also include storage with an Apt-fixed priced storage model. This is represented as Octas or units of 10E-8 Aptos utility tokens.
* [INTEGER]   `gas_unit_price`
  - The price per unit of gas that a sender is willing to pay to execute a transaction represented as Octa or units of 10E-8 utility tokens.
* [STRING]    `sender`
  - Sender is the address of the originator account for a transaction, represented as a 64 character hex string, left-padded with zeros.
* [INTEGER]   `num_events`
  - The number of events that occurred.  If null, no events can occur in that type of transaction, if 0 then no events occurred.
* [RECORD]    `num_changes`
  - The number of changes that occured, organized per change type.  The `total` field represents the total of all the different changes.
* [INTEGER]   `num_changes.total`
  - The total amount of changes to occur in this transaction.
* [INTEGER]   `num_changes.delete_module`
  - The total number of changes deleting modules occured.
* [INTEGER]   `num_changes.delete_resource`
  - The total number of changes deleting resources occured.
* [INTEGER]   `num_changes.delete_table_item`
  - The total number of changes deleting table items occured.
* [INTEGER]   `num_changes.write_module`
  - The total number of changes writing modules occured.
* [INTEGER]   `num_changes.write_resource`
  - The total number of changes writing resources occured.
* [INTEGER]   `num_changes.write_table_item`
  - The total number of changes writing table items occured.
* [TIMESTAMP] `expiration_timestamp`
  - Time that user transaction would expire, only applicable for `user` transactions.  Some timestamps far from the Unix epoch may be set to the maximum TIMESTAMP value for user transactions, whereas the column `expiration_unixtimestamp` should always have the correct precision.
* [RECORD]    `expiration_unixtimestamp`
  - The Unix timestamp that the user transaction would expire.  Only applicable for `user` transactions.
* [INTEGER]   `expiration_unixtimestamp.seconds`
  - The number of seconds since the unix epoch.
* [INTEGER]   `expiration_unixtimestamp.nanos`
  - The number of nanoseconds that have elapsed since the beginning of the second specified in the seconds field.
* [STRING]    `payload_type`
  - One of the following payload types: `entry_function`, `script`, `module_bundle`, `multisig`.
* [RECORD]    `payload`
  - The core content or instructions of the transactions, the payload indicates an action or set of actions to occur on the blockchain.
* [STRING]    `payload.function`
  - Applicable when type is `entry_function`. Entry function id is string representation of a entry function defined on-chain. The format {address}::{module name}::{function name}.  Both module name and function name are case-sensitive.  Addresses are represented as a 64 character hex string.
* [STRING]    `payload.entry_function_id_str`
* [STRING]    `payload.type_arguments`
  - Applicable when type is `entry_function` or `script`. Type arguments of the function.
* [STRING]    `payload.arguments`
  - Applicable when type is `entry_function` or `script`. Arguments of the function.
* [STRING]    `payload.execute_as`
  - A hex encoded 32 byte Aptos account address, address represented as a 64 character string, left-padded with zeroes.
* [RECORD]    `payload.code`
  - Applicable when type is `script_payload`, contains the bytecode and its ABI.
* [BYTES]     `payload.code.bytecode`
  - The bytecode of the code.
* [RECORD]    `payload.code.abi`
  - The application binary interface associated with the code.
* [STRING]    `payload.code.abi.name`
  - Name associated with the code.
* [STRING]    `payload.code.abi.visibility`
  - The visibility; should be `unspecified`, `private`, `public`, or `friend`.
* [BOOLEAN]   `payload.code.abi.is_entry`
  - Whether the code can be invoked by other users or contracts.
* [BOOLEAN]   `payload.code.abi.is_view`
  - Indicates the code is read only.
* [RECORD]    `payload.code.abi.generic_type_params`
  - The generic types associated with the different parameters.
* [STRING]    `payload.code.abi.generic_type_params.generics_types`
  - The generic types.
* [STRING]    `payload.code.abi.params`
  - The parameters applied.
* [STRING]    `payload.code.abi.return`
  - The return values.
* [STRING]    `payload.multisig_address`
  - The multisig address, applicable when payload type is `multisig`.
* [RECORD]    `payload.tx_payload`
  - Sometimes applicable when the payload type is `multisig`, containing additional payload.
* [STRING]    `payload.tx_payload.function`
  - Location of the function being called.
* [STRING]    `payload.tx_payload.type_arguments`
  - The types of the arguments.
* [STRING]    `payload.tx_payload.arguments`
  - The argument values.
* [INTEGER]   `num_signatures`
  - The number of signature records produced.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
