# `crypto_near_mainnet_us.transactions`
`bq-1` | `bigquery-public-data`
Transaction is the main way of interraction between a user and a blockchain. Transaction contains: Signer account ID, Receiver account ID, and Actions.

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
* [STRING]    `transaction_hash`
  - The transaction hash
* [INTEGER]   `index_in_chunk`
  - The index in the Chunk
* [STRING]    `signer_account_id`
  - An account on which behalf transaction is signed
* [STRING]    `signer_public_key`
  - An access key which was used to sign a transaction
* [INTEGER]   `nonce`
  - Nonce is used to determine order of transaction in the pool. It increments for a combination of `signer_id` and `public_key`
* [STRING]    `receiver_account_id`
  - Receiver account for this transaction
* [STRING]    `signature`
  - A signature of a hash of the Borsh-serialized Transaction
* [STRING]    `status`
  - Transaction status
* [STRING]    `converted_into_receipt_id`
  - Receipt ID that the transaction was converted.
* [INTEGER]   `receipt_conversion_gas_burnt`
  - Gas burnt in the receipt conversion
* [FLOAT]     `receipt_conversion_tokens_burnt`
  - Tokens burnt in the receipt conversion

-------------------------------------------------------------------------------
*Do not make edits above this line.*
