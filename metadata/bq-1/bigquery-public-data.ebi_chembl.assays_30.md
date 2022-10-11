# `ebi_chembl.assays_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `assay_id`
  - Unique ID for the assay
* [INTEGER]   `doc_id`
  - Foreign key to documents table
* [STRING]    `description`
  - Description of the reported assay
* [STRING]    `assay_type`
  -  Assay classification, e.g. B=Binding assay, A=ADME assay, F=Functional assay
* [STRING]    `assay_test_type`
  - Type of assay system (i.e., in vivo or in vitro)
* [STRING]    `assay_category`
  - screening, confirmatory (ie: dose-response), summary, panel or other.
* [STRING]    `assay_organism`
  -  Name of the organism for the assay system (e.g., the organism, tissue or cell line in which an assay was performed). May differ from the target organism (e.g., for a human protein expressed in non-human cells, or pathogen-infected human cells).
* [INTEGER]   `assay_tax_id`
  - NCBI tax ID for the assay organism.
* [STRING]    `assay_strain`
  -  Name of specific strain of the assay organism used (where known)
* [STRING]    `assay_tissue`
  -  Name of tissue used in the assay system (e.g., for tissue-based assays) or from which the assay system was derived (e.g., for cell/subcellular fraction-based assays).
* [STRING]    `assay_cell_type`
  -  Name of cell type or cell line used in the assay system (e.g., for cell-based assays).
* [STRING]    `assay_subcellular_fraction`
  -  Name of subcellular fraction used in the assay system (e.g., microsomes, mitochondria).
* [INTEGER]   `tid`
  - Target identifier to which this assay has been mapped. Foreign key to target_dictionary. From ChEMBL_15 onwards, an assay will have only a single target assigned.
* [STRING]    `relationship_type`
  -  Flag indicating of the relationship between the reported target in the source document and the assigned target from TARGET_DICTIONARY. Foreign key to RELATIONSHIP_TYPE table.
* [INTEGER]   `confidence_score`
  - Confidence score, indicating how accurately the assigned target(s) represents the actually assay target. Foreign key to CONFIDENCE_SCORE table. 0 means uncurated/unassigned, 1 = low confidence to 9 = high confidence.
* [STRING]    `curated_by`
  - Indicates the level of curation of the target assignment. Foreign key to curation_lookup table.
* [INTEGER]   `src_id`
  - Foreign key to source table
* [STRING]    `src_assay_id`
  - Identifier for the assay in the source database/deposition (e.g., pubchem AID)
* [STRING]    `chembl_id`
  - ChEMBL identifier for this assay (for use on web interface etc)
* [INTEGER]   `cell_id`
  - Foreign key to cell dictionary. The cell type or cell line used in the assay
* [STRING]    `bao_format`
  - ID for the corresponding format type in BioAssay Ontology (e.g., cell-based, biochemical, organism-based etc)
* [INTEGER]   `tissue_id`
  - ID for the corresponding tissue/anatomy in Uberon. Foreign key to tissue_dictionary
* [INTEGER]   `variant_id`
  - Foreign key to variant_sequences table. Indicates the mutant/variant version of the target used in the assay (where known/applicable)
* [STRING]    `aidx`
  - The Depositor Defined Assay Identifier

-------------------------------------------------------------------------------
*Do not make edits above this line.*
