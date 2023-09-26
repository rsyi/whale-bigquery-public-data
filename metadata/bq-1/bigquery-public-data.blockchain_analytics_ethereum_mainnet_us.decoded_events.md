# `blockchain_analytics_ethereum_mainnet_us.decoded_events`
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
* [INTEGER]   `log_index`
  - The event's index position in the block.
* [STRING]    `address`
  - Address from which this event originated.
* [STRING]    `event_hash`
  - Keccak hash of the event signature.
* [STRING]    `event_signature`
  - Function signature of the event.
* [STRING]    `topics`
  - The original indexed topics of the event.
* [JSON]      `args`
  - The decoded arguments of the event as a JSON array.
* [BOOLEAN]   `removed`
  - Whether or not the event was orphaned off the main chain.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
