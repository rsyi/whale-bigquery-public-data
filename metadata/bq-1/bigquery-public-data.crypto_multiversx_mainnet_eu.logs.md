# `crypto_multiversx_mainnet_eu.logs`
`bq-1` | `bigquery-public-data`
Transaction logs.

## Column details
* [STRING]    `_id`
  - The unique identifier of the object that generated the log (transaction, smart contract result).
* [STRING]    `address`
  - The address in bech32 encoding. It can be the address of the smart contract that generated the log or the address of the transaction's receiver.
* [RECORD]    `events`
  - A list of events.
* [STRING]    `events.address`
  - The address in bech32 encoding. It can be the address of the smart contract that generated the event or the address of the transaction's receiver.
* [STRING]    `events.data`
  - The data field can contain information added by the smart contract that generated the event.
* [STRING]    `events.identifier`
  - The identifier of the event.
* [STRING]    `events.topics`
  - A list with extra information. They don't have a specific order because the smart contract is free to log anything that could be helpful.
* [NUMERIC]   `events.order`
  - The index of the event indicating the execution order.
* [STRING]    `events.additionalData`
  - Additional data captured by the event.
* [STRING]    `originalTxHash`
  - The hash of the initial transaction.
* [TIMESTAMP] `timestamp`
  - The timestamp of the block in which the log was generated.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
