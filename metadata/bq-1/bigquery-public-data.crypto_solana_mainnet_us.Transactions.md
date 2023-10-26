# `crypto_solana_mainnet_us.Transactions`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `block_slot`
  - The block's slot
* [STRING]    `block_hash`
  - The block's hash
* [TIMESTAMP] `block_timestamp`
  - The block's timestamp
* [STRING]    `recent_block_hash`
  - A recent block's hash at the time of the transaction
* [STRING]    `signature`
  - The transaction signature
* [INTEGER]   `index`
  - The position of the transaction within the block
* [NUMERIC]   `fee`
  - The fee of the transaction, paid by the sender
* [STRING]    `status`
  - The status of the transaction. Ok or Err
* [STRING]    `err`
  - The specific error of the transaction, if there was one
* [NUMERIC]   `compute_units_consumed`
  - The compute usage of the transaction
* [RECORD]    `accounts`
* [STRING]    `accounts.pubkey`
  - The account's public key
* [BOOLEAN]   `accounts.signer`
  - True if the account signed the transaction, false otherwise
* [BOOLEAN]   `accounts.writable`
  - True if the account is writable, false otherwise
* [STRING]    `log_messages`
  - The log messages of the transaction
* [RECORD]    `balance_changes`
* [STRING]    `balance_changes.account`
  - The public key of the account
* [NUMERIC]   `balance_changes.before`
  - The balance of the account before the transaction
* [NUMERIC]   `balance_changes.after`
  - The balance of the account after the transaction
* [RECORD]    `pre_token_balances`
* [INTEGER]   `pre_token_balances.account_index`
  - The index of the account with the balance
* [STRING]    `pre_token_balances.mint`
  - The mint of the token
* [STRING]    `pre_token_balances.owner`
  - The token balance's owner
* [BIGNUMERIC] `pre_token_balances.amount`
  - The token balance before the transaction
* [INTEGER]   `pre_token_balances.decimals`
  - The position of the decimal point in the token balance before the transaction
* [RECORD]    `post_token_balances`
* [INTEGER]   `post_token_balances.account_index`
  - The index of the account with the balance
* [STRING]    `post_token_balances.mint`
  - The mint of the token
* [STRING]    `post_token_balances.owner`
  - The token balance's owner
* [BIGNUMERIC] `post_token_balances.amount`
  - The token balance before the transaction
* [INTEGER]   `post_token_balances.decimals`
  - The position of the decimal point in the token balance before the transaction

-------------------------------------------------------------------------------
*Do not make edits above this line.*
