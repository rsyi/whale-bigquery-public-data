# `crypto_near_mainnet_us.chunks`
`bq-1` | `bigquery-public-data`
A structure that represents a chunk in the NEAR blockchain. Chunk of a Block is a part of a Block from a Shard. The collection of Chunks of the Block forms the NEAR Protocol Block. Chunk contains all the structures that make the Block: Transactions, Receipts, and Chunk Header.

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
* [STRING]    `signature`
  - The signature of the Chunk
* [FLOAT]     `gas_limit`
  - The gas limit of the Chunk
* [FLOAT]     `gas_used`
  - The amount of gas spent on computations of the Chunk
* [STRING]    `author_account_id`
  - The AccountId of the author of the Chunk

-------------------------------------------------------------------------------
*Do not make edits above this line.*
