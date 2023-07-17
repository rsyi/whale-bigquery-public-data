# `blockchain_analytics_ethereum_mainnet_us.accounts_state`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `block_hash`
  - Hash of the block this account state was indexed from.
* [INTEGER]   `block_number`
  - Number of the block this account state was indexed from.
* [TIMESTAMP] `block_timestamp`
  - Unix timestamp when the block was added to the blockchain.
* [STRING]    `address`
  - Address identifying the account.
* [INTEGER]   `nonce`
  - Nonce (transaction count) associated with this account at this block.
* [BIGNUMERIC] `balance`
  - Native Ether balance of the account in Wei. A decimal number represented as a BIGNUMERIC to preserve up to 128-bit numeric precision.
* [STRING]    `balance_lossless`
  - Native Ether balance of the account in Wei. A decimal number represented in STRING format to preserve full 256-bit numeric precision.
* [STRING]    `code_hash`
  - Hash of the code of the account. For all externally-owned accounts this will be "0xc5d2460186f7233c927e7db2dcc703c0e500b653ca82273b7bfad8045d85a470". This is the hash when there is no code present.
* [STRING]    `code`
  - Compiled bytecode of this account in hexadecimal format, given the account is a smart contract.
* [STRING]    `account_proof`
  - Merkle proof for verifying the account balance at the given block. An array of RLP-serialized Merkle tree nodes, starting with the state root node.
* [STRING]    `storage_hash`
  - Hash of the storage root representing a Merkle proof. For all non-smart contract accounts this will be "0x56e81f171bcc55a6ff8345e692c0f86e5b48e01b996cadc001622fb5e363b421". This is the hash of an empty Merkle tree.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
