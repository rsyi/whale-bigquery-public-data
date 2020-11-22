# `crypto_zcash.blocks`
`bq-1` | `bigquery-public-data`
All blocks.
Data is exported using https://github.com/blockchain-etl/bitcoin-etl

## Column details
* [STRING]    `hash`
  - Hash of this block
* [INTEGER]   `size`
  - The size of block data in bytes
* [INTEGER]   `stripped_size`
  - The size of block data in bytes excluding witness data
* [INTEGER]   `weight`
  - Three times the base size plus the total size. https://github.com/bitcoin/bips/blob/master/bip-0141.mediawiki
* [INTEGER]   `number`
  - The number of the block
* [INTEGER]   `version`
  - Protocol version specified in block header
* [STRING]    `merkle_root`
  - The root node of a Merkle tree, where leaves are transaction hashes
* [TIMESTAMP] `timestamp`
  - Block creation timestamp specified in block header
* [DATE]      `timestamp_month`
  - Month of the block creation timestamp specified in block header
* [STRING]    `nonce`
  - Difficulty solution specified in block header
* [STRING]    `bits`
  - Difficulty threshold specified in block header
* [STRING]    `coinbase_param`
  - Data specified in the coinbase transaction of this block
* [INTEGER]   `transaction_count`
  - Number of transactions included in this block

-------------------------------------------------------------------------------
*Do not make edits above this line.*
