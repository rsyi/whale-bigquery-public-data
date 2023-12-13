# `crypto_multiversx_mainnet_eu.accountsesdt`
`bq-1` | `bigquery-public-data`
ESDTs of accounts.

## Column details
* [STRING]    `_id`
  - A unique identifier (opaque).
* [STRING]    `address`
  - The address in bech32 encoding.
* [STRING]    `balance`
  - The ESDT balance, in atomic units.
* [FLOAT]     `balanceNum`
  - See `balance`.
* [STRING]    `currentOwner`
* [RECORD]    `data`
  - A structure that contains additional information about a token.
* [STRING]    `data.attributes`
  - The attributes of the token.
* [STRING]    `data.creator`
  - The creator of the token (address).
* [STRING]    `data.hash`
  - Arbitrary field that should contain the hash of the NFT metadata.
* [STRING]    `data.metadata`
  - Token metadata.
* [STRING]    `data.name`
  - Token name.
* [BOOLEAN]   `data.nonEmptyURIs`
  - Whether the token has non empty uris.
* [BOOLEAN]   `data.whiteListedStorage`
  - Whether the token has whitelisted storage. An NFT/SFT has whitelisted storage if the URI belongs to one of the allowed decentralized storage services, such as IPFS or Pinata.
* [NUMERIC]   `data.royalties`
  - NFT royalties. Numeric value between 0 and 10000 (0 meaning 0% and 10000 meaning 100%).
* [STRING]    `data.tags`
* [STRING]    `data.uris`
  - A list of URIs.
* [STRING]    `identifier`
  - The extended identifier. E.g. `TOKEN-01abdc-01`.
* [STRING]    `properties`
* [NUMERIC]   `shardID`
  - Shard of the account.
* [TIMESTAMP] `timestamp`
  - The timestamp when the address balance was changed.
* [STRING]    `token`
  - The name of the token.
* [FLOAT]     `tokenNonce`
  - The sequence number of the token. This field is empty in the case of `FungibleESDT`.
* [STRING]    `type`
  - The type of the ESDT token. It can be `FungibleESDT`, `NonFungibleESDT`, `SemiFungibleESDT`, or `MetaESDT`.
* [BOOLEAN]   `frozen`
  - Whether the tokens in question are 'frozen' for this account.
* [BOOLEAN]   `paused`
  - Whether the token (collection) is 'paused'.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
