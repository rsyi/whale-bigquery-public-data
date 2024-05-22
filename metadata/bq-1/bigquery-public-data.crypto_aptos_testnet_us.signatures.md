# `crypto_aptos_testnet_us.signatures`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `block_height`
  - The height of the block.
* [TIMESTAMP] `block_timestamp`
  - Timestamp of when the block was finalized.
* [RECORD]    `block_unixtimestamp`
  - The unix timestamp of when the block was finalized.
* [INTEGER]   `block_unixtimestamp.seconds`
  - The number of seconds since the unix epoch.
* [INTEGER]   `block_unixtimestamp.nanos`
  - The number of nanoseconds that have elapsed since the beginning of the second specified in the seconds field.
* [INTEGER]   `tx_version`
  - An unique identifier for a transaction.
* [STRING]    `tx_hash`
  - A hash representing this transaction.
* [INTEGER]   `threshold`
  - The number of required signatures, applicable with Multi-Ed25519 signatures
* [STRING]    `build_type`
  - Describes how the signature was built: `ed25519`, `multi_ed25519`, `multi_agent`, `fee_payer`, `single_sender`
* [RECORD]    `public_key`
  - The public key attached to the signature.
* [STRING]    `public_key.type`
  - The public key type: `unspecified`, `ed25519`, `secp256k1_ecdsa`, `secp256r1_ecdsa`.
* [STRING]    `public_key.value`
  - The hex value represents the public key.
* [INTEGER]   `public_key.index`
  - Applicable when part of a Multi-Ed25519
* [RECORD]    `signature`
  - The signature value attached to this signature.  If Null, the public key was a part of the transaction but did not sign.
* [STRING]    `signature.type`
  - The public key type: `unspecified`, `ed25519`, `secp256k1_ecdsa`, `webauthn`, `ZkId`.
* [STRING]    `signature.value`
  - The hex value representing the signature bytes.
* [INTEGER]   `signature.index`
  - Applicable when signature was part of a multi key signature
* [BOOLEAN]   `is_secondary`
  - Whether this signature was a secondary signature.  Null if not applicable.
* [BOOLEAN]   `is_fee_payer`
  - Whether this signature was a fee payer signature. Null if not applicable.
* [BOOLEAN]   `is_sender`
  - Whether this signature was the sender signature. Null if not applicable.
* [STRING]    `signer`
  - Address of the signer's account

-------------------------------------------------------------------------------
*Do not make edits above this line.*
