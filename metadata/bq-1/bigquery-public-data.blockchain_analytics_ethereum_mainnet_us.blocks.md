# `blockchain_analytics_ethereum_mainnet_us.blocks`
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
  - Extra data of this block.
* [INTEGER]   `gas_limit`
  - Maximum gas allowed in this block.
* [INTEGER]   `gas_used`
  - Total gas used by all transactions in this block.
* [INTEGER]   `base_fee_per_gas`
  - Reserve price that transactions must pay for inclusion in this block.
* [STRING]    `mix_hash`
  - 32-byte hash which proves, when combined with the nonce, that a sufficient amount of computation has been carried out on this block.
* [STRING]    `nonce`
  - 8-byte integer in hexadecimal format. Used together with the mix hash to show the proof of work.
* [BIGNUMERIC] `difficulty`
  - Difficulty for this block.
* [BIGNUMERIC] `total_difficulty`
  - Accumulated difficulty of the chain until this block.
* [STRING]    `miner`
  - Address of the beneficiary to whom the mining rewards were given.
* [STRING]    `sha3_uncles`
  - SHA3 of the uncles data in the block.
* [INTEGER]   `transaction_count`
  - Number of transactions in the block.
* [STRING]    `transactions_root`
  - Root of the transaction trie of the block.
* [STRING]    `receipts_root`
  - Root of the receipts trie of the block.
* [STRING]    `state_root`
  - Root of the final state trie of the block.
* [STRING]    `logs_bloom`
  - Bloom filter for the logs of the block.
* [STRING]    `withdrawals_root`
  - Validator withdrawal root.
* [RECORD]    `withdrawals`
  - Validator withdrawals.
* [INTEGER]   `withdrawals.index`
  - Index of the withdrawal.
* [INTEGER]   `withdrawals.validator_index`
  - Index of the validator that generated withdrawal.
* [STRING]    `withdrawals.address`
  - Recipient address for withdrawal value.
* [BIGNUMERIC] `withdrawals.amount`
  - Value transferred by the withdrawal in Wei. A decimal number represented as a BIGNUMERIC to preserve up to 128-bit numeric precision.
* [STRING]    `withdrawals.amount_lossless`
  - Value transferred by the withdrawal in Wei. A decimal number represented in STRING format to preserve full 256-bit numeric precision.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
