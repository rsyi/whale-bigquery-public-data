# `crypto_near_mainnet_us.account_changes`
`bq-1` | `bigquery-public-data`
Describes how account's state has changed and the reason.

## Column details
* [DATE]      `block_date`
  - The date of the Block. Used to partition the table
* [INTEGER]   `block_height`
  - The height of the Block
* [INTEGER]   `block_timestamp`
  - The timestamp of the Block in nanoseconds
* [TIMESTAMP] `block_timestamp_utc`
  - The timestamp of the Block in UTC
* [STRING]    `block_hash`
  - The hash of the Block
* [STRING]    `chunk_hash`
  - The hash of the Chunk
* [INTEGER]   `index_in_block`
  - The index in the Block
* [STRING]    `affected_account_id`
  - Account ID affected by the change
* [STRING]    `caused_by_transaction_hash`
  - The transaction hash that caused the change
* [STRING]    `caused_by_receipt_id`
  - The receipt ID that caused the change
* [STRING]    `update_reason`
  - The update reason
* [FLOAT]     `affected_account_nonstaked_balance`
  - Non stacked balance
* [FLOAT]     `affected_account_staked_balance`
  - Stacked balance
* [FLOAT]     `affected_account_storage_usage`
  - Storage usage

-------------------------------------------------------------------------------
*Do not make edits above this line.*
