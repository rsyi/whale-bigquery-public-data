# `umiami_lincs.signature`
`bq-1` | `bigquery-public-data`
Non-redundant list of signatures per assays, LINCS dataset Identifiers and LINCS Data and Signature Generation Center DSGC.

## Column details
* [STRING]    `signature_id`
  - Unique sequence to identify a signature. Maps to signature_id in readout, perturbagen, and model_system tables
* [STRING]    `bioassay_type`
  - Categorization of bioassays signatures based on the property or process the assay is interrogating, e.g.: proteomics, epigenetic, gene expression. See http://www.bioassayontology.org/bao#BAO_0000008
* [STRING]    `data_level`
  - LINCS conceptual scale of measuring data
* [STRING]    `dataset_id`
  - LINCS Dataset Identifier, see citation guidelines under terms of use
* [STRING]    `source_name`
  - LINCS Data and Signature Generation Center (DSGC) dataset source eg: Broad Institute, HMS, etc
* [STRING]    `external_id`
  - Identifier of the signature from the LINCS Data and Signature Generation Center DSGC eg: LJP008_A375_24H:H02, AML001_HL60_24H:BRD-K03439359:10

-------------------------------------------------------------------------------
*Do not make edits above this line.*
