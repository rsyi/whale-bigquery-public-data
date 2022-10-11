# `ebi_chembl.component_sequences_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `component_id`
  - Primary key. Unique identifier for the component.
* [STRING]    `component_type`
  - Type of molecular component represented (e.g., 'PROTEIN','DNA','RNA').
* [STRING]    `accession`
  - Accession for the sequence in the source database from which it was taken (e.g., UniProt accession for proteins).
* [STRING]    `sequence`
  - A representative sequence for the molecular component, as given in the source sequence database (not necessarily the exact sequence used in the assay).
* [STRING]    `sequence_md5sum`
  - MD5 checksum of the sequence.
* [STRING]    `description`
  -  Description/name for the molecular component, usually taken from the source sequence database.
* [INTEGER]   `tax_id`
  - NCBI tax ID for the sequence in the source database (i.e., species that the protein/nucleic acid sequence comes from).
* [STRING]    `organism`
  -  Name of the organism the sequence comes from.
* [STRING]    `db_source`
  - The name of the source sequence database from which sequences/accessions are taken. For UniProt proteins, this field indicates whether the sequence is from SWISS-PROT or TREMBL.
* [STRING]    `db_version`
  - The version of the source sequence database from which sequences/accession were last updated.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
