# `sec_quarterly_financials.measure_tag`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `measure_tag`
  - The unique identifier (name) for a tag in a specific taxonomy release. measure_tag:[tag]
* [STRING]    `version`
  - For a standard tag, an identifier for the taxonomy; otherwise the accession number where the tag was defined.
* [BOOLEAN]   `custom`
  - 1 if tag is custom (version=adsh), 0 if it is standard. Note: This flag is technically redundant with the version and adsh fields.
* [BOOLEAN]   `abstract`
  - 1 if the tag is not used to represent a numeric fact.
* [STRING]    `datatype`
  - If abstract=1, then NULL, otherwise the data type (e.g., monetary) for the tag.
* [STRING]    `i_or_d`
  - If abstract=1, then NULL; otherwise, I if the value is a point in time, or D if the value is a duration. i_or_d: [iord]
* [STRING]    `credit_or_debit`
  - If datatype = monetary, then the tag's natural accounting balance from the perspective of the balance sheet or income statement (debit or credit); if not defined, then NULL. credit_or_debit: [crdr]
* [STRING]    `tag_label`
  - If a standard tag, then the label text provided by the taxonomy, otherwise the text provided by the filer. A tag which had neither would have a NULL value here. tag_label: [tlabel]
* [STRING]    `doc`
  - The detailed definition for the tag, truncated to 2048 characters. If a standard tag, then the text provided by the taxonomy, otherwise the text assigned by the filer. Some tags have neither, in which case this field is NULL.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
