# `crypto_theta.blocks_and_transactions`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `type`
  - object type
* [STRING]    `chain_id`
  - chain id
* [STRING]    `epoch`
  - block epoch
* [STRING]    `height`
  - block height
* [STRING]    `parent`
  - block parent hash
* [STRING]    `transactions_hash`
  - block transactions hash
* [STRING]    `state_hash`
  - block transactions hash
* [TIMESTAMP] `timestamp`
  - block timestamp
* [STRING]    `proposer`
  - block proposer
* [RECORD]    `hcc`
  - block hcc
* [STRING]    `hcc.type`
  - object type
* [STRING]    `hcc.BlockHash`
  - hcc blockhash
* [RECORD]    `hcc.Votes`
  - hcc votes
* [STRING]    `hcc.Votes.type`
  - object type
* [STRING]    `hcc.Votes.Block`
  - Hash of the tip as seen by the voter
* [NUMERIC]   `hcc.Votes.Height`
  - Height of the tip
* [NUMERIC]   `hcc.Votes.Epoch`
  - Voter's current epoch
* [STRING]    `hcc.Votes.ID`
  - Voter's address
* [STRING]    `hcc.Votes.Signature`
  - Voter's signature
* [RECORD]    `guardian_votes`
  - block guardian votes
* [STRING]    `guardian_votes.type`
  - object type
* [STRING]    `guardian_votes.Block`
  - guardian vote block hash
* [STRING]    `guardian_votes.Gcp`
  - guardian vote Gcp
* [RECORD]    `guardian_votes.Signature`
  - guardian vote Signature
* [STRING]    `guardian_votes.Signature.s`
  - message signature
* [NUMERIC]   `guardian_votes.Multiplies`
  - guardian vote Multiplies
* [STRING]    `children`
  - block children block hashes
* [NUMERIC]   `status`
  - block status
* [STRING]    `hash`
  - block hash
* [RECORD]    `transactions`
  - block transactions
* [STRING]    `transactions.type`
  - object type
* [NUMERIC]   `transactions.tx_type`
  - transaction type
* [STRING]    `transactions.hash`
  - transaction hash
* [RECORD]    `transactions.raw`
  - raw transaction
* [STRING]    `transactions.raw.type`
  - object type
* [STRING]    `transactions.raw.block_height`
  - transaction block height
* [RECORD]    `transactions.raw.proposer`
  - transaction proposer
* [STRING]    `transactions.raw.proposer.type`
  - object type
* [STRING]    `transactions.raw.proposer.address`
  - transaction proposer address
* [STRING]    `transactions.raw.proposer.sequence`
  - transaction proposer sequence
* [STRING]    `transactions.raw.proposer.signature`
  - transaction proposer signature
* [RECORD]    `transactions.raw.proposer.coins`
  - transaction proposer coins
* [STRING]    `transactions.raw.proposer.coins.type`
  - object type
* [STRING]    `transactions.raw.proposer.coins.thetawei`
  - transaction proposer coins thetawei
* [STRING]    `transactions.raw.proposer.coins.tfuelwei`
  - transaction proposer coins tfuelwei
* [RECORD]    `transactions.raw.fee`
  - transaction fee
* [STRING]    `transactions.raw.fee.type`
  - object type
* [STRING]    `transactions.raw.fee.thetawei`
  - transaction fee thetawei
* [STRING]    `transactions.raw.fee.tfuelwei`
  - transaction fee tfuelwei
* [RECORD]    `transactions.raw.inputs`
  - transaction inputs
* [STRING]    `transactions.raw.inputs.type`
  - object type
* [STRING]    `transactions.raw.inputs.address`
  - transaction input address
* [STRING]    `transactions.raw.inputs.sequence`
  - transaction input sequence
* [STRING]    `transactions.raw.inputs.signature`
  - transaction input signature
* [RECORD]    `transactions.raw.inputs.coins`
  - transaction input coins
* [STRING]    `transactions.raw.inputs.coins.type`
  - object type
* [STRING]    `transactions.raw.inputs.coins.thetawei`
  - transaction input coins thetawei
* [STRING]    `transactions.raw.inputs.coins.tfuelwei`
  - transaction input coins tfuelwei
* [RECORD]    `transactions.raw.outputs`
  - transaction outputs
* [STRING]    `transactions.raw.outputs.type`
  - object type
* [STRING]    `transactions.raw.outputs.address`
  - transaction output address
* [RECORD]    `transactions.raw.outputs.coins`
  - transaction output coins
* [STRING]    `transactions.raw.outputs.coins.type`
  - object type
* [STRING]    `transactions.raw.outputs.coins.thetawei`
  - transaction output coins thetawei
* [STRING]    `transactions.raw.outputs.coins.tfuelwei`
  - transaction output coins tfuelwei
* [STRING]    `transactions.raw.slashed_address`
  - transaction slashed address
* [STRING]    `transactions.raw.payment_sequence`
  - transaction payment sequence
* [STRING]    `transactions.raw.reserve_sequence`
  - transaction reserve sequence
* [STRING]    `transactions.raw.slash_proof`
  - transaction slash proof
* [STRING]    `transactions.raw.resource_id`
  - transaction resource id
