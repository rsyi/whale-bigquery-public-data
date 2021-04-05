# `nlm_rxnorm.rxnconso_04_21`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `rxcui`
  - RxNorm Unique identifier for concept (concept ID)
* [STRING]    `lat`
  - Language of Term
* [STRING]    `ts`
  - Term status (no value provided)
* [STRING]    `lui`
  - Unique identifier for term (no value provided)
* [STRING]    `stt`
  - String type (no value provided)
* [STRING]    `sui`
  - Unique identifier for string (no value provided)
* [STRING]    `ispref`
  - Atom status - preferred (Y) or not (N) for this string within this concept (no value provided)
* [STRING]    `rxaui`
  - Unique identifier for atom (RxNorm Atom ID)
* [STRING]    `saui`
  - Source asserted atom identifier [optional]
* [STRING]    `scui`
  - Source asserted concept identifier [optional]
* [STRING]    `sdui`
  - Source asserted descriptor identifier [optional]
* [STRING]    `sab`
  - Source abbreviation
* [STRING]    `tty`
  - Term type in source
* [STRING]    `code`
  - "Most useful" source asserted identifier (if the source vocabulary has more than one identifier), or a RxNorm-generated source entry identifier (if the source vocabulary has none.)
* [STRING]    `str`
  - String
* [STRING]    `srl`
  - Source Restriction Level (no value provided)
* [STRING]    `suppress`
  - Suppressible flag. Values = N, O, Y, or E. N - not suppressible. O - Specific individual names (atoms) set as Obsolete because the name is no longer provided by the original source. Y - Suppressed by RxNorm editor. E - unquantified, non-prescribable drug with related quantified, prescribable drugs. NLM strongly recommends that users not alter editor-assigned suppressibility.
* [STRING]    `cvf`
  - Content view flag. RxNorm includes one value, '4096', to denote inclusion in the Current Prescribable Content subset. All rows with CVF='4096' can be found in the subset.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
