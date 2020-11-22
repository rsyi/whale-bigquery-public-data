# `umiami_lincs.readout`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `signature_id`
  - Unique sequence to identify a signature. Maps to signature_id in perturbagen, signature, and model_system tables
* [STRING]    `lincs_id`
  - Internal reagent identifier
* [STRING]    `reagent`
  - Type of reagent measured eg: Gene, Probe, Protein etc
* [STRING]    `measured_reagent`
  - The name of the reagent part of the readout eg: EGF, ABL1 etc
* [STRING]    `external_id`
  - ID to an external source that can be used to join with external sources
* [STRING]    `external_id_source`
  - Source name ex: Entrez, UniProt etc
* [STRING]    `value`
  - Datapoint value, readout used for numeric data
* [STRING]    `units`
  - It is the definite magnitude of a physical quantity or of time. It has a quantity and a unit associated with it. See http://www.bioassayontology.org/bao#BAO_0000077
* [STRING]    `endpoint`
  - The endpoint is a quantitative or qualitative interpretable standardized representation of a perturbation (a change from a defined reference state of a "closed" model system) that is measured by the signature. An endpoint consists of a series of data points, one for each perturbing agent (screened entity) used in the signature. See http://www.bioassayontology.org/bao#BAO_0000179

-------------------------------------------------------------------------------
*Do not make edits above this line.*
