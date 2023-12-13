# `crypto_multiversx_mainnet_eu.delegators`
`bq-1` | `bigquery-public-data`
Delegators.

## Column details
* [STRING]    `_id`
  - A unique identifier (opaque).
* [STRING]    `activeStake`
  - The EGLD amount of the active stake (not undelegated nor unbondable).
* [FLOAT]     `activeStakeNum`
  - The EGLD amount of the active stake (not undelegated nor unbondable), in a numeric format. Example: 1.5.
* [TIMESTAMP] `timestamp`
  - The last moment of an interaction with the delegation contract.
* [STRING]    `address`
  - The address in bech32 encoding of the delegator.
* [STRING]    `contract`
  - The bech32 encoded address of the staking provider contract to whom it was delegated to.
* [RECORD]    `unDelegateInfo`
  - The unDelegateInfo contains a list with data about the unDelegated values.
* [STRING]    `unDelegateInfo.id`
* [TIMESTAMP] `unDelegateInfo.timestamp`
  - The timestamp when the unDelegation operation was done.
* [STRING]    `unDelegateInfo.value`
  - The EGLD amount that was undelegated.
* [FLOAT]     `unDelegateInfo.valueNum`
  - The EGLD amount that was undelegated, in a numeric format (example: 1.5).

-------------------------------------------------------------------------------
*Do not make edits above this line.*
