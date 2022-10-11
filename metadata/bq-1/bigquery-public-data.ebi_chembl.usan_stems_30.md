# `ebi_chembl.usan_stems_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `usan_stem_id`
  - Numeric primary key.
* [STRING]    `stem`
  - Stem defined for use in United States Adopted Names.
* [STRING]    `subgroup`
  - More specific subgroup of the stem defined for use in United States Adopted Names.
* [STRING]    `annotation`
  - Meaning of the stem (e.g., the class of compound it applies to).
* [STRING]    `stem_class`
  -  Indicates whether stem is used as a Prefix/Infix/Suffix.
* [STRING]    `major_class`
  -  Protein family targeted by compounds of this class (e.g., GPCR/Ion channel/Protease) where known/applicable.
* [INTEGER]   `who_extra`
  - Stem not represented in USAN list, but added from WHO INN stem list (where set to 1).

-------------------------------------------------------------------------------
*Do not make edits above this line.*
