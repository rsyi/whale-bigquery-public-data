# `deepmind_alphafold.metadata`
`bq-1` | `bigquery-public-data`
Metadata for the AlphaFold Protein Structure Database

## Column details
* [INTEGER]   `allVersions`
  - An array of AFDB versions this prediction has had
* [INTEGER]   `latestVersion`
  - The latest AFDB version for this prediction
* [STRING]    `organismCommonNames`
  - List of common organism names
* [INTEGER]   `uniprotEnd`
  - Number of the last residue in the entry relative to the UniProt entry. This is equal to the length of the protein unless we are dealing with protein fragments
* [STRING]    `proteinShortNames`
  - Short names of the protein
* [INTEGER]   `uniprotStart`
  - Number of the first residue in the entry relative to the UniProt entry. This is 1 unless we are dealing with protein fragments
* [FLOAT]     `fractionPlddtConfident`
  - Fraction of the residues in the prediction with pLDDT between 70 and 90
* [STRING]    `organismSynonyms`
  - List of synonyms for the organism
* [FLOAT]     `fractionPlddtVeryHigh`
  - Fraction of the residues in the prediction with pLDDT greater than 90
* [STRING]    `proteinFullNames`
  - Full names of the protein
* [FLOAT]     `globalMetricValue`
  - The mean pLDDT of this prediction
* [STRING]    `organismScientificName`
  - The scientific name of the organism
* [STRING]    `uniprotDescription`
  - The name recommended by the UniProt consortium
* [FLOAT]     `fractionPlddtLow`
  - Fraction of the residues in the prediction with pLDDT between 50 and 70
* [STRING]    `uniprotAccession`
  - Uniprot accession ID
* [STRING]    `sequenceChecksum`
  - CRC64 hash of the sequence. Can be used for cheaper lookups.
* [INTEGER]   `taxId`
  - NCBI taxonomic id of the originating species
* [STRING]    `uniprotId`
  - The Uniprot EntryName field
* [DATE]      `modelCreatedDate`
  - The date of creation for this entry, e.g. "2022-06-01"
* [FLOAT]     `fractionPlddtVeryLow`
  - Fraction of the residues in the prediction with pLDDT less than 50
* [DATE]      `sequenceVersionDate`
  - Date when the sequence data was last modified in UniProt
* [STRING]    `entryId`
  - The AFDB entry ID, e.g. "AF-Q1HGU3-F1"
* [STRING]    `geneSynonyms`
  - Additional synonyms for the gene
* [STRING]    `uniprotSequence`
  - Amino acid sequence for this prediction
* [STRING]    `gene`
  - The name of the gene if known, e.g. "COII"
* [BOOLEAN]   `isReferenceProteome`
  - Is this protein part of the reference proteome?
* [BOOLEAN]   `isReviewed`
  - Has this protein been reviewed, i.e. is it part of SwissProt?

-------------------------------------------------------------------------------
*Do not make edits above this line.*
