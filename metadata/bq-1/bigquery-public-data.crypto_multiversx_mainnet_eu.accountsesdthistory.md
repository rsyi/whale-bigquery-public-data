# `crypto_multiversx_mainnet_eu.accountsesdthistory`
`bq-1` | `bigquery-public-data`
ESDTs of accounts (with history).

## Column details
* [STRING]    `_id`
  - A unique identifier (opaque).
* [STRING]    `address`
  - The address in bech32 encoding.
* [STRING]    `balance`
  - The (historical) ESDT balance, in atomic units.
* [STRING]    `identifier`
  - The identifier field is composed of the `token` field and the `nonce` field, hex encoded.
* [BOOLEAN]   `isSender`
  - Whether the account was the sender (of the ESDT) when the balance changed.
* [BOOLEAN]   `isSmartContract`
  - Whether the address is a smart contract address.
* [NUMERIC]   `shardID`
  - The shard of the account.
* [TIMESTAMP] `timestamp`
  - The timestamp when the address balance was changed.
* [STRING]    `token`
  - The token name of the token.
* [FLOAT]     `tokenNonce`
  - The sequence number of the token. This field can be empty in the case of `FungibleESDT`.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
