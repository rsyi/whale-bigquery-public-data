# `ebi_chembl.drug_mechanism_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `mec_id`
  - Primary key for each drug mechanism of action
* [INTEGER]   `record_id`
  - Record_id for the drug (foreign key to compound_records table)
* [INTEGER]   `molregno`
  - Molregno for the drug (foreign key to molecule_dictionary table)
* [STRING]    `mechanism_of_action`
  -  Description of the mechanism of action e.g., 'Phosphodiesterase 5 inhibitor'
* [INTEGER]   `tid`
  - Target associated with this mechanism of action (foreign key to target_dictionary table)
* [INTEGER]   `site_id`
  - Binding site for the drug within the target (where known) - foreign key to binding_sites table
* [STRING]    `action_type`
  - Type of action of the drug on the target e.g., agonist/antagonist etc (foreign key to action_type table)
* [INTEGER]   `direct_interaction`
  - Flag to show whether the molecule is believed to interact directly with the target (1 = yes, 0 = no)
* [INTEGER]   `molecular_mechanism`
  - Flag to show whether the mechanism of action describes the molecular target of the drug, rather than a higher-level physiological mechanism e.g., vasodilator (1 = yes, 0 = no)
* [INTEGER]   `disease_efficacy`
  - Flag to show whether the target assigned is believed to play a role in the efficacy of the drug in the indication(s) for which it is approved (1 = yes, 0 = no)
* [STRING]    `mechanism_comment`
  - Additional comments regarding the mechanism of action
* [STRING]    `selectivity_comment`
  - Additional comments regarding the selectivity of the drug
* [STRING]    `binding_site_comment`
  - Additional comments regarding the binding site of the drug
* [INTEGER]   `variant_id`
  - None

-------------------------------------------------------------------------------
*Do not make edits above this line.*
