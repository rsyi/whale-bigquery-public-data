# `cymbal_investments.trade_capture_report-2021-11-06T16_24_01`
`bq-1` | `bigquery-public-data`

## Column details
* [TIMESTAMP] `SendingTime`
  - Time the message was sent
* [STRING]    `TargetCompID`
  - Assigned value used to identify firm receiving message.
* [STRING]    `SenderCompID`
  - Assigned value used to identify firm sending message.
* [STRING]    `Symbol`
  - Trading symbol of the asset
* [INTEGER]   `Quantity`
  - Overall/total quantity (e.g. number of shares)
* [STRING]    `OrderID`
  - Order identifier
* [TIMESTAMP] `TransactTime`
  - Time the transaction occured
* [FLOAT]     `StrikePrice`
  - Price at which the CFD closed
* [FLOAT]     `LastPx`
  - Price at which the CFD was entered
* [TIMESTAMP] `MaturityDate`
  - Date of contract expiry
* [STRING]    `TradeReportID`
  - ID of this trade report
* [DATE]      `TradeDate`
  - Date trade was executed
* [STRING]    `CFICode`
  - Financial instrument classification code
* [RECORD]    `Sides`
* [STRING]    `Sides.Side`
  - Direction of the trade (long or short)
* [STRING]    `Sides.OrderID`
* [RECORD]    `Sides.PartyIDs`
* [STRING]    `Sides.PartyIDs.PartyID`
  - Counterparty identifier
* [STRING]    `Sides.PartyIDs.PartyIDSource`
* [STRING]    `Sides.PartyIDs.PartyRole`
  - Counterparty irole

-------------------------------------------------------------------------------
*Do not make edits above this line.*
