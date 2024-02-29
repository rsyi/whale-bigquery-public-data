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
  - The owner program of the account
* [INTEGER]   `space`
  - The fixed storage space (in bytes)
* [STRING]    `account_type`
  - The type of the account, e.g. "account" or "mint"
* [BOOLEAN]   `is_native`
  - Used for token accounts to specify if the token is native
* [STRING]    `mint`
  - Used for token accounts to specify the SPL token address
* [STRING]    `state`
  - The state of the account at the time the data was requested from the node
* [NUMERIC]   `token_amount`
  - Used for token accounts to specify the balance
* [INTEGER]   `token_amount_decimals`
  - Used for token accounts to specify the balance's divisiibility
* [STRING]    `program_data`
  - The raw data, for program accounts
* [RECORD]    `authorized_voters`
  - A list of authorized voters, used for vote accounts
* [STRING]    `authorized_voters.authorized_voter`
  - The vote authority account
* [INTEGER]   `authorized_voters.epoch`
  - The authorized epoch
* [STRING]    `authorized_withdrawer`
  - The public key of the authorized withdrawer account
* [RECORD]    `prior_voters`
  - Stores historical authorized voters, if the authorized voter has changed
* [STRING]    `prior_voters.authorized_pubkey`
  - The pubkey of the authorized voter
* [INTEGER]   `prior_voters.epoch_of_last_authorized_switch`
  - The epoch when the authorized voter last changed
* [INTEGER]   `prior_voters.target_epoch`
  - The epoch of the authorized voter change
* [STRING]    `node_pubkey`
  - The validator identity, as a base-58 encoded string
* [INTEGER]   `commission`
  - The percentage of rewards payout owed to the vote account
* [RECORD]    `epoch_credits`
  - The latest history of earned credits for up to five epochs
* [STRING]    `epoch_credits.credits`
  - The earned credits
* [INTEGER]   `epoch_credits.epoch`
  - The epoch of the earned credits
* [STRING]    `epoch_credits.previous_credits`
  - The previous credits earned
* [RECORD]    `votes`
  - Used for vote accounts. The votes by the account
* [INTEGER]   `votes.confirmation_count`
  - The confirmation progress
* [INTEGER]   `votes.slot`
  - The slot of the block voted on
* [INTEGER]   `root_slot`
  - Used for vote accounts. Current root slot for the account
* [RECORD]    `last_timestamp`
  - The most recent vote and timestamp from the vote account
* [INTEGER]   `last_timestamp.slot`
  - The slot voted on most recently
* [TIMESTAMP] `last_timestamp.timestamp`
  - The timestamp of the most recent vote
* [RECORD]    `data`
  - The raw data, specified if the account could not be parsed
* [STRING]    `data.raw`
  - The raw data
* [STRING]    `data.encoding`
  - The encoding type of the raw data

-------------------------------------------------------------------------------
*Do not make edits above this line.*
