# `crypto_aptos_testnet_us.blocks`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `block_hash`
  - The block's hash.
* [TIMESTAMP] `block_timestamp`
  - The timestamp of when the block was finalized.
* [RECORD]    `block_unixtimestamp`
  - The unix timestamp of when the block was finalized.
* [INTEGER]   `block_unixtimestamp.seconds`
  - The number of seconds since the unix epoch.
* [INTEGER]   `block_unixtimestamp.nanos`
  - The number of nanoseconds that have elapsed since the beginning of the second specified in the seconds field.
* [INTEGER]   `block_height`
  - The block height.
* [INTEGER]   `blockmetadata_tx_version`
  - The transaction version belongs to the block metadata transaction.
* [INTEGER]   `round`
  - The shared counter used to select leaders during an epoch of the consensus protocol.
* [BYTES]     `previous_block_votes_bitvec`
  - The previous vote blocks.
* [STRING]    `proposer`
  - The address of the account that proposed the block.  Represented as a hex encoded 32 byte Aptos account address represented as a 64 character string, left-padded with zeros.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
