# `cms_codes.icd10_procedures_2019`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `order_number`
  - Unique identifier that makes it easier for users to communicate a range of codes
* [STRING]    `pcs_code`
  - Procedure code
* [BOOLEAN]   `is_header_code`
  - TRUE - The code is a “header” code and not valid for HIPAA-covered transactions. FALSE - The code is valid for submission for HIPAA-covered transactions.
* [STRING]    `short_description`
  - Short text description of the procedure
* [STRING]    `long_description`
  - Full text description of the procedure

-------------------------------------------------------------------------------
*Do not make edits above this line.*