* [STRING]    `transactions.raw.resource_ids`
  - transaction resource ids
* [STRING]    `transactions.raw.duration`
  - transaction duration
* [RECORD]    `transactions.raw.source`
  - transaction source
* [STRING]    `transactions.raw.source.type`
  - object type
* [STRING]    `transactions.raw.source.address`
  - transaction source address
* [STRING]    `transactions.raw.source.sequence`
  - transaction source sequence
* [STRING]    `transactions.raw.source.signature`
  - transaction source signature
* [RECORD]    `transactions.raw.source.coins`
  - transaction source coins
* [STRING]    `transactions.raw.source.coins.type`
  - object type
* [STRING]    `transactions.raw.source.coins.thetawei`
  - transaction source coins thetawei
* [STRING]    `transactions.raw.source.coins.tfuelwei`
  - transaction source coins tfuelwei
* [RECORD]    `transactions.raw.target`
  - transaction target
* [STRING]    `transactions.raw.target.type`
  - object type
* [STRING]    `transactions.raw.target.address`
  - transaction target address
* [STRING]    `transactions.raw.target.sequence`
  - transaction target sequence
* [STRING]    `transactions.raw.target.signature`
  - transaction target signature
* [RECORD]    `transactions.raw.target.coins`
  - transaction target coins
* [STRING]    `transactions.raw.target.coins.type`
  - object type
* [STRING]    `transactions.raw.target.coins.thetawei`
  - transaction target coins thetawei
* [STRING]    `transactions.raw.target.coins.tfuelwei`
  - transaction target coins tfuelwei
* [RECORD]    `transactions.raw.collateral`
  - transaction collateral
* [STRING]    `transactions.raw.collateral.type`
  - object type
* [STRING]    `transactions.raw.collateral.thetawei`
  - transaction collateral thetawei
* [STRING]    `transactions.raw.collateral.tfuelwei`
  - transaction collateral tfuelwei
* [RECORD]    `transactions.raw.splits`
  - transaction splits
* [STRING]    `transactions.raw.splits.type`
  - object type
* [STRING]    `transactions.raw.splits.Address`
  - transaction split address
* [NUMERIC]   `transactions.raw.splits.Percentage`
  - transaction split percentage
* [RECORD]    `transactions.raw.initiator`
  - transaction initiator
* [STRING]    `transactions.raw.initiator.type`
  - object type
* [STRING]    `transactions.raw.initiator.address`
  - transaction initiator address
* [STRING]    `transactions.raw.initiator.sequence`
  - transaction initiator sequence
* [STRING]    `transactions.raw.initiator.signature`
  - transaction initiator signature
* [RECORD]    `transactions.raw.initiator.coins`
  - transaction initiator coins
* [STRING]    `transactions.raw.initiator.coins.type`
  - object type
* [STRING]    `transactions.raw.initiator.coins.thetawei`
  - transaction initiator coins thetawei
* [STRING]    `transactions.raw.initiator.coins.tfuelwei`
  - transaction initiator coins tfuelwei
* [STRING]    `transactions.raw.gas_limit`
  - transaction gas_limit
* [STRING]    `transactions.raw.gas_price`
  - transaction gas_price
* [BYTES]     `transactions.raw.data`
  - transaction data
* [RECORD]    `transactions.raw.from`
  - transaction from
* [STRING]    `transactions.raw.from.type`
  - object type
* [STRING]    `transactions.raw.from.address`
  - transaction from address
* [STRING]    `transactions.raw.from.sequence`
  - transaction from sequence
* [STRING]    `transactions.raw.from.signature`
  - transaction from signature
* [RECORD]    `transactions.raw.from.coins`
  - transaction from coins
* [STRING]    `transactions.raw.from.coins.type`
  - object type
* [STRING]    `transactions.raw.from.coins.thetawei`
  - transaction from coins thetawei
* [STRING]    `transactions.raw.from.coins.tfuelwei`
  - transaction from coins tfuelwei
* [RECORD]    `transactions.raw.to`
  - transaction to
* [STRING]    `transactions.raw.to.type`
  - object type
* [STRING]    `transactions.raw.to.address`
  - transaction to address
* [RECORD]    `transactions.raw.to.coins`
  - transaction to coins
* [STRING]    `transactions.raw.to.coins.type`
  - object type
* [STRING]    `transactions.raw.to.coins.thetawei`
  - transaction to coins thetawei
* [STRING]    `transactions.raw.to.coins.tfuelwei`
  - transaction to coins tfuelwei
* [RECORD]    `transactions.raw.holder`
  - transaction holder
* [STRING]    `transactions.raw.holder.type`
  - object type
* [STRING]    `transactions.raw.holder.address`
  - transaction holder address
* [RECORD]    `transactions.raw.holder.coins`
  - transaction holder coins
* [STRING]    `transactions.raw.holder.coins.type`
  - object type
* [STRING]    `transactions.raw.holder.coins.thetawei`
  - transaction holder coins thetawei
* [STRING]    `transactions.raw.holder.coins.tfuelwei`
  - transaction holder coins tfuelwei
* [NUMERIC]   `transactions.raw.Purpose`
  - transaction Purpose

-------------------------------------------------------------------------------
*Do not make edits above this line.*
