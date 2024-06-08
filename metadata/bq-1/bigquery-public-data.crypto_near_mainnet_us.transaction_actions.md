# `crypto_near_mainnet_us.transaction_actions`
`bq-1` | `bigquery-public-data`
Each transaction can have one or multiple Actions, which are the actual operations to be performed on the Receiver account. Action kind can be: ADD_KEY, CREATE_ACCOUNT, DELEGATE_ACTION, DELETE_ACCOUNT, DELETE_KEY, DEPLOY_CONTRACT, FUNCTION_CALL, STAKE, TRANSFER

## Column details
* [DATE]      `block_date`
  - The date of the Block. Used to partition the table
* [INTEGER]   `block_height`
  - The height of the Block
* [INTEGER]   `block_timestamp`
  - The timestamp of the Block in nanoseconds
* [TIMESTAMP] `block_timestamp_utc`
  - The timestamp of the Block in UTC
* [STRING]    `transaction_hash`
  - The transaction hash
* [STRING]    `transaction_status`
  - Transaction status
* [STRING]    `converted_into_receipt_id`
  - Receipt ID that the transaction was converted.
* [STRING]    `signer_account_id`
  - An account on which behalf transaction is signed
* [STRING]    `signer_public_key`
  - An access key which was used to sign a transaction
* [STRING]    `receiver_account_id`
  - Receiver account for this transaction
* [INTEGER]   `index_in_transaction`
  - The index in the transaction actions
* [STRING]    `action_kind`
  - The action kind: ADD_KEY, CREATE_ACCOUNT	, DELEGATE_ACTION, DELETE_ACCOUNT, DELETE_KEY, DEPLOY_CONTRACT, FUNCTION_CALL, STAKE, TRANSFER
* [STRING]    `args`
  - Arguments

-------------------------------------------------------------------------------
*Do not make edits above this line.*
