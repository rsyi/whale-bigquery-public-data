# `crypto_solana_mainnet_us.Instructions`
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
* [INTEGER]   `index`
  - The position of this instruction within all of instructions
* [INTEGER]   `parent_index`
  - The position of the parent instruction with all of the parent instructions. Only present for the inner instructions
* [STRING]    `accounts`
  - The accounts involved in the transaction that this instruction came from
* [STRING]    `data`
  - The instruction's raw data. Only present if the data source did not have a parser for the program
* [STRING]    `parsed`
  - The instruction's parsed info. Only present if the data source had a parser for the program, and the data could not be deserialized from the JSON string.
* [STRING]    `program`
  - The associated program that executes the instruction
* [STRING]    `program_id`
  - The account of the program that executes the instruction
* [STRING]    `instruction_type`
  - The type of the instruction
* [RECORD]    `params`
  - The instruction's parsed info, deserialized from the JSON string.
* [STRING]    `params.key`
  - The identifier of the instruction parameter
* [STRING]    `params.value`
  - The instruction parameter value

-------------------------------------------------------------------------------
*Do not make edits above this line.*
