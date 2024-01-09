# `crypto_multiversx_mainnet_eu.scresults`
`bq-1` | `bigquery-public-data`
Smart contract results.

## Column details
* [STRING]    `_id`
  - The smart contract result hash.
* [STRING]    `callType`
  - The type of smart contract call that is done through the smart contract result.
* [STRING]    `code`
  - The code holds the code of the smart contract result.
* [STRING]    `data`
  - Additional information for a smart contract result. It can contain a simple message, a function call, an ESDT transfer payload, and so on.
* [STRING]    `esdtValues`
  - A list of ESDT values that are transferred by the contract result. Values are expressed in atomic units.
* [STRING]    `function`
  - The name of the function that is called in case of a smart contract call.
* [FLOAT]     `gasLimit`
  - The maximum gas units the sender is willing to pay for.
* [FLOAT]     `gasPrice`
  - The amount to be paid for each gas unit.
* [BOOLEAN]   `hasOperations`
  - Whether the smart contract result produced any operations (e.g. other results).
* [BOOLEAN]   `hasLogs`
  - Whether the transaction has event logs.
* [STRING]    `miniBlockHash`
  - The hash of the miniblock in which the smart contract result was included.
* [NUMERIC]   `nonce`
  - The transaction sequence number.
* [STRING]    `operation`
  - The operation of the smart contract result based on the data field.
* [STRING]    `originalSender`
  - The sender's address of the original transaction.
* [STRING]    `originalTxHash`
  - The originalTxHash holds the hex encoded hash of the transaction that generated the smart contract result.
* [STRING]    `prevTxHash`
  - The prevTxHash holds the hex encoded hash of the previous transaction.
* [STRING]    `receiver`
  - The destination address of the smart contract result.
* [NUMERIC]   `receiverShard`
  - The shard ID of the receiver address.
* [STRING]    `receivers`
  - A list of receiver addresses (one element for now).
* [NUMERIC]   `receiversShardIDs`
  - A list of receiver addresses' shard IDs (one element for now).
* [STRING]    `relayedValue`
  - The amount of EGLD to be transferred via the inner transaction's sender.
* [STRING]    `relayerAddr`
  - The address of the relayer.
* [STRING]    `returnMessage`
  - The message that is returned by a smart contract in case of an error.
* [STRING]    `sender`
  - The address of the smart contract result sender.
* [NUMERIC]   `senderShard`
  - The shard ID of the sender address.
* [TIMESTAMP] `timestamp`
  - The timestamp of the block in which the smart contract result was executed.
* [STRING]    `tokens`
  - A list of ESDT tokens that are transferred by the contract result.
* [STRING]    `value`
  - The amount of EGLD transferred by the contract result, in atomic units. E.g. '1500000000000000000' means 1.5 EGLD.
* [FLOAT]     `valueNum`
  - See `value` field. This value is expressed in EGLD.
* [FLOAT]     `esdtValuesNum`
  - See `esdtValues` field.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
