# `crypto_polkadot.transfers3367`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `event_id`
  - Event ID for the transfer
* [STRING]    `section`
  - Section/Pallet for the event
* [STRING]    `method`
  - Event method
* [STRING]    `extrinsic_id`
  - Extrinsic ID of the extrinsic which includes the event
* [STRING]    `extrinsic_hash`
  - Extrinsic Hash of the extrinsic which includes the event
* [TIMESTAMP] `block_time`
  - Block time of the block which includes the event
* [INTEGER]   `block_number`
  - Block number of the block which includes the event
* [STRING]    `block_hash`
  - Block hash of the block which includes the event
* [STRING]    `from_ss58`
  - SS58 Encoded address of the origin of the transfer
* [STRING]    `from_pub_key`
  - Pub key of the origin of the transfer
* [STRING]    `to_ss58`
  - SS58 Encoded address of the recipient of the transfer
* [STRING]    `to_pub_key`
  - Pub key of the recipient of the transfer
* [STRING]    `asset`
  - String representation of the transfer
* [FLOAT]     `price_usd`
  - Estimated USD value of 1 token of the transfer
* [FLOAT]     `amount_usd`
  - Estimated value of the transfer in USD
* [STRING]    `symbol`
  - Symbol of the asset, if available
* [INTEGER]   `decimals`
  - Decimals of the asset, if available
* [FLOAT]     `amount`
  - Decimalized version of the asset
* [NUMERIC]   `raw_amount`
  - Raw (non-decimalized) version of the amount of the asset being transferred

-------------------------------------------------------------------------------
*Do not make edits above this line.*
