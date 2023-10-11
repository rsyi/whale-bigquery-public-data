# `crypto_near_mainnet_us.near_social_transactions`
`bq-1` | `bigquery-public-data`
NEAR Social transactions for posts, comments, likes, widgets, profiles, followers, etc.

## Column details
* [INTEGER]   `block_height`
  - The height of the Block
* [TIMESTAMP] `block_timestamp_utc`
  - The timestamp of the Block in UTC
* [DATE]      `block_date`
  - The date of the Block. Used to partition the table
* [STRING]    `signer_id`
  - An account on which behalf the origin transaction is signed
* [STRING]    `true_signer_id`
  - An account on which behalf the origin transaction is signed in case of action being delegated to relayer
* [STRING]    `predecessor_id`
  - The account ID which issued a receipt. In case of a gas or deposit refund, the account ID is system
* [STRING]    `receipt_id`
  - An unique id for the receipt
* [STRING]    `contract_id`
  - The contract ID
* [STRING]    `method_name`
  - The method name
* [STRING]    `deposit`
  - The deposit amount
* [STRING]    `gas`
  - The gas fee
* [STRING]    `account_object`
  - The account object
* [STRING]    `widget`
  - The account object edit widget
* [STRING]    `post`
  - The account object post or comment
* [STRING]    `profile`
  - The account object edit profile
* [STRING]    `graph`
  - The account object graph follow or hide
* [STRING]    `settings`
  - The account object settings
* [STRING]    `badge`
  - The account object badge
* [STRING]    `index`
  - The account object index like, follow, poke, comment, post, notify

-------------------------------------------------------------------------------
*Do not make edits above this line.*
