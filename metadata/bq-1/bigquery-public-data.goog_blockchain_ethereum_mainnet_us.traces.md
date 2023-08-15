# `goog_blockchain_ethereum_mainnet_us.traces`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `block_hash`
  - Hash of the block this trace was created from.
* [INTEGER]   `block_number`
  - Number of the block this trace was created from.
* [TIMESTAMP] `block_timestamp`
  - Unix timestamp when the block was added to the blockchain.
* [STRING]    `transaction_hash`
  - Hash of the transaction.
* [INTEGER]   `transaction_index`
  - The transaction's index position in the block.
* [STRING]    `trace_type`
  - Trace type. One of "create", "suicide", "call" or "reward".
* [INTEGER]   `trace_address`
  - A sequence of indices that uniquely identifies this trace within the call tree. Available only for transaction-scoped traces.
* [INTEGER]   `subtrace_count`
  - Number of subtraces of this trace.
* [RECORD]    `action`
  - Action being carried out by this trace.
* [STRING]    `action.from_address`
  - Address of the sender. Null for "suicide" and "reward" traces.
* [STRING]    `action.to_address`
  - Address of the receiver. Null for "suicide" and "reward" traces.
* [STRING]    `action.call_type`
  - Trace call type. One of "call", "callcode", "staticcall" or "delegatecall". Available only for "call" traces.
* [INTEGER]   `action.gas`
  - Amount of gas provided by the sender.
* [STRING]    `action.input`
  - Input sent along with the transaction. Available only for "call" traces.
* [BIGNUMERIC] `action.value`
  - Value transferred by this trace in Wei. A decimal number represented as a BIGNUMERIC to preserve up to 128-bit numeric precision. Available only for "call" traces.
* [STRING]    `action.value_lossless`
  - Value transferred by this trace in Wei. A decimal number represented in STRING format to preserve full 256-bit numeric precision. Available only for "call" traces.
* [STRING]    `action.init`
  - Input sent along with the transaction that deploys the contract. Available only for "create" traces.
* [STRING]    `action.author`
  - Recipient of the block or uncle reward. Available only for "reward" traces.
* [STRING]    `action.reward_type`
  - Reward type. One of "block" or "uncle". Available only for "reward" traces.
* [STRING]    `action.refund_address`
  - Address to which the remaining balance of a suicided contract was transferred. Value is set only for "suicide" traces.
* [BIGNUMERIC] `action.refund_balance`
  - Refund balance in Wei for a suicided contract. A decimal number represented as a BIGNUMERIC to preserve up to 128-bit numeric precision. Available only for "suicide" traces.
* [STRING]    `action.refund_balance_lossless`
  - Refund balance in Wei for a suicided contract. A decimal number represented in STRING format to preserve full 256-bit numeric precision. Available only for "suicide" traces.
* [STRING]    `action.self_destructed_address`
  - Address of the contract being self-destructed. Available only for "suicide" traces.
* [RECORD]    `result`
  - Result of this trace.
* [INTEGER]   `result.gas_used`
  - Gas used by this trace alone.
* [STRING]    `result.output`
  - Value returned by the contract call. Empty if the RETURN method was not executed.
* [STRING]    `result.address`
  - Address of the deployed smart contract. Available only for "create" traces.
* [STRING]    `result.code`
  - Code of the deployed smart contract. Available only for "create" traces.
* [STRING]    `error`
  - Error message of this trace, if any.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
