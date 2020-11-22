# `sec_quarterly_financials.txt`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `submission_number`
  - Accession Number. The 20-character string formed from the 18-digit number assigned by the Commission to each EDGAR submission. submission_number: [adsh]
* [STRING]    `measure_tag`
  - The unique identifier (name) for a tag in a specific taxonomy release. measure_tag: [tag]
* [STRING]    `version`
  - For a standard tag, an identifier for the taxonomy; otherwise the accession number where the tag was defined. For example, \"invest/2013\" indicates that the tag is defined in the 2013 INVEST taxonomy.
* [INTEGER]   `period_end_date`
  - The end date for the data value, rounded to the nearest month end. period_end_date:[ddate]
* [INTEGER]   `num_quarters`
  - The count of the number of quarters represented by the data value, rounded to the nearest whole number. A point in time value is represented by 0. num_quarters:[qtrs]
* [INTEGER]   `iprx`
  - A positive integer to distinguish different reported facts that otherwise would have the same primary key. For most purposes, data with iprx greater than 1 are not needed. The priority for the fact based on higher precision, closeness of the end date to a month end, and closeness of the duration to a multiple of three months. See fields dcml, durp and datp below.
* [STRING]    `language`
  - The ISO language code of the fact content. language:[lang]
* [INTEGER]   `language_decimal`
  - The value of the fact \"xml:lang\" attribute, en-US represented by 32767, other \"en\" dialects having lower values, and other languages lower still. language_decimal: [dcml]
* [FLOAT]     `duration_fraction`
  - The difference between the reported fact duration and the quarter duration (qtrs), expressed as a fraction of 1. For example, a fact with duration of 120 days rounded to a 91-day quarter has a durp value of 29/91 = +0.3187. duration_fraction: [durp]
* [FLOAT]     `date_fraction`
  - The difference between the reported fact date and the month-end rounded date (ddate), expressed as a fraction of 1. For example, a fact reported for 29/Dec, with ddate rounded to 31/Dec, has a datp value of minus 2/31 = -0.0645. date_fraction: [datp]
* [STRING]    `dimension_hash`
  - The 32-byte hexadecimal key for the dimensional information in the DIM data set. dimension_hash: [dimh]
* [INTEGER]   `num_dimensions`
  - Small integer representing the number of dimensions, useful for sorting. Note that this value is function of the dimension segments. num_dimensions: [dimn]
* [STRING]    `coregistrant`
  - If specified, indicates a specific co-registrant, the parent company, or other entity (e.g., guarantor). NULL indicates the consolidated entity. Note that this value is a function of the dimension segments. coregistrant: [coreg]
* [BOOLEAN]   `escaped`
  - Flag indicating whether the value has had tags removed.
* [INTEGER]   `source_length`
  - Number of bytes in the original, unprocessed value. Zero indicates a NULL value. source_length: [srclen]
* [INTEGER]   `text_length`
  - The original length of the whitespace normalized value, which may have been greater than 8192. text_length: [txtlen]
* [STRING]    `footnote`
  - The plain text of any superscripted footnotes on the value, as shown on the page, truncated to 512 characters, or if there is no footnote, then this field will be blank.
* [INTEGER]   `footnote_length`
  - Number of bytes in the plain text of the footnote prior to truncation. footnote_length: [footlen]
* [STRING]    `context`
  - The value of the contextRef attribute in the source XBRL document, which can be used to recover the original HTML tagging if desired.
* [STRING]    `value`
  - The value, with all whitespace normalized, that is, all sequences of line feeds, carriage returns, tabs, non-breaking spaces, and spaces having been collapsed to a single space, and no leading or trailing spaces. Escaped XML that appears in EDGAR \"Text Block\" tags is processed to remove all mark-up (comments, processing instructions, elements, attributes). The value is truncated to a maximum number of bytes. The resulting text is not intended for end user display but only for text analysis applications.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
