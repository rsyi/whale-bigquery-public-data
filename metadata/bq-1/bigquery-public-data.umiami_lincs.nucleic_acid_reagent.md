# `umiami_lincs.nucleic_acid_reagent`
`bq-1` | `bigquery-public-data`
Nucleic acid reagent metadata

## Column details
* [STRING]    `perturbagen_id`
  - Unique sequence to identify a perturbagen
* [STRING]    `perturbagen_class`
  - Type of the perturbagen, eg: small molecule, nucleic acid reagent
* [STRING]    `na_name`
  - The primary name of the siRNA or shRNA or any other genetic perturbagen as chosen by LINCS
* [STRING]    `na_lincs_id`
  - Unique LINCS internal identifier
* [STRING]    `na_type`
  - A controlled vocabulary specifying whether the reagent is Coding or Non-coding
* [STRING]    `na_target_gene_id`
  - The NCBI Entrez Gene ID for the gene targeted by the siRNA, shRNA or sgRNA
* [STRING]    `na_subtype`
  - A controlled vocabulary specifying the nucleic acid subtype. Coding subtypes: cDNA, Other. Non-coding subtypes: siRNA, sgRNA, shRNA, miRNA, Other
* [STRING]    `na_target_locus`
  - The gene name of the target. Can be a gene name/ miRNA gene name or coordinates if no gene name is available
* [STRING]    `na_target_locus_species`
  - A controlled vocabulary specifying the taxonomic species of the target locus
* [STRING]    `na_transcript_id`
  - The NCBI Reference Sequence IDs of the transcript(s) that are being targeted by the reagent
* [STRING]    `na_sense_sequence`
  - The nucleotide sequence of the sense (passenger) strand of the siRNA, the processed shRNA or the sgRNA. The ORF sequence of the cDNA which eventually gets transcribed and translated

-------------------------------------------------------------------------------
*Do not make edits above this line.*
