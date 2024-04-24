# `crypto_sui_mainnet_us.TRANSACTION`
`bq-1` | `bigquery-public-data`
Partitioned by Integer range. Clustered by transaction_digest.


## Column details
* [STRING]    `transaction_digest`
* [INTEGER]   `checkpoint`
* [INTEGER]   `epoch`
* [INTEGER]   `timestamp_ms`
* [STRING]    `sender`
* [STRING]    `transaction_kind`
* [BOOLEAN]   `is_system_txn`
* [BOOLEAN]   `is_sponsored_tx`
* [INTEGER]   `transaction_count`
* [BOOLEAN]   `execution_success`
* [INTEGER]   `input`
* [INTEGER]   `shared_input`
* [INTEGER]   `gas_coins`
* [INTEGER]   `created`
* [INTEGER]   `mutated`
* [INTEGER]   `deleted`
* [INTEGER]   `transfers`
* [INTEGER]   `split_coins`
* [INTEGER]   `merge_coins`
* [INTEGER]   `publish`
* [INTEGER]   `upgrade`
* [INTEGER]   `others`
* [INTEGER]   `move_calls`
* [STRING]    `packages`
* [STRING]    `gas_owner`
* [STRING]    `gas_object_id`
* [INTEGER]   `gas_object_sequence`
* [STRING]    `gas_object_digest`
* [NUMERIC]   `gas_budget`
* [NUMERIC]   `total_gas_cost`
* [NUMERIC]   `computation_cost`
* [NUMERIC]   `storage_cost`
* [NUMERIC]   `storage_rebate`
* [NUMERIC]   `non_refundable_storage_fee`
* [NUMERIC]   `gas_price`
* [STRING]    `raw_transaction`
* [BOOLEAN]   `has_zklogin_sig`
* [BOOLEAN]   `has_upgraded_multisig`
* [JSON]      `transaction_json`
* [JSON]      `effects_json`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
