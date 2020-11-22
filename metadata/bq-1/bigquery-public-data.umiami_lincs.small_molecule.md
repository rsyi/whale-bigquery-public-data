# `umiami_lincs.small_molecule`
`bq-1` | `bigquery-public-data`
Compound metadata

## Column details
* [STRING]    `perturbagen_id`
  - Unique sequence to identify a perturbagen. Maps to perturbagen_id in perturbagen table.
* [STRING]    `perturbagen_class`
  - Type of the perturbagen, eg: small molecule, nucleic acid reagent
* [STRING]    `sm_name`
  - The primary name for the (parent) compound (in a standardized representation) as chosen by LINCS
* [STRING]    `sm_pubchem_cid`
  - CID that corresponds to the standardized parent compound in NCBIs PubChem database
* [STRING]    `sm_chebi_id`
  - ChEBI ID that corresponds to the standardized parent compound
* [STRING]    `sm_lincs_id`
  - The global LINCS ID (parent) compound (in a standardized representation)
* [STRING]    `sm_smiles_parent`
  - Canonical isomeric SMILES representation of parent (standardized) chemical structure
* [STRING]    `sm_inchi_parent`
  - InChi representation of parent (standardized) chemical structure
* [STRING]    `sm_inchi_key_parent`
  - InChi key of parent (standardized) chemical structure

-------------------------------------------------------------------------------
*Do not make edits above this line.*
