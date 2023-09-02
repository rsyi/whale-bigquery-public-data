# `crypto_near_mainnet_us.receipt_origin`
`bq-1` | `bigquery-public-data`
Tracks the transaction that originated the receipt

## Column details
* [DATE]      `block_date`
  - The date of the Block. Used to partition the table
* [INTEGER]   `block_height`
  - The height of the Block
* [STRING]    `receipt_id`
  - An unique id for the receipt
* [STRING]    `data_id`
  - An unique DATA receipt identifier
* [STRING]    `receipt_kind`
  - There are 2 types of Receipt: ACTION and DATA. An ACTION receipt is a request to apply Actions, while a DATA receipt is a result of the application of these actions
* [STRING]    `originated_from_transaction_hash`
  - The transaction hash that originated the receipt

-------------------------------------------------------------------------------
*Do not make edits above this line.*
