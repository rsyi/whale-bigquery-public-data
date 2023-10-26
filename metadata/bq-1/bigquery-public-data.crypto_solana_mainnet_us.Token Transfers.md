# `crypto_solana_mainnet_us.Token Transfers`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `block_slot`
  - The block's slot
* [STRING]    `block_hash`
  - The block's timestamp
* [TIMESTAMP] `block_timestamp`
  - The block's hash
* [STRING]    `tx_signature`
  - The signature of the transaction that this instruction came from
* [STRING]    `source`
  - The account that sent the token. Not present for token minting or burning
* [STRING]    `destination`
  - The account that received the token. Not present for token minting or burning
* [STRING]    `authority`
  - The transfer authority account. Defined by the token program. Not present for token minting or burning
* [NUMERIC]   `value`
  - The amount of tokens transferred
* [NUMERIC]   `decimals`
  - The position of the decimal point in the amount
* [STRING]    `mint`
  - The mint account. Not present for token transferring or burning
* [STRING]    `mint_authority`
  - The account holding mint authority. Not present for token transferring or burning
* [NUMERIC]   `fee`
  - The fee amount paid for the transfer
* [NUMERIC]   `fee_decimals`
  - The position of the decimal point in the fee amount
* [STRING]    `memo`
  - The memo, from the previous instruction
* [STRING]    `transfer_type`
  - The type of the transfer, such as mintTo or transfer

-------------------------------------------------------------------------------
*Do not make edits above this line.*
