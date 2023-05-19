# `crypto_kusama.chains`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `para_id`
  - Para ID of the parachain, or 0 if the chain is the relay chain
* [STRING]    `id`
  - String representation of the chain, in lowercase without spaces, suitable for subdomains
* [STRING]    `chain_name`
  - String representation of the chain, in mixed case potentially with spaces, suitable for display
* [INTEGER]   `ss58_prefix`
  - SS58 Prefix used for SS58 Encoded addresses
* [STRING]    `symbol`
  - Primary native token of the chain
* [BOOLEAN]   `is_evm`
  - true if the chain supports EVM Contracts, otherwise false
* [BOOLEAN]   `is_wasm`
  - true if the chain supports WASM Contracts, otherwise false
* [STRING]    `icon_url`
  - Icon URL

-------------------------------------------------------------------------------
*Do not make edits above this line.*
