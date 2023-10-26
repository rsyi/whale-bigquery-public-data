# `crypto_solana_mainnet_us.Accounts`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `block_slot`
  - The block's slot
* [STRING]    `block_hash`
  - The block's hash
* [TIMESTAMP] `block_timestamp`
  - The block's timestamp
* [STRING]    `pubkey`
  - The account's public key
* [STRING]    `tx_signature`
  - The signature of the transaction that created the account
* [TIMESTAMP] `retrieval_timestamp`
  - A timestamp of when the account data was retrieved
* [BOOLEAN]   `executable`
  - True if the account data is executable, false otherwise
* [NUMERIC]   `lamports`
  - The account's balance, in Lamports
* [STRING]    `owner`
  - The program assigned to the account
* [INTEGER]   `rent_epoch`
  - The next epoch when this account will owe rent
* [STRING]    `program`
* [INTEGER]   `space`
* [STRING]    `account_type`
* [BOOLEAN]   `is_native`
* [STRING]    `mint`
* [STRING]    `state`
* [NUMERIC]   `token_amount`
* [INTEGER]   `token_amount_decimals`
* [STRING]    `program_data`
* [RECORD]    `authorized_voters`
* [STRING]    `authorized_voters.authorized_voter`
* [INTEGER]   `authorized_voters.epoch`
* [STRING]    `authorized_withdrawer`
* [RECORD]    `prior_voters`
* [STRING]    `prior_voters.authorized_pubkey`
* [INTEGER]   `prior_voters.epoch_of_last_authorized_switch`
* [INTEGER]   `prior_voters.target_epoch`
* [STRING]    `node_pubkey`
* [INTEGER]   `commission`
* [RECORD]    `epoch_credits`
* [STRING]    `epoch_credits.credits`
* [INTEGER]   `epoch_credits.epoch`
* [STRING]    `epoch_credits.previous_credits`
* [RECORD]    `votes`
* [INTEGER]   `votes.confirmation_count`
* [INTEGER]   `votes.slot`
* [INTEGER]   `root_slot`
* [RECORD]    `last_timestamp`
* [INTEGER]   `last_timestamp.slot`
* [TIMESTAMP] `last_timestamp.timestamp`
* [RECORD]    `data`
* [STRING]    `data.raw`
  - The raw data, which could not be parsed by the data source
* [STRING]    `data.encoding`
  - The encoding type of the raw data

-------------------------------------------------------------------------------
*Do not make edits above this line.*
