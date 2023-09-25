# `goog_blockchain_optimism_mainnet_us.receipts`
`bq-1` | `bigquery-public-data`
"Corresponds to a transaction receipt in an EVM-compatible blockchain."

## Column details
* [STRING]    `block_hash`
  - Hash of the block in which this transaction was located.
* [STRING]    `transaction_hash`
  - Hash of the transaction.
* [INTEGER]   `transaction_index`
  - The transaction's index position in the block.
* [STRING]    `from_address`
  - Address of the sender.
* [STRING]    `to_address`
  - Address of the receiver.
* [STRING]    `contract_address`
  - Hexadecimal-encoded address of new contract or absent if no contract was created.
* [INTEGER]   `cumulative_gas_used`
  - Gas used by this and all preceding transactions in the block.
* [INTEGER]   `gas_used`
  - Gas used by this transaction alone.
* [INTEGER]   `effective_gas_price`
  - Actual value per gas deducted from the sender's account.
* [STRING]    `root`
  - Post-transaction state root.
* [INTEGER]   `status`
  - Either 1 (success) or 0 (failure).

-------------------------------------------------------------------------------
*Do not make edits above this line.*