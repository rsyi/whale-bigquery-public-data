# `sec_quarterly_financials.numbers`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `submission_number`
  - Accession Number. The 20-character string formed from the 18-digit number assigned by the Commission to each EDGAR submission. submission_number: [adsh]
* [STRING]    `company_name`
  - Name of registrant from the submission table. This corresponds to the name of the legal entity as recorded in EDGAR as of the filing date.
* [STRING]    `measure_tag`
  - The unique identifier (name) for a tag in a specific taxonomy release. measure_tag: [tag]
* [STRING]    `version`
  - For a standard tag, an identifier for the taxonomy; otherwise the accession number where the tag was defined.
* [INTEGER]   `period_end_date`
  - The end date for the data value, rounded to the nearest month end. period_end_date: [ddate]
* [INTEGER]   `number_of_quarters`
  - The count of the number of quarters represented by the data value, rounded to the nearest whole number. \"0\" indicates it is a point-in-time value. number_of_quarters: [qtrs]
* [STRING]    `units`
  - The unit of measure for the value. units: [uom]
* [STRING]    `dimension_hash`
  - The 32-byte hexadecimal key for the dimensional information in the DIM data set. dimension_hash: [dimh]
* [INTEGER]   `iprx`
  - A positive integer to distinguish different reported facts that otherwise would have the same primary key. For most purposes, data with iprx greater than 1 are not needed. The priority for the fact based on higher precision, closeness of the end date to a month end, and closeness of the duration to a multiple of three months. See fields dcml, durp and datp below.
* [FLOAT]     `value`
  - The value. This is not scaled, it is as found in the Interactive Data file, but is rounded to four digits to the right of the decimal point.
* [STRING]    `footnote`
  - The plain text of any superscripted footnotes on the value, if any, as shown on the statement page, truncated to 512 characters.
* [INTEGER]   `footnote_length`
  - Number of bytes in the plain text of the footnote prior to truncation; zero if no footnote. footnote_length: [footlen]
* [INTEGER]   `num_dimensions`
  - Small integer representing the number of dimensions. Note that this value is a function of the dimension segments. num_dimensions: [dimn]
* [STRING]    `coregistrant`
  - If specified, indicates a specific co-registrant, the parent company, or other entity (e.g., guarantor). NULL indicates the consolidated entity. Note that this value is a function of the dimension segments. coregistrant: [coreg]
* [FLOAT]     `duration_fraction`
  - The difference between the reported fact duration and the quarter duration (qtrs), expressed as a fraction of 1. For example, a fact with duration of 120 days rounded to a 91-day quarter has a durp value of 29/91 = +0.3187. duration_fraction: [durp]
* [FLOAT]     `date_fraction`
  - The difference between the reported fact date and the month-end rounded date (ddate), expressed as a fraction of 1. For example, a fact reported for 29/Dec, with ddate rounded to 31/Dec, has a datp value of minus 2/31 = -0.0645. date_fraction: [datp]
* [INTEGER]   `decimal`
  - The value of the fact \"decimals\" attribute, with INF represented by 32767. decimal: [dcml]

-------------------------------------------------------------------------------
*Do not make edits above this line.*
