# `nlm_rxnorm.rxnsat_12_20`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `rxcui`
  - Unique identifier for concept (concept id)
* [STRING]    `lui`
  - Unique identifier for term (no value provided)
* [STRING]    `sui`
  - Unique identifier for string (no value provided)
* [STRING]    `rxaui`
  - RxNorm atom identifier (RXAUI) or RxNorm relationship identifier (RUI).
* [STRING]    `stype`
  - The name of the column in RXNCONSO.RRF or RXNREL.RRF that contains the identifier to which the attribute is attached, e.g., CUI, AUI.
* [STRING]    `code`
  - Most useful source asserted identifier (if the source vocabulary has more than one identifier), or a RxNorm-generated source entry identifier (if the source vocabulary has none.)
* [STRING]    `atui`
  - Unique identifier for attribute
* [STRING]    `satui`
  - Source asserted attribute identifier (optional - present if it exists)
* [STRING]    `atn`
  - Attribute name. Possible values appear in RXNDOC.RRF and are described on the UMLS Attribute Names page
* [STRING]    `sab`
  - Abbreviation of the source of the attribute. Possible values appear in RXNSAB.RRF and are listed on the UMLS Source Vocabularies page
* [STRING]    `atv`
  - Attribute value described under specific attribute name on the UMLS Attribute Names page. A few attribute values exceed 1,000 characters. Many of the abbreviations used in attribute values are explained in RXNDOC.RRF and included UMLS Abbreviations Used in Data Elements page
* [STRING]    `suppress`
  - Suppressible flag. Values = O, Y, or N. Reflects the suppressible status of the attribute. N - Attribute is not suppressed. O - Attribute is suppressed at source level. Y - Attribute is suppressed by RxNorm editors.
* [STRING]    `cvf`
  - Content view flag. RxNorm includes one value, 4096, to denote inclusion in the Current Prescribable Content subset. All rows with CVF=4096 can be found in the subset.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
