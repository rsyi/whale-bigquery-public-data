# `crypto_polkadot.assets`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `para_id`
  - Para ID of the parachain representing this asset
* [STRING]    `chain_name`
  - Human readable chain name
* [STRING]    `asset`
  - JSON String representation of the asset
* [STRING]    `name`
  - Simple name of asset, if provided
* [STRING]    `currency_id`
  - Currency ID / Asset ID of asset, if provided in assets, tokens or some other chain pallet
* [STRING]    `symbol`
  - Human readable string token (e.g. DOT, ETH, USDC, DAI, ...)
* [INTEGER]   `decimals`
  - Decimals for asset
* [STRING]    `xcm_interior_key`
  - XCM Interior Key (v2 style) -- can be mapped directly to xcmassets
* [STRING]    `xc_contract_address`
  - Precompiled xcContract Address of asset, if available (on EVM Chains only)

-------------------------------------------------------------------------------
*Do not make edits above this line.*
