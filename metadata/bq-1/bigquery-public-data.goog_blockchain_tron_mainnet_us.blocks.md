# `goog_blockchain_tron_mainnet_us.blocks`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `block_hash`
  - Hash of the block.
* [INTEGER]   `block_number`
  - Number of the block.
* [TIMESTAMP] `block_timestamp`
  - Unix timestamp when the block was added to the blockchain.
* [STRING]    `parent_hash`
  - Hash of the parent block.
* [INTEGER]   `size`
  - Size of this block in bytes.
* [STRING]    `extra_data`
  - Extra data of this block. Lowercase hex-encoded string prefixed with 0x.
* [INTEGER]   `gas_limit`
  - Maximum gas allowed in this block.
* [INTEGER]   `gas_used`
  - Total gas used by all transactions in this block.
* [INTEGER]   `base_fee_per_gas`
  - Reserve price that transactions must pay for inclusion in this block.
* [STRING]    `mix_hash`
  - 32-byte hash which proves, when combined with the nonce, that a sufficient amount of computation has been carried out on this block.
* [BIGNUMERIC] `nonce`
  - Used together with the mix hash to show the proof of work.
* [RECORD]    `difficulty`
  - Difficulty for this block.
* [STRING]    `difficulty.string_value`
  - Decimal value stored as a string.
* [BIGNUMERIC] `difficulty.bignumeric_value`
  - Decimal value stored as a bignumeric.
* [RECORD]    `total_difficulty`
  - Accumulated difficulty of the chain until this block.
* [STRING]    `total_difficulty.string_value`
  - Decimal value stored as a string.
* [BIGNUMERIC] `total_difficulty.bignumeric_value`
  - Decimal value stored as a bignumeric.
* [STRING]    `miner`
  - Address of the beneficiary to whom the mining rewards were given.
* [STRING]    `uncles_sha3`
  - SHA3 of the uncles data in the block.
* [STRING]    `uncles`
  - Array of uncle hashes.
* [STRING]    `transactions_root`
  - Root of the transaction trie of the block. Lowercase hex-encoded string prefixed with 0x.
* [STRING]    `receipts_root`
  - Root of the receipts trie of the block.
* [STRING]    `state_root`
  - Root of the final state trie of the block.
* [STRING]    `logs_bloom`
  - Bloom filter for the logs of the block.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
