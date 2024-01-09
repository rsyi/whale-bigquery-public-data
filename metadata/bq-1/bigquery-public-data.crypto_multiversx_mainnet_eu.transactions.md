# `crypto_multiversx_mainnet_eu.transactions`
`bq-1` | `bigquery-public-data`
Transactions.

## Column details
* [STRING]    `_id`
  - The transaction hash.
* [STRING]    `data`
  - Additional information for a transaction. It can contain a simple message, a function call, an ESDT transfer payload, and so on.
* [STRING]    `esdtValues`
  - A list of ESDT values that are transferred by the transaction. Values are expressed in atomic units.
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
* [BOOLEAN]   `hasLogs`
  - Whether the transaction has event logs.
* [BOOLEAN]   `hasScResults`
  - Whether the transaction has smart contract results.
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
* [STRING]    `receiver`
  - The destination address of the transaction.
* [NUMERIC]   `receiverShard`
  - The shard ID of the receiver address.
* [STRING]    `receivers`
  - A list of receiver addresses (one element for now).
* [NUMERIC]   `receiversShardIDs`
  - A list of receiver addresses shard IDs (one element for now).
* [STRING]    `receiverUserName`
  - The username of the receiver address.
* [NUMERIC]   `round`
  - The round of the block when the transaction was executed.
* [NUMERIC]   `searchOrder`
* [STRING]    `sender`
  - The address of the transaction sender.
* [NUMERIC]   `senderShard`
  - The shard ID of the sender address.
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
* [STRING]    `value`
  - The amount of EGLD transferred by the transaction, in atomic units. E.g. '1500000000000000000' means 1.5 EGLD.
* [NUMERIC]   `version`
  - The version of the transaction.
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
