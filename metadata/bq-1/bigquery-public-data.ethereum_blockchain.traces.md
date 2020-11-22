# `ethereum_blockchain.traces`
`bq-1` | `bigquery-public-data`
Traces exported using Parity trace module https://wiki.parity.io/JSONRPC-trace-module.
Data is exported using https://github.com/medvedev1088/ethereum-etl


## Column details
* [STRING]    `transaction_hash`
  - Transaction hash where this trace was in
* [INTEGER]   `transaction_index`
  - Integer of the transactions index position in the block
* [STRING]    `from_address`
  - Address of the sender, null when trace_type is genesis or reward
* [STRING]    `to_address`
  - Address of the receiver if trace_type is call, address of new contract or null if trace_type is create, beneficiary address if trace_type is suicide, miner address if trace_type is reward, shareholder address if trace_type is genesis, WithdrawDAO address if trace_type is daofork
* [NUMERIC]   `value`
  - Value transferred in Wei
* [STRING]    `input`
  - The data sent along with the message call
* [STRING]    `output`
  - The output of the message call, bytecode of contract when trace_type is create
* [STRING]    `trace_type`
  - One of call, create, suicide, reward, genesis, daofork
* [STRING]    `call_type`
  - One of call, callcode, delegatecall, staticcall
* [STRING]    `reward_type`
  - One of block, uncle
* [INTEGER]   `gas`
  - Gas provided with the message call
* [INTEGER]   `gas_used`
  - Gas used by the message call
* [INTEGER]   `subtraces`
  - Number of subtraces
* [STRING]    `trace_address`
  - Comma separated list of trace address in call tree
* [STRING]    `error`
  - Error if message call failed. This field doesn't contain top-level trace errors.
* [INTEGER]   `status`
  - Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert)
* [TIMESTAMP] `block_timestamp`
  - Timestamp of the block where this trace was in
* [INTEGER]   `block_number`
  - Block number where this trace was in
* [STRING]    `block_hash`
  - Hash of the block where this trace was in

-------------------------------------------------------------------------------
*Do not make edits above this line.*
