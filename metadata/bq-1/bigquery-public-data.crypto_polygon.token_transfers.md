# `crypto_polygon.token_transfers`
`bq-1` | `bigquery-public-data`
The most popular type of transaction on the Polygon blockchain invokes a contract of type ERC20 to perform a transfer operation, moving some number of tokens from one 20-byte address to another 20-byte address.
This table contains the subset of those transactions and has further processed and denormalized the data to make it easier to consume for analysis of token transfer events.
Data is exported using https://github.com/blockchain-etl/polygon-etl


## Column details
* [STRING]    `token_address`
  - ERC20 token address
* [STRING]    `from_address`
  - Address of the sender
* [STRING]    `to_address`
  - Address of the receiver
* [STRING]    `value`
  - Amount of tokens transferred (ERC20) / id of the token transferred (ERC721). Use safe_cast for casting to NUMERIC or FLOAT64
* [STRING]    `transaction_hash`
  - Transaction hash
* [INTEGER]   `log_index`
  - Log index in the transaction receipt
* [TIMESTAMP] `block_timestamp`
  - Timestamp of the block where this transfer was in
* [INTEGER]   `block_number`
  - Block number where this transfer was in
* [STRING]    `block_hash`
  - Hash of the block where this transfer was in

-------------------------------------------------------------------------------
*Do not make edits above this line.*
