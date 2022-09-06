# `crypto_band.blocks`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `block_height`
* [STRING]    `block_timestamp`
* [TIMESTAMP] `block_timestamp_truncated`
* [STRING]    `block_hash`
* [STRING]    `proposer_address`
* [STRING]    `last_commit_hash`
* [STRING]    `data_hash`
* [STRING]    `validators_hash`
* [STRING]    `next_validators_hash`
* [STRING]    `consensus_hash`
* [STRING]    `app_hash`
* [STRING]    `last_results_hash`
* [STRING]    `evidence_hash`
* [RECORD]    `signatures`
* [INTEGER]   `signatures.block_id_flag`
* [STRING]    `signatures.validator_address`
* [TIMESTAMP] `signatures.timestamp`
* [RECORD]    `signatures.signatures`
* [INTEGER]   `signatures.signatures.block_id_flag`
* [STRING]    `signatures.signatures.validator_address`
* [TIMESTAMP] `signatures.signatures.timestamp`
* [STRING]    `signatures.signatures.signature`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
