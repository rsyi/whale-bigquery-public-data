# `human_genome_variants.simons_genome_diversity_project_sample_variants`
`bq-1` | `bigquery-public-data`
VCF files from [1] loaded using Variant Transforms v0.4.2 [2].
See http://www.nature.com/nature/journal/v538/n7624/full/nature18964.html and https://cloud.google.com/genomics/docs/public-datasets/simons for more details about the dataset.

[1] https://sharehost.hms.harvard.edu/genetics/reich_lab/sgdp/vcf_variants/
[2] https://github.com/googlegenomics/gcp-variant-transforms/

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
* [INTEGER]   `alternate_bases.AC`
  - Allele count in genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF`
  - Allele Frequency, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.MLEAC`
  - Maximum likelihood expectation (MLE) for the allele counts (not necessarily the same as the AC), for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.MLEAF`
  - Maximum likelihood expectation (MLE) for the allele frequency (not necessarily the same as the AF), for each ALT allele, in the same order as listed
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
* [INTEGER]   `call.AD`
  - Allelic depths for the ref and alt alleles in the order listed
* [INTEGER]   `call.DP`
  - Approximate read depth (reads with MQ=255 or with bad mates are filtered)
* [INTEGER]   `call.GQ`
  - Genotype Quality
* [INTEGER]   `call.PL`
  - Normalized, Phred-scaled likelihoods for genotypes as defined in the VCF specification
* [STRING]    `call.FL`
  - filter level in range 0-9 or no value (non-integer: N,?) with zero being least reliable; to threshold at FL=n, use all levels n-9
* [FLOAT]     `call.quality`
  - Phred-scaled quality score (-10log10 prob(call is wrong)). Higher values imply better quality.
Note: this field has been copied from QUAL field from individual VCF files.
* [INTEGER]   `AN`
  - Total number of alleles in called genotypes
* [INTEGER]   `BaseCounts`
  - Counts of each base
* [FLOAT]     `BaseQRankSum`
  - Z-score from Wilcoxon rank sum test of Alt Vs. Ref base qualities
* [BOOLEAN]   `DB`
  - dbSNP Membership
* [INTEGER]   `DP`
  - Approximate read depth; some reads may have been filtered
* [BOOLEAN]   `DS`
  - Were any of the samples downsampled?
* [FLOAT]     `Dels`
  - Fraction of Reads Containing Spanning Deletions
* [FLOAT]     `FS`
  - Phred-scaled p-value using Fisher's exact test to detect strand bias
* [FLOAT]     `GC`
  - GC content around the variant (see docs for window size details)
* [FLOAT]     `HaplotypeScore`
  - Consistency of the site with at most two segregating haplotypes
* [FLOAT]     `InbreedingCoeff`
  - Inbreeding coefficient as estimated from the genotype likelihoods per-sample when compared against the Hardy-Weinberg expectation
* [FLOAT]     `MQ`
  - RMS Mapping Quality
* [INTEGER]   `MQ0`
  - Total Mapping Quality Zero Reads
* [FLOAT]     `MQRankSum`
  - Z-score From Wilcoxon rank sum test of Alt vs. Ref read mapping qualities
* [FLOAT]     `QD`
  - Variant Confidence/Quality by Depth
* [INTEGER]   `RPA`
  - Number of times tandem repeat unit is repeated, for each allele (including reference)
* [STRING]    `RU`
  - Tandem repeat unit (bases)
* [FLOAT]     `ReadPosRankSum`
  - Z-score from Wilcoxon rank sum test of Alt vs. Ref read position bias
* [BOOLEAN]   `STR`
  - Variant is a short tandem repeat
* [DATE]      `partition_date_please_ignore`
  - Column required by BigQuery partitioning/clustering logic. See https://cloud.google.com/bigquery/docs/clustered-tables

-------------------------------------------------------------------------------
*Do not make edits above this line.*
