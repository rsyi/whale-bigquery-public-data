# `human_variant_annotation.ensembl_1000genomes_phase3_hg38_release89`
`bq-1` | `bigquery-public-data`
Source: http://ftp.ensembl.org/pub/release-89/variation/vcf/homo_sapiens/1000GENOMES-phase_3.vcf.gz

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
* [FLOAT]     `AFR_AF`
  - Allele frequency in the AFR populations
* [FLOAT]     `AMR_AF`
  - Allele frequency in the AMR populations
* [BOOLEAN]   `CLIN_association`
* [BOOLEAN]   `CLIN_benign`
* [BOOLEAN]   `CLIN_confers_sensitivity`
* [BOOLEAN]   `CLIN_drug_response`
* [BOOLEAN]   `CLIN_likely_benign`
* [BOOLEAN]   `CLIN_likely_pathogenic`
* [BOOLEAN]   `CLIN_not_provided`
* [BOOLEAN]   `CLIN_other`
* [BOOLEAN]   `CLIN_pathogenic`
* [BOOLEAN]   `CLIN_protective`
* [BOOLEAN]   `CLIN_risk_factor`
* [BOOLEAN]   `CLIN_uncertain_significance`
* [FLOAT]     `EAS_AF`
  - Allele frequency in the EAS populations
* [FLOAT]     `EUR_AF`
  - Allele frequency in the EUR populations
* [BOOLEAN]   `E_1000G`
* [BOOLEAN]   `E_Cited`
* [BOOLEAN]   `E_ESP`
* [BOOLEAN]   `E_ExAC`
* [BOOLEAN]   `E_Freq`
* [BOOLEAN]   `E_Hapmap`
* [BOOLEAN]   `E_Phenotype_or_Disease`
* [STRING]    `MA`
* [INTEGER]   `MAC`
* [FLOAT]     `MAF`
* [STRING]    `Reference_seq`
* [FLOAT]     `SAS_AF`
  - Allele frequency in the SAS populations
* [STRING]    `TSA`
  - Type of sequence alteration. Child of term sequence_alteration as defined by the sequence ontology project.
* [STRING]    `Variant_seq`
* [STRING]    `allele_string`
* [BOOLEAN]   `dbSNP_149`
  - Variants (including SNPs and indels) imported from dbSNP
* [INTEGER]   `variation_id`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
