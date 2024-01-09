# `crypto_multiversx_mainnet_eu.blocks`
`bq-1` | `bigquery-public-data`
Blocks.

## Column details
* [STRING]    `_id`
  - The block hash.
* [STRING]    `accumulatedFees`
  - The accumulated fees that were payed in the block.
* [STRING]    `developerFees`
  - The developer fees that were accumulated in the block.
* [NUMERIC]   `epoch`
  - The epoch when the block was proposed and executed.
* [BOOLEAN]   `epochStartBlock`
  - Whether the current block is an epoch-start block.
* [RECORD]    `epochStartInfo`
  - A structure with information about the new epoch.
* [STRING]    `epochStartInfo.nodePrice`
  - EGLD amount required to run a validator.
* [STRING]    `epochStartInfo.prevEpochStartHash`
  - The hash of the previous epoch start block.
* [NUMERIC]   `epochStartInfo.prevEpochStartRound`
  - The round of the previous epoch start block.
* [STRING]    `epochStartInfo.rewardsForProtocolSustainability`
  - The amount of rewards for the protocol sustainability address.
* [STRING]    `epochStartInfo.rewardsPerBlock`
  - The amount of EGLD rewards per block.
* [STRING]    `epochStartInfo.totalNewlyMinted`
  - The amount of the newly minted EGLD.
* [STRING]    `epochStartInfo.totalSupply`
  - The EGLD supply.
* [STRING]    `epochStartInfo.totalToDistribute`
  - The amount of EGLD that will be distributed to validators/delegators.
* [RECORD]    `epochStartShardsData`
  - An array of structures with information about the epoch start.
* [NUMERIC]   `epochStartShardsData.epoch`
  - The epoch number.
* [STRING]    `epochStartShardsData.firstPendingMetaBlock`
  - The first pending metablock hash.
* [STRING]    `epochStartShardsData.headerHash`
  - The hash of the epoch start block.
* [STRING]    `epochStartShardsData.lastFinishedMetaBlock`
  - The last finished metablock hash.
* [NUMERIC]   `epochStartShardsData.nonce`
  - The sequence number (block height) of the epoch start block.
* [RECORD]    `epochStartShardsData.pendingMiniBlockHeaders`
  - An array of structures with information about the pending miniblocks.
* [STRING]    `epochStartShardsData.pendingMiniBlockHeaders.hash`
  - The miniblock hash.
* [NUMERIC]   `epochStartShardsData.pendingMiniBlockHeaders.receiverShard`
  - The receiver shard.
* [NUMERIC]   `epochStartShardsData.pendingMiniBlockHeaders.senderShard`
  - The sender shard.
* [TIMESTAMP] `epochStartShardsData.pendingMiniBlockHeaders.timestamp`
  - The timestamp of the miniblock.
* [STRING]    `epochStartShardsData.pendingMiniBlockHeaders.type`
  - The type of the miniblock.
* [STRING]    `epochStartShardsData.rootHash`
  - The root hash of the epoch start block.
* [NUMERIC]   `epochStartShardsData.round`
  - The first round of the epoch.
* [STRING]    `epochStartShardsData.scheduledRootHash`
  - The 'scheduled' root hash of the epoch start block.
* [NUMERIC]   `epochStartShardsData.shardID`
  - The shard ID.
* [FLOAT]     `gasPenalized`
  - The total gas that was penalized in the block.
* [FLOAT]     `gasProvided`
  - The total gas that was provided in the block.
* [FLOAT]     `gasRefunded`
  - The total gas that was refunded in the block.
* [FLOAT]     `maxGasLimit`
  - The total gas that can be provided in the block.
* [RECORD]    `miniBlocksDetails`
  - An array of structures with information about the miniblocks within the block.
* [NUMERIC]   `miniBlocksDetails.firstProcessedTx`
  - The index of the first transaction that was processed in the miniblock.
* [NUMERIC]   `miniBlocksDetails.lastProcessedTx`
  - The index of the last transaction that was processed in the miniblock.
* [NUMERIC]   `miniBlocksDetails.senderShard`
  - The sender shard.
* [NUMERIC]   `miniBlocksDetails.receiverShard`
  - The receiver shard.
* [NUMERIC]   `miniBlocksDetails.mbIndex`
  - The index of the miniblock.
* [STRING]    `miniBlocksDetails.type`
  - The type of the miniblock.
* [STRING]    `miniBlocksDetails.procType`
  - The processing type of the miniblock.
* [STRING]    `miniBlocksDetails.txsHashes`
  - The hashes of the transactions that were included in the miniblock.
* [NUMERIC]   `miniBlocksDetails.executionOrderTxsIndices`
* [STRING]    `miniBlocksHashes`
  - An array of the miniblock hashes (hexadecimal encoded) that were included in the block.
* [NUMERIC]   `nonce`
  - The sequence number of the block (block height).
* [STRING]    `notarizedBlocksHashes`
  - The hashes of the blocks that were notarized in the current block.
* [NUMERIC]   `notarizedTxsCount`
  - The number of transactions that were notarized in the block.
* [STRING]    `prevHash`
  - The hash of the previous block.
* [NUMERIC]   `proposer`
  - The index of the validator that proposed the block.
* [STRING]    `pubKeyBitmap`
  - The pub key bitmap.
* [NUMERIC]   `round`
  - The round when the block was proposed and executed.
* [RECORD]    `scheduledData`
  - A structure that contains data about the scheduled execution.
* [STRING]    `scheduledData.accumulatedFees`
* [STRING]    `scheduledData.developerFees`
* [FLOAT]     `scheduledData.gasProvided`
* [FLOAT]     `scheduledData.gasRefunded`
* [FLOAT]     `scheduledData.penalized`
* [STRING]    `scheduledData.rootHash`
* [NUMERIC]   `searchOrder`
* [NUMERIC]   `shardId`
  - The shard this block belongs to.
* [NUMERIC]   `size`
  - The size of the block in bytes.
* [NUMERIC]   `sizeTxs`
  - The size of the block's transactions in bytes.
* [STRING]    `stateRootHash`
  - The trie's state root hash when the block was proposed and executed.
* [TIMESTAMP] `timestamp`
  - The timestamp when the block was proposed and executed.
* [NUMERIC]   `txCount`
  - The number of transactions that were executed in the block.
* [NUMERIC]   `validators`
  - An array that contains the indices of the validators that signed the block.
* [STRING]    `signature`
  - The block signature.
* [STRING]    `leaderSignature`
  - The leader signature.
* [STRING]    `randSeed`
  - The random seed.
* [STRING]    `prevRandSeed`
  - The random seed of the previous block.
* [STRING]    `receiptsHash`
  - The receipts hash.
* [STRING]    `softwareVersion`
  - The software version.
* [STRING]    `chainID`
  - The chain ID.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
