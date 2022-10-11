# `ebi_chembl.molecule_dictionary_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `molregno`
  - Internal Primary Key for the molecule
* [STRING]    `pref_name`
  -  Preferred name for the molecule
* [STRING]    `chembl_id`
  - ChEMBL identifier for this compound (for use on web interface etc)
* [INTEGER]   `max_phase`
  - Maximum phase of development reached for the compound (4 = approved). Null where max phase has not yet been assigned.
* [INTEGER]   `therapeutic_flag`
  - Indicates that a drug has a therapeutic application (as opposed to e.g., an imaging agent, additive etc).
* [INTEGER]   `dosed_ingredient`
  - Indicates that the drug is dosed in this form (e.g., a particular salt)
* [STRING]    `structure_type`
  - Indications whether the molecule has a small molecule structure or a protein sequence (MOL indicates an entry in the compound_structures table, SEQ indications an entry in the protein_therapeutics table, NONE indicates an entry in neither table, e.g., structure unknown)
* [INTEGER]   `chebi_par_id`
  - Preferred ChEBI ID for the compound (where different from assigned)
* [STRING]    `molecule_type`
  - Type of molecule (Small molecule, Protein, Antibody, Oligosaccharide, Oligonucleotide, Cell, Unknown)
* [INTEGER]   `first_approval`
  - Earliest known approval year for the molecule
* [INTEGER]   `oral`
  - Indicates whether the drug is known to be administered orally.
* [INTEGER]   `parenteral`
  - Indicates whether the drug is known to be administered parenterally
* [INTEGER]   `topical`
  - Indicates whether the drug is known to be administered topically.
* [INTEGER]   `black_box_warning`
  - Indicates that the drug has a black box warning
* [INTEGER]   `natural_product`
  - Indicates whether the compound is natural product-derived (currently curated only for drugs)
* [INTEGER]   `first_in_class`
  - Indicates whether this is known to be the first compound of its class (e.g., acting on a particular target).
* [INTEGER]   `chirality`
  - Shows whether a drug is dosed as a racemic mixture (0), single stereoisomer (1) or is an achiral molecule (2)
* [INTEGER]   `prodrug`
  - Indicates that the molecule is a pro-drug (see molecule hierarchy for active component, where known)
* [INTEGER]   `inorganic_flag`
  - Indicates whether the molecule is inorganic (i.e., containing only metal atoms and <2 carbon atoms)
* [INTEGER]   `usan_year`
  - The year in which the application for a USAN/INN name was made
* [INTEGER]   `availability_type`
  - The availability type for the drug (0 = discontinued, 1 = prescription only, 2 = over the counter)
* [STRING]    `usan_stem`
  - Where the compound has been assigned a USAN name, this indicates the stem, as described in the USAN_STEM table.
* [INTEGER]   `polymer_flag`
  - Indicates whether a molecule is a small molecule polymer (e.g., polistyrex)
* [STRING]    `usan_substem`
  - Where the compound has been assigned a USAN name, this indicates the substem
* [STRING]    `usan_stem_definition`
  - Definition of the USAN stem
* [STRING]    `indication_class`
  - Indication class(es) assigned to a drug in the USP dictionary
* [INTEGER]   `withdrawn_flag`
  - Flag indicating whether the drug has been withdrawn in at least one country (not necessarily in the US)
* [INTEGER]   `withdrawn_year`
  - Year the drug was first withdrawn in any country
* [STRING]    `withdrawn_country`
  - List of countries/regions where the drug has been withdrawn
* [STRING]    `withdrawn_reason`
  - Reasons for withdrawl (e.g., safety)
* [STRING]    `withdrawn_class`
  -  High level categories for the withdrawn reason (e.g., Cardiotoxicity, Hepatotoxicity)

-------------------------------------------------------------------------------
*Do not make edits above this line.*
