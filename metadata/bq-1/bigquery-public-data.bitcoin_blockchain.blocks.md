# `bitcoin_blockchain.blocks`
`bq-1` | `bigquery-public-data`
****NOTE: This dataset has been migrated to `bigquery-public-data.crypto_bitcoin`. Updates to the data are being sent to the new version of this dataset, whose schema is better aligned with our other cryptocurrency offerings. 

This version of the data is no longer being updated and will be removed within the next 15 days.

## Column details
* [STRING]    `block_id`
* [STRING]    `previous_block`
* [STRING]    `merkle_root`
* [INTEGER]   `timestamp`
* [INTEGER]   `difficultyTarget`
* [INTEGER]   `nonce`
* [INTEGER]   `version`
* [INTEGER]   `work_terahash`
* [STRING]    `work_error`
* [RECORD]    `transactions`
* [STRING]    `transactions.transaction_id`
* [RECORD]    `transactions.inputs`
* [BYTES]     `transactions.inputs.input_script_bytes`
* [STRING]    `transactions.inputs.input_script_string`
* [STRING]    `transactions.inputs.input_script_string_error`
* [INTEGER]   `transactions.inputs.input_sequence_number`
* [STRING]    `transactions.inputs.input_pubkey_base58`
* [STRING]    `transactions.inputs.input_pubkey_base58_error`
* [RECORD]    `transactions.outputs`
* [INTEGER]   `transactions.outputs.output_satoshis`
* [BYTES]     `transactions.outputs.output_script_bytes`
* [STRING]    `transactions.outputs.output_script_string`
* [STRING]    `transactions.outputs.output_script_string_error`
* [STRING]    `transactions.outputs.output_pubkey_base58`
* [STRING]    `transactions.outputs.output_pubkey_base58_error`
* [INTEGER]   `row_number`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
