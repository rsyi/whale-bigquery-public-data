# `crypto_near_mainnet_us.blocks`
`bq-1` | `bigquery-public-data`
A structure that represents an entire block in the NEAR blockchain. Block is the main entity in NEAR Protocol blockchain. Blocks are produced in NEAR Protocol every second.

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
* [STRING]    `prev_block_hash`
  - The hash of the previous Block
* [FLOAT]     `total_supply`
  - The total supply of the Block
* [FLOAT]     `gas_price`
  - The gas price of the Block
* [STRING]    `author_account_id`
  - The AccountId of the author of the Block

-------------------------------------------------------------------------------
*Do not make edits above this line.*
