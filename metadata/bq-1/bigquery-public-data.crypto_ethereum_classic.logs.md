# `crypto_ethereum_classic.logs`
`bq-1` | `bigquery-public-data`
Similar to the token_transfers table, the logs table contains data for smart contract events. However, it contains all log data, not only ERC20 token transfers.
This table is generally useful for reporting on any logged event type on the Ethereum blockchain.
Data is exported using https://github.com/medvedev1088/ethereum-etl

## Column details
* [INTEGER]   `log_index`
  - Integer of the log index position in the block
* [STRING]    `transaction_hash`
  - Hash of the transactions this log was created from
* [INTEGER]   `transaction_index`
  - Integer of the transactions index position log was created from
* [STRING]    `address`
  - Address from which this log originated
* [STRING]    `data`
  - Contains one or more 32 Bytes non-indexed arguments of the log
* [STRING]    `topics`
  - Indexed log arguments (0 to 4 32-byte hex strings). (In solidity: The first topic is the hash of the signature of the event (e.g. Deposit(address,bytes32,uint256)), except you declared the event with the anonymous specifier.)
* [TIMESTAMP] `block_timestamp`
  - Timestamp of the block where this log was in
* [INTEGER]   `block_number`
  - The block number where this log was in
* [STRING]    `block_hash`
  - Hash of the block where this log was in

-------------------------------------------------------------------------------
*Do not make edits above this line.*
