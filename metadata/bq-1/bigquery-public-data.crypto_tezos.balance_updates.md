# `crypto_tezos.balance_updates`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `level`
  - Block level where balance update is found
* [TIMESTAMP] `timestamp`
  - Block timestamp where balance update is found
* [STRING]    `block_hash`
  - Block hash where balance update is found
* [STRING]    `type`
  - The type of balance update: block if balance update is found in a block, operation_metadata if balance update is found in operation metadata, operation_result if balance update is found in operation results, internal_operation_result if balance update is found in internal operation result
* [STRING]    `operation_hash`
  - If type is operation, this field contains hash of the operation where the balance update is found
* [INTEGER]   `operation_group_index`
  - If type is operation, this field contains group index of the operation where the balance update is found
* [INTEGER]   `operation_index`
  - If type is operation, this field contains index of the operation where the balance update is found
* [INTEGER]   `content_index`
  - If type is operation, this field contains content index of the operation where the balance update is found
* [INTEGER]   `internal_operation_index`
  - If type is operation and balance update is found in an internal operation results, this field contains internal operation index of the operation where the balance update is found
* [INTEGER]   `balance_update_index`
  - Balance update index
* [STRING]    `status`
  - Status of the operation if balance update is associated with an operation
* [STRING]    `kind`
  - The kind of balance update. One of: contract, freezer
* [STRING]    `contract`
  - If kind is contract, this field contains contract address
* [STRING]    `delegate`
  - If kind is freezer, this field contains delegate address
* [INTEGER]   `change`
  - Balance change
* [STRING]    `category`
  - Balance update category if kind is freezer. One of: rewards, fees, deposits

-------------------------------------------------------------------------------
*Do not make edits above this line.*
