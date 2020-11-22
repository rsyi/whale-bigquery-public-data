# `crypto_bitcoin_cash.transactions`
`bq-1` | `bigquery-public-data`
All transactions.
Data is exported using https://github.com/blockchain-etl/bitcoin-etl


## Column details
* [STRING]    `hash`
  - The hash of this transaction
* [INTEGER]   `size`
  - The size of this transaction in bytes
* [INTEGER]   `virtual_size`
  - The virtual transaction size (differs from size for witness transactions)
* [INTEGER]   `version`
  - Protocol version specified in block which contained this transaction
* [INTEGER]   `lock_time`
  - Earliest time that miners can include the transaction in their hashing of the Merkle root to attach it in the latest block of the blockchain
* [STRING]    `block_hash`
  - Hash of the block which contains this transaction
* [INTEGER]   `block_number`
  - Number of the block which contains this transaction
* [TIMESTAMP] `block_timestamp`
  - Timestamp of the block which contains this transaction
* [DATE]      `block_timestamp_month`
  - Month of the block which contains this transaction
* [INTEGER]   `input_count`
  - The number of inputs in the transaction
* [INTEGER]   `output_count`
  - The number of outputs in the transaction
* [NUMERIC]   `input_value`
  - Total value of inputs in the transaction
* [NUMERIC]   `output_value`
  - Total value of outputs in the transaction
* [BOOLEAN]   `is_coinbase`
  - true if this transaction is a coinbase transaction
* [NUMERIC]   `fee`
  - The fee paid by this transaction
* [RECORD]    `inputs`
  - Transaction inputs
* [INTEGER]   `inputs.index`
  - 0-indexed number of an input within a transaction
* [STRING]    `inputs.spent_transaction_hash`
  - The hash of the transaction which contains the output that this input spends
* [INTEGER]   `inputs.spent_output_index`
  - The index of the output this input spends
* [STRING]    `inputs.script_asm`
  - Symbolic representation of the bitcoin's script language op-codes
* [STRING]    `inputs.script_hex`
  - Hexadecimal representation of the bitcoin's script language op-codes
* [INTEGER]   `inputs.sequence`
  - A number intended to allow unconfirmed time-locked transactions to be updated before being finalized; not currently used except to disable locktime in a transaction
* [INTEGER]   `inputs.required_signatures`
  - The number of signatures required to authorize the spent output
* [STRING]    `inputs.type`
  - The address type of the spent output
* [STRING]    `inputs.addresses`
  - Addresses which own the spent output
* [NUMERIC]   `inputs.value`
  - The value in base currency attached to the spent output
* [RECORD]    `outputs`
  - Transaction outputs
* [INTEGER]   `outputs.index`
  - 0-indexed number of an output within a transaction used by a later transaction to refer to that specific output
* [STRING]    `outputs.script_asm`
  - Symbolic representation of the bitcoin's script language op-codes
* [STRING]    `outputs.script_hex`
  - Hexadecimal representation of the bitcoin's script language op-codes
* [INTEGER]   `outputs.required_signatures`
  - The number of signatures required to authorize spending of this output
* [STRING]    `outputs.type`
  - The address type of the output
* [STRING]    `outputs.addresses`
  - Addresses which own this output
* [NUMERIC]   `outputs.value`
  - The value in base currency attached to this output

-------------------------------------------------------------------------------
*Do not make edits above this line.*
