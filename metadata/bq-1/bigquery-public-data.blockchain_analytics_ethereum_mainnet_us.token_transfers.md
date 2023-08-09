# `blockchain_analytics_ethereum_mainnet_us.token_transfers`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `block_hash`
  - Hash of the block this event was emitted from.
* [INTEGER]   `block_number`
  - Number of the block this event was emitted from.
* [TIMESTAMP] `block_timestamp`
  - Unix timestamp when the block was added to the blockchain.
* [STRING]    `transaction_hash`
  - Hash of the transaction this event was emitted from.
* [INTEGER]   `transaction_index`
  - The transaction's index position in the block.
* [INTEGER]   `event_index`
  - The event's index position in the block.
* [INTEGER]   `batch_index`
  - The transfer's position in the batch transfer event.
* [STRING]    `address`
  - Address from which this event originated.
* [STRING]    `event_type`
  - Token standard that matches the event.
* [STRING]    `event_hash`
  - Keccak hash of the event signature.
* [STRING]    `event_signature`
  - Function signature of the event.
* [STRING]    `operator_address`
  - Address of the transfer operator.
* [STRING]    `from_address`
  - Address of the previous owner of the token(s).
* [STRING]    `to_address`
  - Address of the new owner of the token(s).
* [STRING]    `token_id`
  - Identifier of the token(s) being transferred.
* [STRING]    `quantity`
  - Quantity of tokens being transferred.
* [BOOLEAN]   `removed`
  - Whether or not the event was orphaned off the main chain.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
