# `crypto_near_mainnet_us.receipt_actions`
`bq-1` | `bigquery-public-data`
Action Receipt represents a request to apply actions on the receiver_id side. It could be derived as a result of a Transaction execution or another ACTION Receipt processing. Action kind can be: ADD_KEY, CREATE_ACCOUNT, DELEGATE_ACTION, DELETE_ACCOUNT, DELETE_KEY, DEPLOY_CONTRACT, FUNCTION_CALL, STAKE, TRANSFER

## Column details
* [DATE]      `block_date`
  - The date of the Block. Used to partition the table
* [INTEGER]   `block_height`
  - The height of the Block
* [INTEGER]   `block_timestamp`
  - The timestamp of the Block in nanoseconds
* [TIMESTAMP] `block_timestamp_utc`
  - The timestamp of the Block in UTC
* [STRING]    `block_hash`
  - The hash of the Block
* [STRING]    `chunk_hash`
  - The hash of the Chunk
* [INTEGER]   `shard_id`
  - The shard ID of the Chunk
* [INTEGER]   `index_in_action_receipt`
  - The index in the ACTION receipt
* [STRING]    `receipt_id`
  - An unique id for the receipt
* [STRING]    `args`
  - Arguments
* [STRING]    `receipt_predecessor_account_id`
  - The account ID which issued a receipt. In case of a gas or deposit refund, the account ID is system
* [STRING]    `action_kind`
  - The action kind: ADD_KEY, CREATE_ACCOUNT	, DELEGATE_ACTION, DELETE_ACCOUNT, DELETE_KEY, DEPLOY_CONTRACT, FUNCTION_CALL, STAKE, TRANSFER
* [STRING]    `receipt_receiver_account_id`
  - The destination account ID
* [BOOLEAN]   `is_delegate_action`
  - Flag for delegate action

-------------------------------------------------------------------------------
*Do not make edits above this line.*
