# `crypto_multiversx_mainnet_eu.scdeploys`
`bq-1` | `bigquery-public-data`
Smart contract deploys.

## Column details
* [STRING]    `_id`
  - The address of the smart contract.
* [STRING]    `deployTxHash`
  - The deployTxHash holds the hex encoded hash of the transaction that deployed the smart contract.
* [STRING]    `deployer`
  - The address in bech32 encoding of the smart contract deployer.
* [TIMESTAMP] `timestamp`
  - The timestamp of the block in which the smart contract was deployed.
* [RECORD]    `upgrades`
  - A list with details about the upgrades of the smart contract.
* [TIMESTAMP] `upgrades.timestamp`
  - The timestamp of the block in which the smart contract was upgraded.
* [STRING]    `upgrades.upgradeTxHash`
  - The hex encoded hash of the contract upgrade transaction.
* [STRING]    `upgrades.upgrader`
  - The bech32 encoded address of the sender of the contract upgrade transaction.
* [STRING]    `upgrades.codeHash`
  - The new code hash of the smart contract.
* [STRING]    `currentOwner`
  - The current owner of the smart contract.
* [STRING]    `initialCodeHash`
  - The initial code hash of the smart contract.
* [STRING]    `codeHash`
  - The current code hash of the smart contract.
* [RECORD]    `owners`
  - An array of smart contract owners, as they changed over time.
* [STRING]    `owners.txHash`
  - The 'change owner' transaction.
* [TIMESTAMP] `owners.timestamp`
  - The timestamp of the 'change owner' transaction.
* [STRING]    `owners.address`
  - The address of the owner.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
