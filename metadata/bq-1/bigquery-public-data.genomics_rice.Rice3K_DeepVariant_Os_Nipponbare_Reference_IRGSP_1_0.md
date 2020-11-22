# `genomics_rice.Rice3K_DeepVariant_Os_Nipponbare_Reference_IRGSP_1_0`
`bq-1` | `bigquery-public-data`

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

-------------------------------------------------------------------------------
*Do not make edits above this line.*
