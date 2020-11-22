# `umiami_lincs.perturbagen`
`bq-1` | `bigquery-public-data`
Parameters and properties of the perturbagen important to interpret the activity readout values.

## Column details
* [STRING]    `signature_id`
  - Unique sequence to identify a signature
* [STRING]    `perturbagen_id`
  - Unique sequence to identify a perturbagen
* [STRING]    `perturbagen_class`
  - Type of the perturbagen, eg: small molecule, nucleic acid reagent
* [FLOAT]     `timepoint`
  - An endpoint defined by a length in time at which a desired effect or observation occurs. See http://www.bioassayontology.org/bao/bao_complete.owl#BAO_0002114
* [STRING]    `timepoint_units`
  - A unit which is a standard measure of the dimension in which events occur in sequence. See http://purl.obolibrary.org/obo/UO_0000003
* [FLOAT]     `concentration`
  - It can refer to the screening concentration (for example in a primary assay) or it can be a concentration at which the perturbagen mediates a defined response, such as IC50 or EC50. It always has one value and a concentration unit. See http://www.bioassayontology.org/bao#BAO_0000180
* [STRING]    `concentration_units`
  - It describes the most common unit used in calculating volumetric stoichiometry: molarity. Units include: molar, millimolar, micromolar, nanomolar. See http://www.bioassayontology.org/bao#BAO_0190000

-------------------------------------------------------------------------------
*Do not make edits above this line.*
