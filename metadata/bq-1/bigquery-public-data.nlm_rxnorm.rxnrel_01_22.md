# `nlm_rxnorm.rxnrel_01_22`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `rxcui1`
  - Unique identifier of first concept
* [STRING]    `rxaui1`
  - Unique identifier for first atom
* [STRING]    `stype1`
  - The name of the column in RXNCONSO.RRF that contains the identifier used for the first concept or first atom in source of the relationship
* [STRING]    `rel`
  - Relationship of second concept or atom to first concept or atom
* [STRING]    `rxcui2`
  - Unique identifier of second concept
* [STRING]    `rxaui2`
  - Unique identifier for second atom
* [STRING]    `stype2`
  - The name of the column in RXNCONSO.RRF that contains the identifier used for the second concept or second atom in the source of the relationship
* [STRING]    `rela`
  - Additional (more specific) relationship label (optional)
* [STRING]    `rui`
  - Unique identifier for relationship
* [STRING]    `srui`
  - Source asserted relationship identifier, if present (no value provided)
* [STRING]    `sab`
  - Abbreviation of the source of relationship
* [STRING]    `sl`
  - Source of relationship labels (no value provided)
* [STRING]    `dir`
  - Source asserted directionality flag. (no value provided) Y indicates that this is the direction of the relationship in its source; N indicates that it is not; a blank indicates that it is not important or has not yet been determined.
* [STRING]    `rg`
  - Machine generated and unverified indicator (optional)
* [STRING]    `suppress`
  - Suppressible flag. Values = Y, E, or N. Reflects the suppressible status of the relationship; not yet in use. See also SUPPRESS in MRCONSO.RRF and MRDEF.RRF and MRREL.RRF in the UMLS Reference Manual.
* [STRING]    `cvf`
  - Content view flag. RxNorm includes one value, 4096, to denote inclusion in the Current Prescribable Content subset. All rows with CVF=4096 can be found in the subset.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
