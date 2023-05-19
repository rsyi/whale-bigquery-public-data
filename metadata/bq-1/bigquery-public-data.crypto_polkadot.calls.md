# `crypto_polkadot.calls`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `relay_chain`
* [INTEGER]   `para_id`
* [STRING]    `id`
* [STRING]    `block_hash`
  - Block hash of extrinsic
* [INTEGER]   `block_number`
  - Block number that includes the extrinsic
* [TIMESTAMP] `block_time`
  - Block timestamp of block that includes the extrinsic
* [STRING]    `extrinsic_hash`
  - Hash of extrinsic data -- because of account reaping, may not be unique
* [STRING]    `extrinsic_id`
  - Extrinsic ID of extrinsic
* [STRING]    `extrinsic_section`
  - Pallet/section of extrinsic (top-level call)
* [STRING]    `extrinsic_method`
  - Method of extrinsic  (top-level call)
* [STRING]    `call_id`
  - Call ID of extrinsic
* [STRING]    `call_index`
  - The 2 bytes index of the call_section:call_method
* [STRING]    `call_section`
  - Pallet/section of call (top-level call)
* [STRING]    `call_method`
  - Method of call
* [JSON]      `call_args`
  - Args of call
* [JSON]      `call_args_def`
  - Args Definition of call
* [BOOLEAN]   `root`
  - Whether the call is root (top-level call)
* [BOOLEAN]   `leaf`
  - Whether the call is leaf (bottom-level call)
* [FLOAT]     `fee`
  - Fee of extrinsic
* [FLOAT]     `fee_usd`
  - Fee USD of extrinsic (if available)
* [INTEGER]   `weight`
  - Extrinsic weight (if available)
* [BOOLEAN]   `signed`
  - Whether extrinsic has been signed (true) or not (false)
* [STRING]    `signer_ss58`
  - SS58 Address of Signer of extrinsic, if signed
* [STRING]    `signer_pub_key`
  - Pub key of Signer of extrinsic
* [JSON]      `lifetime`
  - Lifetime of extrinsic

-------------------------------------------------------------------------------
*Do not make edits above this line.*
