# `crypto_multiversx_mainnet_eu.receipts`
`bq-1` | `bigquery-public-data`
Transaction receipts.

## Column details
* [STRING]    `_id`
  - The receipt hash.
* [STRING]    `data`
  - A message with the reason why the receipt was generated.
* [STRING]    `sender`
  - The sender of the transaction that generated the receipt.
* [TIMESTAMP] `timestamp`
  - The timestamp of the block in which the receipt was generated.
* [STRING]    `txHash`
  - The hash of the transaction that generated the receipt.
* [STRING]    `value`
  - The amount of EGLD that was refunded/penalized from the transaction fee.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
