# `crypto_ethereum.tokens`
`bq-1` | `bigquery-public-data`
Token data.
Data is exported using https://github.com/medvedev1088/ethereum-etl

## Column details
* [STRING]    `address`
  - The address of the ERC20 token
* [STRING]    `symbol`
  - The symbol of the ERC20 token
* [STRING]    `name`
  - The name of the ERC20 token
* [STRING]    `decimals`
  - The number of decimals the token uses. Use safe_cast for casting to NUMERIC or FLOAT64
* [STRING]    `total_supply`
  - The total token supply. Use safe_cast for casting to NUMERIC or FLOAT64
* [TIMESTAMP] `block_timestamp`
  - Timestamp of the block where this token was created
* [INTEGER]   `block_number`
  - Block number where this token was created
* [STRING]    `block_hash`
  - Hash of the block where this token was created

-------------------------------------------------------------------------------
*Do not make edits above this line.*
