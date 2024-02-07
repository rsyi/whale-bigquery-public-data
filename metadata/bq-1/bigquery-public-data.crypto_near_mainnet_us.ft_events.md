# `crypto_near_mainnet_us.ft_events`
`bq-1` | `bigquery-public-data`
NEAR Fungible Tokens event logs.

## Column details
* [DATE]      `block_date`
  - The date of the Block. Used to partition the table
* [INTEGER]   `block_height`
  - The height of the Block
* [INTEGER]   `block_timestamp`
  - The timestamp of the Block
* [TIMESTAMP] `block_timestamp_utc`
  - The timestamp of the Block in UTC
* [STRING]    `block_hash`
  - The hash of the Block
* [STRING]    `chunk_hash`
  - The hash of the Chunk
* [INTEGER]   `shard_id`
  - The shard ID of the Chunk
* [STRING]    `standard`
  - The fungible tokens standard. e.g. nep141. 
* [STRING]    `receipt_id`
  - An unique id for the receipt
* [STRING]    `contract_account_id`
  - The contract account ID
* [STRING]    `affected_account_id`
  - Account ID affected by the change
* [STRING]    `involved_account_id`
  - Account ID involved
* [STRING]    `delta_amount`
  - The delta amount
* [STRING]    `cause`
  - The cause of the change
* [STRING]    `status`
  - Execution status. Contains the result in case of successful execution
* [STRING]    `event_memo`
  - The event log memo
* [STRING]    `event_index`
  - The event log index
* [STRING]    `token_id`
  - The token ID

-------------------------------------------------------------------------------
*Do not make edits above this line.*
