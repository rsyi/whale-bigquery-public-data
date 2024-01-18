# `crypto_polkadot.extrinsics2091`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `hash`
  - Hash of extrinsic data -- because of account reaping, may not be unique
* [STRING]    `extrinsic_id`
  - Extrinsic ID of extrinsic
* [TIMESTAMP] `block_time`
  - Block timestamp of block that includes the extrinsic
* [INTEGER]   `block_number`
  - Block number that includes the extrinsic
* [STRING]    `block_hash`
  - Block hash of extrinsic
* [JSON]      `lifetime`
  - Lifetime of extrinsic
* [STRING]    `section`
  - Pallet/section of extrinsic
* [STRING]    `method`
  - Method of extrinsic pallet/section
* [JSON]      `params`
  - Parameters of extrinsic
* [FLOAT]     `fee`
  - Fee of extrinsic
* [INTEGER]   `weight`
  - Extrinsic weight (if available)
* [BOOLEAN]   `signed`
  - Whether extrinsic has been signed (true) or not (false)
* [STRING]    `signer_ss58`
  - SS58 Address of Signer of extrinsic, if signed
* [STRING]    `signer_pub_key`
  - Pub key of Signer of extrinsic
* [FLOAT]     `fee_usd`
  - Fee USD of extrinsic (if available)
* [BOOLEAN]   `status`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
