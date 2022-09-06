# `crypto_polygon.contracts`
`bq-1` | `bigquery-public-data`
Some transactions create smart contracts from their input bytes, and this smart contract is stored at a particular 20-byte address.
This table contains a subset of Polygon addresses that contain contract byte-code, as well as some basic analysis of that byte-code.
Data is exported using https://github.com/blockchain-etl/polygon-etl

## Column details
* [STRING]    `address`
  - Address of the contract
* [STRING]    `bytecode`
  - Bytecode of the contract
* [STRING]    `function_sighashes`
  - 4-byte function signature hashes
* [BOOLEAN]   `is_erc20`
  - Whether this contract is an ERC20 contract
* [BOOLEAN]   `is_erc721`
  - Whether this contract is an ERC721 contract
* [TIMESTAMP] `block_timestamp`
  - Timestamp of the block where this contract was created
* [INTEGER]   `block_number`
  - Block number where this contract was created
* [STRING]    `block_hash`
  - Hash of the block where this contract was created

-------------------------------------------------------------------------------
*Do not make edits above this line.*
