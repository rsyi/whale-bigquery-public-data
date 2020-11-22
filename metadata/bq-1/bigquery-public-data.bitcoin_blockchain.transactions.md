# `bitcoin_blockchain.transactions`
`bq-1` | `bigquery-public-data`
****NOTE: This dataset has been migrated to `bigquery-public-data.crypto_bitcoin`. Updates to the data are being sent to the new version of this dataset, whose schema is better aligned with our other cryptocurrency offerings. 

This version of the data is no longer being updated and will be removed within the next 15 days.

## Column details
* [INTEGER]   `timestamp`
* [STRING]    `transaction_id`
* [RECORD]    `inputs`
* [BYTES]     `inputs.input_script_bytes`
* [STRING]    `inputs.input_script_string`
* [STRING]    `inputs.input_script_string_error`
* [INTEGER]   `inputs.input_sequence_number`
* [STRING]    `inputs.input_pubkey_base58`
* [STRING]    `inputs.input_pubkey_base58_error`
* [RECORD]    `outputs`
* [INTEGER]   `outputs.output_satoshis`
* [BYTES]     `outputs.output_script_bytes`
* [STRING]    `outputs.output_script_string`
* [STRING]    `outputs.output_script_string_error`
* [STRING]    `outputs.output_pubkey_base58`
* [STRING]    `outputs.output_pubkey_base58_error`
* [STRING]    `block_id`
* [STRING]    `previous_block`
* [STRING]    `merkle_root`
* [INTEGER]   `nonce`
* [INTEGER]   `version`
* [INTEGER]   `work_terahash`
* [STRING]    `work_error`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
