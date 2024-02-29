# `crypto_near_mainnet_us.ft_balances_daily`
`bq-1` | `bigquery-public-data`
Fungible Tokens daily balances

## Column details
* [DATE]      `epoch_date`
  - The date of the Epoch. Used to partition the table
* [STRING]    `epoch_block_height`
  - The max height of the Block in the epoch
* [STRING]    `account_id`
  - The delegator Account ID
* [FLOAT]     `liquid`
  - Liquid balance
* [INTEGER]   `storage_usage`
  - Storage Usage
* [FLOAT]     `unstaked_not_liquid`
  - Unstaked balance
* [FLOAT]     `staked`
  - Staked balance
* [FLOAT]     `reward`
  - Reward
* [STRING]    `lockup_account_id`
  - The lockup delegator Account ID
* [FLOAT]     `lockup_liquid`
  - Lockup liquid balance
* [FLOAT]     `lockup_unstaked_not_liquid`
  - Lockup unstaked balance
* [FLOAT]     `lockup_staked`
  - Lockup staked balance
* [FLOAT]     `lockup_reward`
  - Lockup Reward

-------------------------------------------------------------------------------
*Do not make edits above this line.*
