# `crypto_near_mainnet_us.receipts` [view]
`bq-1` | `bigquery-public-data`
It's recomended to select only the columns and partitions (block_date) needed to avoid unecessary query costs. This view join the receipt details, the transaction that originated the receipt and the receipt execution outcome. Receipt: All cross-contract (we assume that each account lives in its own shard) communication in Near happens through Receipts. Receipts are stateful in a sense that they serve not only as messages between accounts but also can be stored in the account storage to await DataReceipts. Each receipt has a predecessor_id (who sent it) and receiver_id the current account.

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
* [INTEGER]   `index_in_chunk`
  - The index in the Chunk
* [STRING]    `receipt_kind`
  - There are 2 types of Receipt: ACTION and DATA. An ACTION receipt is a request to apply Actions, while a DATA receipt is a result of the application of these actions
* [STRING]    `receipt_id`
  - An unique id for the receipt
* [STRING]    `data_id`
  - An unique DATA receipt identifier
* [STRING]    `predecessor_account_id`
  - The account ID which issued a receipt. In case of a gas or deposit refund, the account ID is system
* [STRING]    `receiver_account_id`
  - The destination account ID
* [STRING]    `receipt`
  - Receipt details
* [STRING]    `originated_from_transaction_hash`
  - The transaction hash that originated the receipt
* [STRING]    `transaction_signer_account_id`
  - An account on which behalf the origin transaction is signed
* [STRING]    `transaction_signer_public_key`
  - An access key which was used to sign the origin transaction
* [STRING]    `transaction_status`
* [STRING]    `execution_outcome_executed_in_block_hash`
  - The execution outcome Block hash
* [RECORD]    `execution_outcome_receipt_ids`
  - The execution outcome Receipt IDs generated by the transaction or receipt
* [RECORD]    `execution_outcome_receipt_ids.list`
* [STRING]    `execution_outcome_receipt_ids.list.element`
* [FLOAT]     `execution_outcome_gas_burnt`
  - The execution outcome amount of the gas burnt by the given transaction or receipt
* [FLOAT]     `execution_outcome_tokens_burnt`
  - The execution outcome amount of tokens burnt corresponding to the burnt gas amount. This value does not always equal to the `gas_burnt` multiplied by the gas price, because the prepaid gas price might be lower than the actual gas price and it creates a deficit
* [STRING]    `execution_outcome_executor_account_id`
  - The execution outcome id of the account on which the execution happens. For transaction this is signer_id, for receipt this is receiver_id
* [STRING]    `execution_outcome_status`
  - The execution outcome status. Contains the result in case of successful execution

-------------------------------------------------------------------------------
*Do not make edits above this line.*