# `human_variant_annotation.ensembl_esp6500_aa_hg38_release89`
`bq-1` | `bigquery-public-data`
Source: http://ftp.ensembl.org/pub/release-89/variation/vcf/homo_sapiens/ESP6500-African_American.vcf.gz

## Column details
* [STRING]    `reference_name`
  - An identifier from the reference genome or an angle-bracketed ID string pointing to a contig in the assembly file.
* [INTEGER]   `start`
  - The reference position, with the first base having position 0.
* [INTEGER]   `end`
  - End position of the variant described in this record.
* [STRING]    `reference_bases`
  - Each base must be one of A,C,G,T,N (case insensitive). Multiple bases are permitted. The value in the 'start' field refers to the position of the first base in the string.
* [STRING]    `alternate_bases`
  - List of alternate non-reference alleles.
* [STRING]    `variant_id`
  - Google Genomics variant id.
* [FLOAT]     `quality`
  - Phred-scaled quality score for the assertion made in ALT.
* [STRING]    `filter`
* [STRING]    `names`
  - List of unique identifiers for the variant where available.
* [RECORD]    `call`
  - Per-sample measurements.
* [STRING]    `call.call_set_id`
  - The id of the callset from which this data was exported from the Google Genomics Variants API.
* [STRING]    `call.call_set_name`
  - Sample identifier from source data.
* [INTEGER]   `call.genotype`
  - List of genotypes.
* [STRING]    `call.phaseset`
  - If this value is null, the data is unphased.  Otherwise it is phased.
* [FLOAT]     `call.genotype_likelihood`
  - List of genotype likelihoods.
* [STRING]    `AA`
  - Ancestral Allele
* [FLOAT]     `AF`
  - Allele Frequency
* [BOOLEAN]   `CLIN_association`
  - association.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_benign`
  - benign.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_confers_sensitivity`
  - confers sensitivity.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_drug_response`
  - drug response.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_likely_benign`
  - likely benign.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_likely_pathogenic`
  - likely pathogenic.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_not_provided`
  - not provided.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_other`
  - other.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_pathogenic`
  - pathogenic.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_protective`
  - protective.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_risk_factor`
  - risk factor.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_uncertain_significance`
  - uncertain significance.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `ESP_20141103`
  - Data from NHLBI ESP version v.0.0.30. The goal of the NHLBI GO Exome Sequencing Project is to discover novel genes and mechanisms contributing to heart, lung and blood disorders by sequencing the protein coding regions of the human genome.
* [BOOLEAN]   `E_1000G`
  - 1000Genomes.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_Cited`
  - Cited.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_ESP`
  - ESP.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_ExAC`
  - ExAC.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_Freq`
  - Frequency.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_Hapmap`
  - HapMap.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_Phenotype_or_Disease`
  - Phenotype_or_Disease.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [STRING]    `Reference_seq`
* [STRING]    `TSA`
  - Type of sequence alteration. Child of term sequence_alteration as defined by the sequence ontology project.
* [STRING]    `Variant_seq`
* [BOOLEAN]   `dbSNP_149`
  - Variants (including SNPs and indels) imported from dbSNP

-------------------------------------------------------------------------------
*Do not make edits above this line.*
