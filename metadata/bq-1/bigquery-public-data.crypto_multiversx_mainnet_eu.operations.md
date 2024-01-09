# `crypto_multiversx_mainnet_eu.operations`
`bq-1` | `bigquery-public-data`
Operations (transactions and transactions results).

## Column details
* [STRING]    `_id`
  - The transaction or smart contract result hash.
* [STRING]    `callType`
  - Call type (for smart contract results).
* [BOOLEAN]   `canBeIgnored`
* [STRING]    `code`
  - The contract code (for smart contract deployments and upgrades).
* [STRING]    `data`
  - Additional information for a transaction. It can contain a simple message, a function call, an ESDT transfer payload, and so on.
* [STRING]    `esdtValues`
  - A list of ESDT values that are transferred. Values are expressed in atomic units.
* [STRING]    `fee`
  - The amount of EGLD the sender paid for the transaction, expressed in atomic units.
* [FLOAT]     `feeNum`
  - See `fee` field.
* [STRING]    `function`
  - The name of the function that is called in case of a smart contract call.
* [FLOAT]     `gasLimit`
  - The maximum gas units the sender is willing to pay for.
* [FLOAT]     `gasPrice`
  - The amount to be paid for each gas unit.
* [FLOAT]     `gasUsed`
  - The amount of gas used by the transaction.
* [BOOLEAN]   `hasOperations`
  - Whether the transaction has smart contract results.
* [BOOLEAN]   `hasScResults`
  - Whether the transaction has smart contract results.
* [BOOLEAN]   `hasLogs`
  - Whether the transaction has event logs.
* [STRING]    `initialPaidFee`
  - The initial amount of EGLD the sender paid for the transaction, before the refund.
* [BOOLEAN]   `isRelayed`
  - Whether the transaction is a relayed transaction.
* [BOOLEAN]   `isScCall`
  - Whether the transaction is a smart contract call.
* [STRING]    `miniBlockHash`
  - The hash of the miniblock in which the transaction was included.
* [NUMERIC]   `nonce`
  - The transaction sequence number of the sender.
* [STRING]    `operation`
  - The operation of the transaction, given the data field.
* [STRING]    `originalSender`
  - The sender of the original transaction.
* [STRING]    `originalTxHash`
  - The hash of the original transaction.
* [STRING]    `prevTxHash`
  - The hash of the previous transaction (for smart contract results).
* [STRING]    `receiver`
  - The receiver address.
* [NUMERIC]   `receiverShard`
  - The shard of the receiver address.
* [STRING]    `receivers`
  - A list of receiver addresses (one element for now).
* [NUMERIC]   `receiversShardIDs`
  - A list of receiver addresses shard IDs (one element for now).
* [STRING]    `receiverUserName`
  - The username of the receiver address.
* [STRING]    `relayedValue`
* [STRING]    `relayerAddr`
  - The address of the relayer.
* [STRING]    `returnMessage`
  - The return message (for smart contract calls).
* [NUMERIC]   `round`
  - The round of the block when the transaction was executed.
* [NUMERIC]   `searchOrder`
* [STRING]    `sender`
  - The address of the transaction sender.
* [NUMERIC]   `senderShard`
  - The shard of the sender address.
* [STRING]    `senderUserName`
  - The username of the sender address.
* [STRING]    `signature`
  - The signature of the transaction, hex-encoded.
* [STRING]    `status`
  - The status of the transaction.
* [TIMESTAMP] `timestamp`
  - The timestamp of the block in which the transaction was executed.
* [STRING]    `tokens`
  - A list of ESDT tokens that are transferred by the transaction.
* [STRING]    `type`
  - The operation type: `normal` in case of a user-signed transaction and `unsigned` in case of a smart contract result.
* [STRING]    `value`
  - The amount of EGLD transferred, in atomic units. E.g. '1500000000000000000' means 1.5 EGLD.
* [NUMERIC]   `version`
  - The version (for `normal` transactions).
* [FLOAT]     `valueNum`
  - See `value` field. This value is expressed in EGLD.
* [FLOAT]     `esdtValuesNum`
  - See `esdtValues` field.
* [STRING]    `guardian`
  - The guardian address, if the sender has a guardian.
* [STRING]    `guardianSignature`
  - The signature of the guardian.
* [BOOLEAN]   `errorEvent`
  - Whether the transaction has an event that indicates an error.
* [BOOLEAN]   `completedEvent`
  - Whether the transaction has an event that indicates completion.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
