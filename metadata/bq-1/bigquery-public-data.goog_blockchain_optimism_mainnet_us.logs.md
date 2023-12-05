# `goog_blockchain_optimism_mainnet_us.logs`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `block_hash`
  - Hash of the block this log was created from.
* [INTEGER]   `block_number`
  - Number of the block this log was created from.
* [TIMESTAMP] `block_timestamp`
  - Unix timestamp when the log was added to the blockchain.
* [STRING]    `transaction_hash`
  - Hash of the transaction this log was created from.
* [INTEGER]   `transaction_index`
  - The transaction's index position in the block.
* [INTEGER]   `log_index`
  - The log's index position in the block.
* [STRING]    `address`
  - Address from which this log originated.
* [STRING]    `data`
  - Contains one or more 32-byte non-indexed arguments of the log.
* [STRING]    `topics`
  - Array of 0 to 4 32-byte hex of indexed log arguments.
* [BOOLEAN]   `removed`
  - Whether or not the log was orphaned off the main chain.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
