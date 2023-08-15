# `goog_blockchain_ethereum_mainnet_us.transactions`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `block_hash`
  - Hash of the block in which this transaction was located.
* [INTEGER]   `block_number`
  - Number of the block in which this transaction was located.
* [TIMESTAMP] `block_timestamp`
  - Unix timestamp when the block was added to the blockchain.
* [STRING]    `transaction_hash`
  - Hash of the transaction.
* [INTEGER]   `transaction_index`
  - The transaction's index position in the block.
* [INTEGER]   `nonce`
  - Number of transactions made by the sender prior to this one.
* [STRING]    `from_address`
  - Address of the sender.
* [STRING]    `to_address`
  - Address of the receiver.
* [BIGNUMERIC] `value`
  - Value transferred in Wei. A decimal number represented as a BIGNUMERIC to preserve up to 128-bit numeric precision.
* [STRING]    `value_lossless`
  - Value transferred in Wei. A decimal number represented in STRING format to preserve full 256-bit numeric precision.
* [INTEGER]   `gas`
  - Quantity of gas units provided by the sender.
* [INTEGER]   `gas_price`
  - Price per gas unit provided by the sender in Wei.
* [STRING]    `input`
  - Data sent along with the transaction, with a maximum size of 32 bytes.
* [INTEGER]   `max_fee_per_gas`
  - Maximum fee per unit of gas for this transaction.
* [INTEGER]   `max_priority_fee_per_gas`
  - Maximum priority fee per unit of gas for this transaction.
* [INTEGER]   `transaction_type`
  - Type of the transaction.
* [INTEGER]   `chain_id`
  - Chain ID used in transaction signing.
* [RECORD]    `access_list`
  - List of addresses and storage keys that the transaction plans to access and has pre-paid gas for.
* [STRING]    `access_list.address`
  - Smart contract or wallet address.
* [STRING]    `access_list.storage_keys`
  - Storage keys for accessing the Merkle tree state.
* [STRING]    `r`
  - ECDSA signature r.
* [STRING]    `s`
  - ECDSA signature s.
* [STRING]    `v`
  - ECDSA signature v.
* [STRING]    `y_parity`
  - ECDSA signature y_parity.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
