# `crypto_kusama.evmtxs2129`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `hash`
  - Hash of the transaction
* [INTEGER]   `nonce`
  - The number of transactions made by the sender prior to this one
* [INTEGER]   `transaction_index`
  - Integer of the transactions index position in the block
* [STRING]    `from_address`
  - Address of the sender
* [STRING]    `to_address`
  - Address of the receiver. null when its a contract creation transaction
* [NUMERIC]   `value`
  - Value transferred in Wei
* [INTEGER]   `gas`
  - Gas provided by the sender
* [INTEGER]   `gas_price`
  - Gas price provided by the sender in Wei
* [STRING]    `input`
  - The data sent along with the transaction
* [INTEGER]   `receipt_cumulative_gas_used`
  - The total amount of gas used when this transaction was executed in the block
* [INTEGER]   `receipt_gas_used`
  - The amount of gas used by this specific transaction alone
* [STRING]    `receipt_contract_address`
  - The contract address created, if the transaction was a contract creation, otherwise null
* [STRING]    `receipt_root`
  - 32 bytes of post-transaction stateroot (pre Byzantium)
* [INTEGER]   `receipt_status`
  - Either 1 (success) or 0 (failure) (post Byzantium)
* [TIMESTAMP] `block_timestamp`
  - Timestamp of the block where this transaction was in
* [INTEGER]   `block_number`
  - Block number where this transaction was in
* [STRING]    `block_hash`
  - EVM Hash of the block where this transaction was in
* [INTEGER]   `max_fee_per_gas`
  - Total fee that covers both base and priority fees
* [INTEGER]   `max_priority_fee_per_gas`
  - Fee given to miners to incentivize them to include the transaction
* [INTEGER]   `transaction_type`
  - Transaction type
* [INTEGER]   `receipt_effective_gas_price`
  - The actual value per gas deducted from the senders account. Replacement of gas_price after EIP-1559
* [FLOAT]     `fee`
  - The actual transaction fee (in ether, 10^18)
* [FLOAT]     `txn_saving`
  - Total fee saved from the amount the user was willing to pay for this txn (in ether, 10^18)
* [FLOAT]     `burned_fee`
  - The amunt burned from this txn (in ether, 10^18)
* [STRING]    `extrinsic_id`
  - Identifier of the extrinsic
* [STRING]    `extrinsic_hash`
  - Blake2b Hash of the extrinsic
* [STRING]    `method_id`
  - The 4 byte hash of function signature
* [STRING]    `signature`
  - The inferred function signature, if available
* [JSON]      `access_list`
  - The accessList specifies a list of addresses and storage keys (introduced in EIP-2929)
* [JSON]      `params`
  - The decoded input, if available

-------------------------------------------------------------------------------
*Do not make edits above this line.*
