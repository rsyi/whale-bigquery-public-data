# `human_genome_variants.platinum_genomes_deepvariant_variants_`
`bq-1` | `bigquery-public-data`
This dataset comprises the 6 member CEPH pedigree 1463. See http://www.illumina.com/platinumgenomes/ and https://cloud.google.com/genomics/docs/public-datasets/illumina-platinum-genomes for details.

The BAM files from these samples were retrieved from the European Nucleotide Archive (ENA) accession PRJEB3381 and variants were called using DeepVariant [1] v0.7.0. The VCF files were loaded using GCP Variant Transforms v0.4.2 [2]. The raw VCF files are available in https://console.cloud.google.com/storage/browser/genomics-public-data/platinum-genomes/vcf_deepvariant/0.7.0/ 

[1] https://github.com/google/deepvariant
[2] https://github.com/googlegenomics/gcp-variant-transforms

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
* [INTEGER]   `call.GQ`
  - Conditional genotype quality
* [INTEGER]   `call.DP`
  - Read depth
* [INTEGER]   `call.MIN_DP`
  - Minimum DP observed within the GVCF block.
* [INTEGER]   `call.AD`
  - Read depth for each allele
* [FLOAT]     `call.VAF`
  - Variant allele fractions.
* [FLOAT]     `call.GL`
  - Genotype likelihoods
* [INTEGER]   `call.PL`
  - Phred-scaled genotype likelihoods rounded to the closest integer
* [FLOAT]     `call.quality`
  - Phred-scaled quality score (-10log10 prob(call is wrong)). Higher values imply better quality.
Note: this field has been copied from QUAL field from individual VCF files.
* [STRING]    `call.filter`
  - List of failed filters (if any) or "PASS" indicating the variant has passed all filters.
Note: this field has been copied from FILTER field from individual VCF files.
* [DATE]      `partition_date_please_ignore`
  - Column required by BigQuery partitioning/clustering logic. See https://cloud.google.com/bigquery/docs/clustered-tables

-------------------------------------------------------------------------------
*Do not make edits above this line.*
