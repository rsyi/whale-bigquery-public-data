# `crypto_kusama.xcmassets`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `xcm_interior_key`
  - XCM Interior Key Canonicalized [flattened xcmV1Multilocation from polkadot.js v1 with network field added]
* [STRING]    `xcm_v1_multilocation_byte`
  - Polkadot.js v1 decodable bytes for XCM
* [STRING]    `xcm_v1_multilocation`
  - Encodable JSON [polkadot.js v1 API]
* [STRING]    `symbol`
  - Human readable string token (e.g. DOT, ETH, USDC, DAI, ...)
* [INTEGER]   `decimals`
  - Decimals for asset
* [INTEGER]   `para_id`
  - Native Para ID for XCM asset
* [STRING]    `chain_name`
  - Human readable chain name
* [STRING]    `interior_type`
  - Number of arguments in XCM V1 Multilocation
* [STRING]    `source`
  - Para ID sources array
* [STRING]    `xc_contract_address`
  - For EVM Chains, precompiled Contract Address (if available)
* [STRING]    `xc_currency_id`
  - Local indexes, used to specify Foreign Asset in each chain
* [INTEGER]   `confidence`
  - Count of non-native parachains that have published the same multilocation

-------------------------------------------------------------------------------
*Do not make edits above this line.*
