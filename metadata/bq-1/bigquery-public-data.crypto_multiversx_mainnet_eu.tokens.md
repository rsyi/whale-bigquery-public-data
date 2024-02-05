# `crypto_multiversx_mainnet_eu.tokens`
`bq-1` | `bigquery-public-data`
ESDT tokens.

## Column details
* [STRING]    `_id`
  - The token identifier.
* [STRING]    `currentOwner`
  - The address in a bech32 format of the current owner of the token.
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
* [NUMERIC]   `data.royalties`
  - NFT royalties. Numeric value between 0 and 10000 (0 meaning 0% and 10000 meaning 100%).
* [STRING]    `data.tags`
* [STRING]    `data.uris`
  - A list of URIs.
* [BOOLEAN]   `data.whiteListedStorage`
  - Whether the token has whitelisted storage. An NFT/SFT has whitelisted storage if the URI belongs to one of the allowed decentralized storage services, such as IPFS or Pinata.
* [STRING]    `identifier`
  - The extended identifier. E.g. `TOKEN-01abdc-01`.
* [STRING]    `issuer`
  - The issuer of the token (address).
* [STRING]    `name`
  - The name of the token. It contains alphanumeric characters only.
* [FLOAT]     `nonce`
  - The sequence number of the token. This field is empty in the case of `FungibleESDT`.
* [NUMERIC]   `numDecimals`
  - The number of decimals.
* [RECORD]    `ownersHistory`
  - A list of all the owners of a token.
* [STRING]    `ownersHistory.address`
  - Address of (historical) owner.
* [TIMESTAMP] `ownersHistory.timestamp`
* [RECORD]    `properties`
* [BOOLEAN]   `properties.canAddSpecialRoles`
* [BOOLEAN]   `properties.canBurn`
* [BOOLEAN]   `properties.canChangeOwner`
* [BOOLEAN]   `properties.canCreateMultiShard`
* [BOOLEAN]   `properties.canFreeze`
* [BOOLEAN]   `properties.canMint`
* [BOOLEAN]   `properties.canPause`
* [BOOLEAN]   `properties.canTransferNFTCreateRole`
* [BOOLEAN]   `properties.canUpgrade`
* [BOOLEAN]   `properties.canWipe`
* [RECORD]    `roles`
  - A structure with information about the addresses that have certain roles for the token.
* [STRING]    `roles.ESDTRoleLocalBurn`
  - List of addresses with the role in question (see name of column).
* [STRING]    `roles.ESDTRoleLocalMint`
  - List of addresses with the role in question (see name of column).
* [STRING]    `roles.ESDTRoleNFTAddQuantity`
  - List of addresses with the role in question (see name of column).
* [STRING]    `roles.ESDTRoleNFTAddURI`
  - List of addresses with the role in question (see name of column).
* [STRING]    `roles.ESDTRoleNFTBurn`
  - List of addresses with the role in question (see name of column).
* [STRING]    `roles.ESDTRoleNFTCreate`
  - List of addresses with the role in question (see name of column).
* [STRING]    `roles.ESDTRoleNFTUpdateAttributes`
  - List of addresses with the role in question (see name of column).
* [STRING]    `roles.ESDTTransferRole`
  - List of addresses with the role in question (see name of column).
* [STRING]    `roles.ESDTRoleNFTCreateMultiShard`
  - List of addresses with the role in question (see name of column).
* [STRING]    `roles.ESDTRoleLocalNFTCreate`
  - List of addresses with the role in question (see name of column).
* [STRING]    `roles.ESDTRoleBurnForAll`
  - List of addresses with the role in question (see name of column).
* [STRING]    `ticker`
  - The token's ticker (uppercase alphanumeric characters).
* [TIMESTAMP] `timestamp`
  - The timestamp of the block in which the token was created.
* [STRING]    `token`
  - The token field is composed of the `ticker` field and a random sequence generated when the token is created(e.g. `ABCD-012345`).
* [STRING]    `type`
  - The type of the token. It can be `FungibleESDT`, `NonFungibleESDT`, `SemiFungibleESDT`, or `MetaESDT`.
* [BOOLEAN]   `frozen`
* [BOOLEAN]   `paused`
  - Whether the token is 'paused'.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
