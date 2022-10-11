# `ebi_chembl.bio_component_sequences_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `component_id`
  - Primary key. Unique identifier for each of the molecular components of biotherapeutics in ChEMBL (e.g., antibody chains, recombinant proteins, synthetic peptides).
* [STRING]    `component_type`
  - Type of molecular component (e.g., 'PROTEIN','DNA','RNA').
* [STRING]    `description`
  -  Description/name of molecular component.
* [STRING]    `sequence`
  - Sequence of the biotherapeutic component.
* [STRING]    `sequence_md5sum`
  - MD5 checksum of the sequence.
* [INTEGER]   `tax_id`
  - NCBI tax ID for the species from which the sequence is derived. May be null for humanized monoclonal antibodies, synthetic peptides etc.
* [STRING]    `organism`
  -  Name of the species from which the sequence is derived.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
