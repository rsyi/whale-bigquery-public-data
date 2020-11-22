# `human_variant_annotation.ensembl_1000genomes_phase3_hg38_release93`
`bq-1` | `bigquery-public-data`
Source: http://ftp.ensembl.org/pub/release-93/variation/vcf/homo_sapiens/1000GENOMES-phase_3.vcf.gz

## Column details
* [STRING]    `reference_name`
  - Reference name.
* [INTEGER]   `start_position`
  - Start position (0-based). Corresponds to the first base of the string of reference bases.
* [INTEGER]   `end_position`
  - End position (0-based). Corresponds to the first base after the last base in the reference allele.
* [STRING]    `reference_bases`
  - Reference bases.
* [RECORD]    `alternate_bases`
  - One record for each alternate base (if any).
* [STRING]    `alternate_bases.alt`
  - Alternate base.
* [FLOAT]     `alternate_bases.EAS_AF`
  - Allele frequency in the EAS populations
* [FLOAT]     `alternate_bases.EUR_AF`
  - Allele frequency in the EUR populations
* [FLOAT]     `alternate_bases.AFR_AF`
  - Allele frequency in the AFR populations
* [FLOAT]     `alternate_bases.AMR_AF`
  - Allele frequency in the AMR populations
* [FLOAT]     `alternate_bases.SAS_AF`
  - Allele frequency in the SAS populations
* [STRING]    `names`
  - Variant names (e.g. RefSNP ID).
* [FLOAT]     `quality`
  - Phred-scaled quality score (-10log10 prob(call is wrong)). Higher values imply better quality.
* [STRING]    `filter`
  - List of failed filters (if any) or "PASS" indicating the variant has passed all filters.
* [RECORD]    `call`
  - One record for each call.
* [STRING]    `call.name`
  - Name of the call.
* [INTEGER]   `call.genotype`
  - Genotype of the call. "-1" is used in cases where the genotype is not called.
* [STRING]    `call.phaseset`
  - Phaseset of the call (if any). "*" is used in cases where the genotype is phased, but no phase set ("PS" in FORMAT) was specified.
* [BOOLEAN]   `COSMIC_85`
  - Somatic mutations found in human cancers from the COSMIC catalogue
* [BOOLEAN]   `HGMD_PUBLIC_20174`
  - Variants from HGMD-PUBLIC dataset December 2017 [Remapped from GRCh37]
* [BOOLEAN]   `dbSNP_150`
  - Variants (including SNPs and indels) imported from dbSNP
* [BOOLEAN]   `ClinVar_201805`
  - Variants of clinical significance imported from ClinVar
* [BOOLEAN]   `PhenCode`
  - PhenCode is a collaborative project to better understand the relationship between genotype and phenotype in humans
* [BOOLEAN]   `dbSNP151_151`
  - Partial update from dbSNP
* [BOOLEAN]   `ESP_20141103`
  - Data from NHLBI ESP version v.0.0.30. The goal of the NHLBI GO Exome Sequencing Project is to discover novel genes and mechanisms contributing to heart, lung and blood disorders by sequencing the protein coding regions of the human genome.
* [STRING]    `TSA`
  - Type of sequence alteration. Child of term sequence_alteration as defined by the sequence ontology project.
* [BOOLEAN]   `E_Cited`
  - Cited.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_Multiple_observations`
  - Multiple_observations.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_Freq`
  - Frequency.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_TOPMed`
  - TOPMed.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_Hapmap`
  - HapMap.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_Phenotype_or_Disease`
  - Phenotype_or_Disease.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_ESP`
  - ESP.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_gnomAD`
  - gnomAD.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_1000G`
  - 1000Genomes.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `E_ExAC`
  - ExAC.http://www.ensembl.org/info/docs/variation/data_description.html#evidence_status
* [BOOLEAN]   `CLIN_risk_factor`
  - risk factor.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_protective`
  - protective.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_confers_sensitivity`
  - confers sensitivity.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_other`
  - other.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_drug_response`
  - drug response.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_uncertain_significance`
  - uncertain significance.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_benign`
  - benign.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_likely_pathogenic`
  - likely pathogenic.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_pathogenic`
  - pathogenic.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_likely_benign`
  - likely benign.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_histocompatibility`
  - histocompatibility.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_not_provided`
  - not provided.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [BOOLEAN]   `CLIN_association`
  - association.http://www.ensembl.org/info/genome/variation/data_description.html#clin_significance
* [STRING]    `MA`
  - Minor Allele
* [FLOAT]     `MAF`
  - Minor Allele Frequency
* [INTEGER]   `MAC`
  - Minor Alelele Count
* [STRING]    `AA`
  - Ancestral Allele

-------------------------------------------------------------------------------
*Do not make edits above this line.*
