# `ebi_chembl.variant_sequences_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `variant_id`
  - Primary key, numeric ID for each sequence variant.
* [STRING]    `mutation`
  - Details of variant(s) used, with residue positions adjusted to match provided sequence.
* [STRING]    `accession`
  - UniProt accesion for the representative sequence used as the base sequence (without variation).
* [INTEGER]   `version`
  - Version of the UniProt sequence used as the base sequence.
* [INTEGER]   `isoform`
  - Details of the UniProt isoform used as the base sequence where relevant.
* [STRING]    `sequence`
  - Variant sequence formed by adjusting the UniProt base sequence with the specified mutations/variations.
* [STRING]    `organism`
  -  Organism from which the sequence was obtained.
* [INTEGER]   `tax_id`
  - NCBI Tax ID for the organism from which the sequence was obtained

-------------------------------------------------------------------------------
*Do not make edits above this line.*
