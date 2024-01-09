# `crypto_multiversx_mainnet_eu.accounts`
`bq-1` | `bigquery-public-data`
Accounts data.

## Column details
* [STRING]    `_id`
  - The address of the account, in bech32 encoding. Same as `address`.
* [STRING]    `address`
  - The address in bech32 encoding. Should be equal to the `_id` field.
* [STRING]    `userName`
  - The herotag the address possesses.
* [STRING]    `balance`
  - The EGLD balance, in atomic units. E.g. '1500000000000000000' means 1.5 EGLD.
* [FLOAT]     `balanceNum`
  - See `balance`. This value is expressed in EGLD.
* [FLOAT]     `nonce`
  - The sequence number of the address.
* [NUMERIC]   `shardID`
  - The shard of the account.
* [TIMESTAMP] `timestamp`
  - The last moment when the address balance was changed.
* [STRING]    `developerRewards`
  - The developer rewards (for smart contract calls), in atomic units of EGLD. E.g. '1500000000000000000' means 1.5 EGLD.
* [FLOAT]     `developerRewardsNum`
  - See `developerRewards`. This value is expressed in EGLD.
* [STRING]    `totalBalanceWithStake`
  - Total balance of the account, including the staked amount, in atomic units of EGLD. E.g. '1500000000000000000' means 1.5 EGLD.
* [FLOAT]     `totalBalanceWithStakeNum`
  - See `totalBalanceWithStake`. This value is expressed in EGLD.
* [STRING]    `currentOwner`
  - The address in a bech32 format of the current owner of the smart contract. This field is populated only for the smart contract addresses.
* [STRING]    `codeHash`
  - The current code hash of the smart contract.
* [STRING]    `rootHash`
  - The root hash of the smart contract's data trie.
* [STRING]    `codeMetadata`
  - The code metadata of the smart contract.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
