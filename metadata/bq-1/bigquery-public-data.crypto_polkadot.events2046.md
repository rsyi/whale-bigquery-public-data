# `crypto_polkadot.events2046`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `event_id`
  - Event ID of the event ('blocknumber-extrinsicIndex-eventIdx')
* [STRING]    `section`
  - Event section of the event
* [STRING]    `method`
  - Event method of the event
* [JSON]      `data`
  - JSON data of the event
* [STRING]    `extrinsic_id`
  - Extrinsic ID of the extrinsic that includes this event
* [STRING]    `extrinsic_hash`
  - Extrinsic hash of the extrinsic that includes this event
* [TIMESTAMP] `block_time`
  - Block time (unix time) of the block that includes this event
* [INTEGER]   `block_number`
  - Block number of the block that includes this event
* [STRING]    `block_hash`
  - Block hash of the block that includes this event
* [JSON]      `data_decoded`
  - Decoded JSON data of the event, if available

-------------------------------------------------------------------------------
*Do not make edits above this line.*
