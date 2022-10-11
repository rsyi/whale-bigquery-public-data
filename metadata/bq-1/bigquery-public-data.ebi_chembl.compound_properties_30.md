# `ebi_chembl.compound_properties_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `molregno`
  - Foreign key to compounds table (compound structure)
* [FLOAT]     `mw_freebase`
  - Molecular weight of parent compound
* [FLOAT]     `alogp`
  - Calculated ALogP
* [INTEGER]   `hba`
  - Number hydrogen bond acceptors
* [INTEGER]   `hbd`
  - Number hydrogen bond donors
* [FLOAT]     `psa`
  - Polar surface area
* [INTEGER]   `rtb`
  - Number rotatable bonds
* [STRING]    `ro3_pass`
  -  Indicates whether the compound passes the rule-of-three (mw < 300, logP < 3 etc)
* [INTEGER]   `num_ro5_violations`
  - Number of violations of Lipinski's rule-of-five, using HBA and HBD definitions
* [FLOAT]     `cx_most_apka`
  - The most acidic pKa calculated using ChemAxon v17.29.0
* [FLOAT]     `cx_most_bpka`
  - The most basic pKa calculated using ChemAxon v17.29.0
* [FLOAT]     `cx_logp`
  - The calculated octanol/water partition coefficient using ChemAxon v17.29.0
* [FLOAT]     `cx_logd`
  - The calculated octanol/water distribution coefficient at pH7.4 using ChemAxon v17.29.0
* [STRING]    `molecular_species`
  - Indicates whether the compound is an acid/base/neutral
* [FLOAT]     `full_mwt`
  - Molecular weight of the full compound including any salts
* [INTEGER]   `aromatic_rings`
  - Number of aromatic rings
* [INTEGER]   `heavy_atoms`
  - Number of heavy (non-hydrogen) atoms
* [FLOAT]     `qed_weighted`
  - Weighted quantitative estimate of drug likeness (as defined by Bickerton et al., Nature Chem 2012)
* [FLOAT]     `mw_monoisotopic`
  - Monoisotopic parent molecular weight
* [STRING]    `full_molformula`
  -  Molecular formula for the full compound (including any salt)
* [INTEGER]   `hba_lipinski`
  - Number of hydrogen bond acceptors calculated according to Lipinski's original rules (i.e., N + O count))
* [INTEGER]   `hbd_lipinski`
  - Number of hydrogen bond donors calculated according to Lipinski's original rules (i.e., NH + OH count)
* [INTEGER]   `num_lipinski_ro5_violations`
  - Number of violations of Lipinski's rule of five using HBA_LIPINSKI and HBD_LIPINSKI counts

-------------------------------------------------------------------------------
*Do not make edits above this line.*
