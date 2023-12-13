# `crypto_multiversx_mainnet_eu.accountshistory`
`bq-1` | `bigquery-public-data`
Accounts data (with history).

## Column details
* [STRING]    `_id`
  - A unique identifier (opaque).
* [STRING]    `address`
  - The address in bech32 encoding.
* [STRING]    `balance`
  - The (historical) EGLD balance, in atomic units. E.g. '1500000000000000000' means 1.5 EGLD.
* [BOOLEAN]   `isSender`
  - Whether the account was the sender (of the EGLD) when the balance changed.
* [BOOLEAN]   `isSmartContract`
  - Whether the account is a smart contract.
* [NUMERIC]   `shardID`
  - The shard of the account.
* [TIMESTAMP] `timestamp`
  - The timestamp when the address balance was changed.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
