# `crypto_band.oracle_requests`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `block_height`
* [STRING]    `block_timestamp`
* [TIMESTAMP] `block_timestamp_truncated`
* [INTEGER]   `oracle_request_id`
* [RECORD]    `request`
* [INTEGER]   `request.oracle_script_id`
* [STRING]    `request.calldata`
* [STRING]    `request.requested_validators`
* [INTEGER]   `request.min_count`
* [INTEGER]   `request.request_height`
* [TIMESTAMP] `request.request_time`
* [RECORD]    `request.raw_requests`
* [INTEGER]   `request.raw_requests.external_id`
* [INTEGER]   `request.raw_requests.data_source_id`
* [STRING]    `request.raw_requests.calldata`
* [RECORD]    `reports`
* [RECORD]    `reports.raw_reports`
* [INTEGER]   `reports.raw_reports.exit_code`
* [BYTES]     `reports.raw_reports.data`
* [INTEGER]   `reports.raw_reports.external_id`
* [BOOLEAN]   `reports.in_before_resolve`
* [STRING]    `reports.validator`
* [RECORD]    `result`
* [RECORD]    `result.request_packet_data`
* [INTEGER]   `result.request_packet_data.oracle_script_id`
* [STRING]    `result.request_packet_data.calldata`
* [INTEGER]   `result.request_packet_data.ask_count`
* [INTEGER]   `result.request_packet_data.min_count`
* [RECORD]    `result.response_packet_data`
* [INTEGER]   `result.response_packet_data.request_id`
* [INTEGER]   `result.response_packet_data.ans_count`
* [INTEGER]   `result.response_packet_data.request_time`
* [INTEGER]   `result.response_packet_data.resolve_time`
* [INTEGER]   `result.response_packet_data.resolve_status`
* [STRING]    `result.response_packet_data.result`
* [RECORD]    `decoded_result`
* [STRING]    `decoded_result.calldata`
* [STRING]    `decoded_result.result`
* [RECORD]    `oracle_script`
* [STRING]    `oracle_script.owner`
* [STRING]    `oracle_script.name`
* [STRING]    `oracle_script.description`
* [STRING]    `oracle_script.filename`
* [STRING]    `oracle_script.schema`
* [STRING]    `oracle_script.source_code_url`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
