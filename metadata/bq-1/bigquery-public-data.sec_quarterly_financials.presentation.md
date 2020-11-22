# `sec_quarterly_financials.presentation`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `submission_number`
  - Accession Number. The 20-character string formed from the 18-digit number assigned by the Commission to each EDGAR submission. submission_number: [adsh]
* [INTEGER]   `report`
  - Represents the report grouping. The numeric value refers to the \"R file\" as computed by the renderer and posted on the EDGAR website. Note that in some situations the numbers skip.
* [INTEGER]   `line`
  - Represents the tag's presentation line order for a given report. Together with the statement and report field, presentation location, order and grouping can be derived.
* [STRING]    `statement`
  - The financial statement location to which the value of the \"report\" field pertains. statement: [stmt]
* [BOOLEAN]   `presented_parenthetically`
  - 1 indicates that the value was presented \"parenthetically\" instead of in fields within the financial statements. For example: Receivables (net of allowance for bad debts of USD 200 in 2012) USD 700 presented_parenthetically: [inpth]
* [STRING]    `rfile`
  - The type of interactive data file rendered on the EDGAR website, H = .htm file, X = .xml file.
* [STRING]    `measure_tag`
  - The tag chosen by the filer for this line item. measure_tag: [tag]
* [STRING]    `version`
  - The taxonomy identifier if the tag is a standard tag, otherwise adsh.
* [STRING]    `preferred_role`
  - The XBRL link \"role\" of the preferred label, using only the portion of the role URI after the last \"/\". preferred_role: [prole]
* [STRING]    `preferred_label`
  - The text presented on the line item, also known as a \"preferred\" label. preferred_label: [plabel]
* [BOOLEAN]   `negating`
  - Flag to indicate whether the prole is treated as negating by the renderer.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
