# `goog_blockchain_cronos_mainnet_us.decoded_events`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `block_hash`
  - Hash of the block this event was emitted on.
* [INTEGER]   `block_number`
  - Number of the block this event was emitted on.
* [TIMESTAMP] `block_timestamp`
  - Unix timestamp when the block was added to the blockchain.
* [STRING]    `transaction_hash`
  - Hash of the transaction this event was emitted on.
* [INTEGER]   `transaction_index`
  - The transaction's index position in the block.
* [INTEGER]   `log_index`
  - The event's index position in the transaction.
* [STRING]    `address`
  - Address from which this event originated.
* [STRING]    `event_hash`
  - Keccak hash of the event signature.
* [STRING]    `event_signature`
  - The function signature of the event.
* [STRING]    `topics`
  - The indexed topics of the event.
* [JSON]      `args`
  - Decoded event arguments serialized as a JSON array.
* [BOOLEAN]   `removed`
  - Whether or not the event was orphaned off the main chain.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
