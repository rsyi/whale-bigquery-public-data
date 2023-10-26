# `crypto_solana_mainnet_us.Tokens`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `block_slot`
  - The block's slot
* [STRING]    `block_hash`
  - The block's timestamp
* [TIMESTAMP] `block_timestamp`
  - The block's hash
* [STRING]    `tx_signature`
  - The signature of the transaction that transferred the token
* [TIMESTAMP] `retrieval_timestamp`
  - The timestamp from when the token data was retrieved
* [BOOLEAN]   `is_nft`
  - True if the token is an NFT, false otherwise
* [STRING]    `mint`
  - The mint account of the token
* [STRING]    `update_authority`
  - The account with the authority to update the token
* [STRING]    `name`
  - The name of the token
* [STRING]    `symbol`
  - The symbol of the token
* [STRING]    `uri`
  - A URI to an external JSON that provides information about the token
* [NUMERIC]   `seller_fee_basis_points`
  - The fee that the seller is charged when the token is traded. Value is in basis points
* [RECORD]    `creators`
* [STRING]    `creators.address`
  - The address of the creator's account
* [BOOLEAN]   `creators.verified`
  - The verification status of the creator
* [INTEGER]   `creators.share`
  - The proportion of ownership (as a percentage) that this creator has over the token
* [BOOLEAN]   `primary_sale_happened`
  - True if the token has had its primary sale, false otherwise
* [BOOLEAN]   `is_mutable`
  - True if the token can be modified after its creation, false otherwise

-------------------------------------------------------------------------------
*Do not make edits above this line.*
