# `immune_epitope_db.tcr_3d_assays`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `t_cell_assay_iri`
  - Reference/T Cell Assay IRI
* [STRING]    `reference_iri`
  - Reference/Reference IRI
* [STRING]    `method_technique`
  - Assay/Method/Technique
* [STRING]    `process_type`
  - 1st in vivo Process/Process Type
* [STRING]    `immunogen`
  - 1st in vivo Process/Immunogen
* [STRING]    `name`
  - Host/Name
* [STRING]    `epitope_iri`
  - Epitope/Epitope IRI
* [STRING]    `epitope_description`
  - Epitope/Epitope Description
* [STRING]    `antigen_name`
  - Epitope/Antigen Name
* [STRING]    `antigen_iri`
  - Epitope/Antigen IRI
* [STRING]    `antigen_sequence`
  - Epitope/Antigen Sequence
* [INTEGER]   `starting_position`
  - Epitope/Starting Position
* [INTEGER]   `ending_position`
  - Epitope/Ending Position
* [STRING]    `epitope_sequence`
  - Epitope/Epitope Sequence
* [STRING]    `organism`
  - Epitope/Organism
* [STRING]    `organism_iri`
  - Epitope/Organism IRI
* [STRING]    `parent_antigen_id`
  - Epitope/Parent Antigen ID
* [STRING]    `parent_antigen_name`
  - Epitope/Parent Antigen Name
* [STRING]    `parent_organism_id`
  - Epitope/Parent Organism ID
* [STRING]    `parent_organism_name`
  - Epitope/Parent Organism name
* [INTEGER]   `receptor_id`
  - TCR/Receptor ID
* [STRING]    `tcr_type`
  - TCR/TCR Type
* [STRING]    `tcr_name`
  - TCR/TCR Name
* [STRING]    `chain_1_organism_name`
  - TCR/Chain 1 Organism Name
* [STRING]    `chain_1_organism_iri`
  - TCR/Chain 1 Organism IRI
* [STRING]    `chain_2_organism_name`
  - TCR/Chain 2 Organism Name
* [STRING]    `chain_2_organism_iri`
  - TCR/Chain 2 Organism IRI
* [STRING]    `chain_1_type`
  - TCR/Chain 1 type
* [STRING]    `chain_2_type`
  - TCR/Chain 2 type
* [STRING]    `chain_1_sequence`
  - TCR/Chain 1 Sequence
* [STRING]    `chain_2_sequence`
  - TCR/Chain 2 Sequence
* [STRING]    `mhc_allele`
  - MHC/MHC Allele
* [STRING]    `mhc_class`
  - MHC/MHC Class
* [STRING]    `mhc_iri`
  - MHC/MHC IRI
* [STRING]    `mhc_chain1`
  - MHC/MHC Chain1
* [STRING]    `mhc_chain2`
  - MHC/MHC Chain2
* [STRING]    `mhc_chain1_iri`
  - MHC/MHC Chain1 IRI
* [STRING]    `mhc_chain1_sequence`
  - MHC/MHC Chain1 Sequence
* [STRING]    `mhc_chain2_iri`
  - MHC/MHC Chain2 IRI
* [STRING]    `mhc_chain2_sequence`
  - MHC/MHC Chain2 Sequence
* [INTEGER]   `complex_id`
  - 3D Complex/Complex ID
* [STRING]    `pdb_id`
  - 3D Complex/PDB ID
* [FLOAT]     `resolution_angstrom`
  - 3D Complex/Resolution (Angstrom)
* [STRING]    `tcr_pdb_chain_1`
  - 3D Complex/TCR PDB Chain 1
* [STRING]    `tcr_pdb_chain_2`
  - 3D Complex/TCR PDB Chain 2
* [STRING]    `mhc_pdb_chain_1`
  - 3D Complex/MHC PDB Chain1
* [STRING]    `mhc_pdb_chain_2`
  - 3D Complex/MHC PDB Chain1
* [STRING]    `antigen_pdb_chains`
  - 3D Complex/Antigen PDB Chain(s)
* [STRING]    `curated_epitope_residues_interacting_with_tcr`
  - 3D Complex/Curated Epitope Residues Interacting with TCR
* [STRING]    `curated_epitope_residues_interacting_with_mhc`
  - 3D Complex/Curated Epitope Residues Interacting with MHC
* [STRING]    `curated_tcr_residues_interacting_with_epitope`
  - 3D Complex/Curated TCR Residues Interacting with Epitope
* [STRING]    `curated_tcr_residues_interacting_with_mhc`
  - 3D Complex/Curated TCR Residues Interacting with MHC
* [STRING]    `curated_mhc_residues_interacting_with_tcr`
  - 3D Complex/Curated MHC Residues Interacting with TCR
* [STRING]    `curated_mhc_residues_interacting_with_epitope`
  - 3D Complex/Curated MHC Residues Interacting with Epitope
* [STRING]    `calculated_epitope_residues`
  - 3D Complex/Calculated Epitope Residues
* [STRING]    `calculated_epitope_residues_interacting_with_tcr`
  - 3D Complex/Calculated Epitope Residues Interacting with TCR
* [STRING]    `calculated_epitope_residues_interacting_with_mhc`
  - 3D Complex/Calculated Epitope Residues Interacting with MHC
* [STRING]    `calculated_tcr_residues_interacting_with_epitope`
  - 3D Complex/Calculated TCR Residues Interacting with Epitope
* [STRING]    `calculated_tcr_residues_interacting_with_mhc`
  - 3D Complex/Calculated TCR Residues Interacting with MHC
* [STRING]    `calculated_mhc_residues_interacting_with_epitope`
  - 3D Complex/Calculated MHC Residues Interacting with Epitope
* [STRING]    `calculated_mhc_residues_interacting_with_tcr`
  - 3D Complex/Calculated MHC Residues Interacting with TCR
* [STRING]    `calculated_atom_pairs`
  - 3D Complex/Calculated Atom Pairs
* [FLOAT]     `curated_antigen_buried_surface_area`
  - 3D Complex/Curated Antigen Buried Surface Area
* [FLOAT]     `curated_tcr_buried_surface_area`
  - 3D Complex/Curated TCR Buried Surface Area
* [FLOAT]     `calculated_antigen_buried_surface_area`
  - 3D Complex/Calculated Antigen Buried Surface Area
* [FLOAT]     `calculated_tcr_buried_surface_area`
  - 3D Complex/Calculated TCR Buried Surface Area
* [STRING]    `comments`
  - 3D Complex/Comments

-------------------------------------------------------------------------------
*Do not make edits above this line.*
