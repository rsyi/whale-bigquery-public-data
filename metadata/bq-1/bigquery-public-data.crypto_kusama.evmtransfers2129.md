# `crypto_kusama.evmtransfers2129`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `token_address`
  - ERC20 token address
* [STRING]    `from_address`
  - Address of the sender
* [STRING]    `to_address`
  - Address of the receiver
* [STRING]    `value`
  - Amount of tokens transferred (ERC20) / id of the token transferred (ERC721). Use safe_cast for casting to NUMERIC or FLOAT64
* [FLOAT]     `value_usd`
* [STRING]    `operator`
  - The address of an account/contract that is approved to make the transfer (ERC1155)
* [JSON]      `token_ids`
  - ids of the token transferred (ERC1155). Use safe_cast for casting to NUMERIC or FLOAT64.
* [JSON]      `token_values`
  - Amounts of token transferred (ERC1155).  Use safe_cast for casting to NUMERIC or FLOAT64
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
* [STRING]    `transfer_type`
  - Transfer Type (ERC20, ERC721)

-------------------------------------------------------------------------------
*Do not make edits above this line.*
