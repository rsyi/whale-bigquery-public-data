# `crypto_multiversx_mainnet_eu.miniblocks`
`bq-1` | `bigquery-public-data`
Miniblocks (sub-components of blocks).

## Column details
* [STRING]    `_id`
  - The miniblock hash.
* [STRING]    `procTypeD`
  - The processing type at the destination shard. It can be `Normal` or `Scheduled`.
* [STRING]    `procTypeS`
  - The processing type at the source shard. It can be `Normal` or `Scheduled`.
* [STRING]    `receiverBlockHash`
  - The hash (hex encoded) of the destination block in which the miniblock was included.
* [NUMERIC]   `receiverShard`
  - The shard ID of the destination block.
* [STRING]    `reserved`
* [STRING]    `senderBlockHash`
  - The hash (hex encoded) of the source block in which the miniblock was included.
* [NUMERIC]   `senderShard`
  - The shard ID of the source block.
* [TIMESTAMP] `timestamp`
  - The timestamp of the block in which the miniblock was executed.
* [STRING]    `type`
  - The type of the miniblock. It can be `TxBlock` (if it contains transactions) or `SmartContractResultBlock` (if it contains smart contracts results).

-------------------------------------------------------------------------------
*Do not make edits above this line.*
