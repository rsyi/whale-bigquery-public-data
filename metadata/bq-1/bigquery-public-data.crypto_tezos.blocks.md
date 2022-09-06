# `crypto_tezos.blocks`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `level`
  - The height of the block, from the genesis block
* [INTEGER]   `proto`
  - Number of protocol changes since genesis (mod 256)
* [STRING]    `predecessor`
  - The hash of the preceding block
* [TIMESTAMP] `timestamp`
  - The timestamp at which the block is claimed to have been created
* [INTEGER]   `validation_pass`
  - Number of validation passes (also number of lists of lists of operations)
* [STRING]    `operations_hash`
  - The hash of a list of root hashes of Merkle trees of operations. There is one list of operations per validation pass
* [STRING]    `fitness`
  - A sequence of sequences of unsigned bytes, ordered by length and then lexicographically. It represents the claimed fitness of the chain ending in this block
* [STRING]    `context`
  - Hash of context (Base58Check-encoded)
* [STRING]    `protocol`
  - Protocol version
* [STRING]    `chain_id`
  - Network identifier (Base58Check-encoded)
* [STRING]    `block_hash`
  - Block identifier (Base58Check-encoded)
* [STRING]    `nonce_hash`
  - A commitment to a random number, used to generate entropy on the chain
* [INTEGER]   `consumed_gas`
  - Gas consumed in a block
* [STRING]    `baker`
  - Public key hash of block baker (Base58Check-encoded)
* [STRING]    `voting_period_kind`
  - The kind of the voting period
* [INTEGER]   `cycle`
  - Block cycle
* [INTEGER]   `cycle_position`
  - Cycle position
* [INTEGER]   `voting_period`
  - Voting period
* [INTEGER]   `voting_period_position`
  - Voting period position
* [BOOLEAN]   `expected_commitment`
  - Expected commitment
* [INTEGER]   `number_of_operation_groups`
  - The number of operation groups in a block
* [INTEGER]   `number_of_operations`
  - The number of operations in a block

-------------------------------------------------------------------------------
*Do not make edits above this line.*
