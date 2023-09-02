# `crypto_near_mainnet_us.receipt_details`
`bq-1` | `bigquery-public-data`
All cross-contract (we assume that each account lives in its own shard) communication in Near happens through Receipts. Receipts are stateful in a sense that they serve not only as messages between accounts but also can be stored in the account storage to await DataReceipts. Each receipt has a predecessor_id (who sent it) and receiver_id the current account. 

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
* [INTEGER]   `index_in_chunk`
  - The index in the Chunk
* [STRING]    `receipt_kind`
  - There are 2 types of Receipt: ACTION and DATA. An ACTION receipt is a request to apply Actions, while a DATA receipt is a result of the application of these actions
* [STRING]    `receipt_id`
  - An unique id for the receipt
* [STRING]    `data_id`
  - An unique DATA receipt identifier
* [STRING]    `predecessor_account_id`
  - The account ID which issued a receipt. In case of a gas or deposit refund, the account ID is system
* [STRING]    `receiver_account_id`
  - The destination account ID
* [STRING]    `receipt`
  - Receipt details

-------------------------------------------------------------------------------
*Do not make edits above this line.*
