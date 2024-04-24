# `crypto_sui_mainnet_us.CHECKPOINT`
`bq-1` | `bigquery-public-data`
Partitioned by Integer range. Clustered by epoch & sequence_number.

## Column details
* [STRING]    `checkpoint_digest`
* [INTEGER]   `sequence_number`
* [INTEGER]   `epoch`
* [INTEGER]   `timestamp_ms`
* [STRING]    `previous_checkpoint_digest`
* [BOOLEAN]   `end_of_epoch`
* [NUMERIC]   `total_gas_cost`
* [NUMERIC]   `computation_cost`
* [NUMERIC]   `storage_cost`
* [NUMERIC]   `storage_rebate`
* [NUMERIC]   `non_refundable_storage_fee`
* [NUMERIC]   `total_transaction_blocks`
* [NUMERIC]   `total_transactions`
* [NUMERIC]   `total_successful_transaction_blocks`
* [NUMERIC]   `total_successful_transactions`
* [NUMERIC]   `network_total_transaction`
* [STRING]    `validator_signature`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
