# `goog_blockchain_tron_mainnet_us.transactions`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `block_hash`
  - Hash of the block in which this transaction was located.
* [TIMESTAMP] `block_timestamp`
  - Unix timestamp when the transaction was added to the blockchain.
* [STRING]    `transaction_hash`
  - Hash of the transaction.
* [INTEGER]   `transaction_index`
  - The transaction's index position in the block.
* [BIGNUMERIC] `nonce`
  - Number of transactions made by the sender prior to this one.
* [STRING]    `from_address`
  - Address of the sender.
* [STRING]    `to_address`
  - Address of the receiver.
* [RECORD]    `value`
  - Value transferred in Wei.
* [STRING]    `value.string_value`
  - Decimal value stored as a string.
* [BIGNUMERIC] `value.bignumeric_value`
  - Decimal value stored as a bignumeric.
* [STRING]    `input`
  - Data sent along with the transaction, with a maximum size of 32 bytes.
* [INTEGER]   `gas`
  - Quantity of gas units provided by the sender.
* [RECORD]    `gas_price`
  - Price per gas unit provided by the sender in Wei.
* [STRING]    `gas_price.string_value`
  - Decimal value stored as a string.
* [BIGNUMERIC] `gas_price.bignumeric_value`
  - Decimal value stored as a bignumeric.
* [INTEGER]   `max_fee_per_gas`
  - Maximum fee per unit of gas for this transaction.
* [INTEGER]   `max_priority_fee_per_gas`
  - Maximum priority fee per unit of gas for this transaction.
* [INTEGER]   `transaction_type`
  - Type of the transaction.
* [RECORD]    `access_list`
  - List of addresses and storage keys that the transaction plans to access and has pre-paid gas for.
* [STRING]    `access_list.address`
  - Address that a particular transaction will access.
* [STRING]    `access_list.storage_keys`
  - List of storage keys a particular transaction will access.
* [RECORD]    `r`
  - ECDSA signature r.
* [STRING]    `r.string_value`
  - Decimal value stored as a string.
* [BIGNUMERIC] `r.bignumeric_value`
  - Decimal value stored as a bignumeric.
* [RECORD]    `s`
  - ECDSA signature s.
* [STRING]    `s.string_value`
  - Decimal value stored as a string.
* [BIGNUMERIC] `s.bignumeric_value`
  - Decimal value stored as a bignumeric.
* [RECORD]    `v`
  - ECDSA signature v.
* [STRING]    `v.string_value`
  - Decimal value stored as a string.
* [BIGNUMERIC] `v.bignumeric_value`
  - Decimal value stored as a bignumeric.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
