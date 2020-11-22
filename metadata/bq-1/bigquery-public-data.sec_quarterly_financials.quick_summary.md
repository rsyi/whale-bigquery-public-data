# `sec_quarterly_financials.quick_summary`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `submission_number`
  - Accession Number. The 20-character string formed from the 18-digit number assigned by the Commission to each EDGAR submission. submission_number: [adsh]
* [STRING]    `company_name`
  - Name of registrant from the submission table. This corresponds to the name of the legal entity as recorded in EDGAR as of the filing date.
* [STRING]    `measure_tag`
  - The unique identifier (name) for a tag in a specific taxonomy release. measure_tag: [tag]
* [STRING]    `period_end_date`
  - The end date for the data value, rounded to the nearest month end. period_end_date: [ddate]
* [FLOAT]     `value`
  - The value. This is not scaled, it is as found in the Interactive Data file, but is rounded to four digits to the right of the decimal point.
* [STRING]    `units`
  - The unit of measure for the value. units: [uom]
* [INTEGER]   `number_of_quarters`
  - The count of the number of quarters represented by the data value, rounded to the nearest whole number. \"0\" indicates it is a point-in-time value. number_of_quarters: [qtrs]
* [STRING]    `version`
  - For a standard tag, an identifier for the taxonomy; otherwise the accession number where the tag was defined.
* [INTEGER]   `central_index_key`
  - Central Index Key (CIK). Ten digit number assigned by the Commission to each registrant that submits filings. central_index_key: [cik]
* [STRING]    `ein`
  - Employee Identification Number, 9 digit identification number assigned by the Internal Revenue Service to business entities operating in the United States.
* [STRING]    `sic`
  - Standard Industrial Classification (SIC). Four digit code assigned by the Commission as of the filing date, indicating the registrant's type of business.
* [STRING]    `fiscal_year_end`
  - Fiscal Year End Date. fiscal_year_end: [fye]
* [STRING]    `form`
  - The submission type of the registrant's filing.
* [INTEGER]   `fiscal_year`
  - Fiscal Year Focus (as defined in EFM Ch. 6). fiscal_year: [fy]
* [STRING]    `fiscal_period_focus`
  - Fiscal Period Focus (as defined in EFM Ch. 6) within Fiscal Year. The 10-Q for the 1st, 2nd and 3rd quarters would have a fiscal period focus of Q1, Q2 (or H1), and Q3 (or M9) respectively, and a 10-K would have a fiscal period focus of FY. fiscal_period_focus: [fp]
* [INTEGER]   `date_filed`
  - The date of the registrant's filing with the Commission. date_filed: [filed]
* [TIMESTAMP] `date_accepted`
  - The acceptance date and time of the registrant's filing with the Commission. Filings accepted after 5:30pm EST are considered filed on the following business day. date_accepted: [accepted]

-------------------------------------------------------------------------------
*Do not make edits above this line.*
