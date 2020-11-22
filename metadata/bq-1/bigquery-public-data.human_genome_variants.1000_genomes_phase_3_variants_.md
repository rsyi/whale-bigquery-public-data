# `human_genome_variants.1000_genomes_phase_3_variants_`
`bq-1` | `bigquery-public-data`
1000 genomes (phase 3) VCF files from [1] loaded using Variant Transforms v0.4.2 [2].
See ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20130502/README_phase3_callset_20150220 and https://cloud.google.com/genomics/docs/public-datasets/1000-genomes for more details about the dataset.

[1] ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20130502/
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
* [INTEGER]   `alternate_bases.AC`
  - Total number of alternate alleles in called genotypes
* [FLOAT]     `alternate_bases.AF`
  - Estimated allele frequency in the range (0,1)
* [FLOAT]     `alternate_bases.EAS_AF`
  - Allele frequency in the EAS populations calculated from AC and AN, in the range (0,1)
* [FLOAT]     `alternate_bases.EUR_AF`
  - Allele frequency in the EUR populations calculated from AC and AN, in the range (0,1)
* [FLOAT]     `alternate_bases.AFR_AF`
  - Allele frequency in the AFR populations calculated from AC and AN, in the range (0,1)
* [FLOAT]     `alternate_bases.AMR_AF`
  - Allele frequency in the AMR populations calculated from AC and AN, in the range (0,1)
* [FLOAT]     `alternate_bases.SAS_AF`
  - Allele frequency in the SAS populations calculated from AC and AN, in the range (0,1)
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
* [INTEGER]   `call.CN`
  - Copy number genotype for imprecise events
* [FLOAT]     `call.CNL`
  - Copy number likelihoods with no frequency prior
* [FLOAT]     `call.CNP`
  - Copy number likelihoods
* [FLOAT]     `call.CNQ`
  - Copy number genotype quality for imprecise events
* [FLOAT]     `call.GP`
  - Genotype likelihoods
* [INTEGER]   `call.GQ`
  - Genotype Quality
* [STRING]    `call.FT`
  - Per-sample genotype filter
* [INTEGER]   `call.PL`
  - Normalized, Phred-scaled likelihoods for genotypes as defined in the VCF specification
* [INTEGER]   `CIEND`
  - Confidence interval around END for imprecise variants
* [INTEGER]   `CIPOS`
  - Confidence interval around POS for imprecise variants
* [STRING]    `CS`
  - Source call set.
* [BOOLEAN]   `IMPRECISE`
  - Imprecise structural variation
* [STRING]    `MC`
  - Merged calls.
* [STRING]    `MEINFO`
  - Mobile element info of the form NAME,START,END<POLARITY; If there is only 5' OR 3' support for this call, will be NULL NULL for START and END
* [INTEGER]   `MEND`
  - Mitochondrial end coordinate of inserted sequence
* [INTEGER]   `MLEN`
  - Estimated length of mitochondrial insert
* [INTEGER]   `MSTART`
  - Mitochondrial start coordinate of inserted sequence
* [INTEGER]   `SVLEN`
  - SV length. It is only calculated for structural variation MEIs. For other types of SVs; one may calculate the SV length by INFO:END-START+1, or by finding the difference between lengthes of REF and ALT alleles
* [STRING]    `SVTYPE`
  - Type of structural variant
* [STRING]    `TSD`
  - Precise Target Site Duplication for bases, if unknown, value will be NULL
* [INTEGER]   `NS`
  - Number of samples with data
* [INTEGER]   `AN`
  - Total number of alleles in called genotypes
* [INTEGER]   `DP`
  - Total read depth; only low coverage data were counted towards the DP, exome data were not used
* [STRING]    `AA`
  - Ancestral Allele. Format: AA|REF|ALT|IndelType. AA: Ancestral allele, REF:Reference Allele, ALT:Alternate Allele, IndelType:Type of Indel (REF, ALT and IndelType are only defined for indels)
* [STRING]    `VT`
  - indicates what type of variant the line represents
* [BOOLEAN]   `EX_TARGET`
  - indicates whether a variant is within the exon pull down target boundaries
* [BOOLEAN]   `MULTI_ALLELIC`
  - indicates whether a site is multi-allelic
* [STRING]    `OLD_VARIANT`
* [DATE]      `partition_date_please_ignore`
  - Column required by BigQuery partitioning/clustering logic. See https://cloud.google.com/bigquery/docs/clustered-tables

-------------------------------------------------------------------------------
*Do not make edits above this line.*
