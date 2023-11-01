# `crypto_near_mainnet_us.accounts` [view]
`bq-1` | `bigquery-public-data`
It's recomended to select only the columns and partitions (block_date) needed to avoid unecessary query costs. This view filters the receipt_actions table to have the latest account state based on action_kind CREATE_ACCOUNT, TRANSFER, and DELETE_ACCOUNT.

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
* [INTEGER]   `shard_id`
  - The shard ID of the Chunk
* [INTEGER]   `index_in_action_receipt`
  - The index in the ACTION receipt
* [STRING]    `receipt_id`
  - An unique id for the receipt
* [STRING]    `account_id`
  - The account ID
* [STRING]    `action_kind`
  - The action kind: CREATE_ACCOUNT, DELETE_ACCOUNT, TRANSFER
* [BOOLEAN]   `is_active`
  - Active Flag

-------------------------------------------------------------------------------
*Do not make edits above this line.*
