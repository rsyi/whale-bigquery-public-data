# `ebi_chembl.ligand_eff_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `activity_id`
  - Link key to activities table
* [FLOAT]     `bei`
  - Binding Efficiency Index = p(XC50) *1000/MW_freebase
* [FLOAT]     `sei`
  - Surface Efficiency Index = p(XC50)*100/PSA
* [FLOAT]     `le`
  - [from the Hopkins DDT paper 2004]
* [FLOAT]     `lle`
  - Lipophilic Ligand Efficiency = -logKi-ALogP. [from Leeson NRDD 2007]

-------------------------------------------------------------------------------
*Do not make edits above this line.*
