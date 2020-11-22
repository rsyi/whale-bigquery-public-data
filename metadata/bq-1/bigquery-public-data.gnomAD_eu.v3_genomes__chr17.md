# `gnomAD_eu.v3_genomes__chr17`
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
* [INTEGER]   `alternate_bases.AC`
  - Alternate allele count for samples
* [FLOAT]     `alternate_bases.AF`
  - Alternate allele frequency in samples
* [INTEGER]   `alternate_bases.n_alt_alleles`
  - Total number of alternate alleles observed at variant locus
* [INTEGER]   `alternate_bases.AC_asj_female`
  - Alternate allele count for female samples of Ashkenazi Jewish ancestry
* [FLOAT]     `alternate_bases.AF_asj_female`
  - Alternate allele frequency in female samples of Ashkenazi Jewish ancestry
* [INTEGER]   `alternate_bases.nhomalt_asj_female`
  - Count of homozygous individuals in female samples of Ashkenazi Jewish ancestry
* [INTEGER]   `alternate_bases.AC_eas_female`
  - Alternate allele count for female samples of East Asian ancestry
* [FLOAT]     `alternate_bases.AF_eas_female`
  - Alternate allele frequency in female samples of East Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_eas_female`
  - Count of homozygous individuals in female samples of East Asian ancestry
* [INTEGER]   `alternate_bases.AC_afr_male`
  - Alternate allele count for male samples of African-American/African ancestry
* [FLOAT]     `alternate_bases.AF_afr_male`
  - Alternate allele frequency in male samples of African-American/African ancestry
* [INTEGER]   `alternate_bases.nhomalt_afr_male`
  - Count of homozygous individuals in male samples of African-American/African ancestry
* [INTEGER]   `alternate_bases.AC_female`
  - Alternate allele count for female samples
* [FLOAT]     `alternate_bases.AF_female`
  - Alternate allele frequency in female samples
* [INTEGER]   `alternate_bases.nhomalt_female`
  - Count of homozygous individuals in female samples
* [INTEGER]   `alternate_bases.AC_fin_male`
  - Alternate allele count for male samples of Finnish ancestry
* [FLOAT]     `alternate_bases.AF_fin_male`
  - Alternate allele frequency in male samples of Finnish ancestry
* [INTEGER]   `alternate_bases.nhomalt_fin_male`
  - Count of homozygous individuals in male samples of Finnish ancestry
* [INTEGER]   `alternate_bases.AC_oth_female`
  - Alternate allele count for female samples of Other ancestry
* [FLOAT]     `alternate_bases.AF_oth_female`
  - Alternate allele frequency in female samples of Other ancestry
* [INTEGER]   `alternate_bases.nhomalt_oth_female`
  - Count of homozygous individuals in female samples of Other ancestry
* [INTEGER]   `alternate_bases.AC_ami`
  - Alternate allele count for samples of Amish ancestry
* [FLOAT]     `alternate_bases.AF_ami`
  - Alternate allele frequency in samples of Amish ancestry
* [INTEGER]   `alternate_bases.nhomalt_ami`
  - Count of homozygous individuals in samples of Amish ancestry
* [INTEGER]   `alternate_bases.AC_oth`
  - Alternate allele count for samples of Other ancestry
* [FLOAT]     `alternate_bases.AF_oth`
  - Alternate allele frequency in samples of Other ancestry
* [INTEGER]   `alternate_bases.nhomalt_oth`
  - Count of homozygous individuals in samples of Other ancestry
* [INTEGER]   `alternate_bases.AC_male`
  - Alternate allele count for male samples
* [FLOAT]     `alternate_bases.AF_male`
  - Alternate allele frequency in male samples
* [INTEGER]   `alternate_bases.nhomalt_male`
  - Count of homozygous individuals in male samples
* [INTEGER]   `alternate_bases.AC_ami_female`
  - Alternate allele count for female samples of Amish ancestry
* [FLOAT]     `alternate_bases.AF_ami_female`
  - Alternate allele frequency in female samples of Amish ancestry
* [INTEGER]   `alternate_bases.nhomalt_ami_female`
  - Count of homozygous individuals in female samples of Amish ancestry
* [INTEGER]   `alternate_bases.AC_afr`
  - Alternate allele count for samples of African-American/African ancestry
* [FLOAT]     `alternate_bases.AF_afr`
  - Alternate allele frequency in samples of African-American/African ancestry
* [INTEGER]   `alternate_bases.nhomalt_afr`
  - Count of homozygous individuals in samples of African-American/African ancestry
* [INTEGER]   `alternate_bases.AC_eas_male`
  - Alternate allele count for male samples of East Asian ancestry
* [FLOAT]     `alternate_bases.AF_eas_male`
  - Alternate allele frequency in male samples of East Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_eas_male`
  - Count of homozygous individuals in male samples of East Asian ancestry
* [INTEGER]   `alternate_bases.AC_sas`
  - Alternate allele count for samples of South Asian ancestry
* [FLOAT]     `alternate_bases.AF_sas`
  - Alternate allele frequency in samples of South Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_sas`
  - Count of homozygous individuals in samples of South Asian ancestry
* [INTEGER]   `alternate_bases.AC_nfe_female`
  - Alternate allele count for female samples of Non-Finnish European ancestry
* [FLOAT]     `alternate_bases.AF_nfe_female`
  - Alternate allele frequency in female samples of Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.nhomalt_nfe_female`
  - Count of homozygous individuals in female samples of Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.AC_asj_male`
  - Alternate allele count for male samples of Ashkenazi Jewish ancestry
* [FLOAT]     `alternate_bases.AF_asj_male`
  - Alternate allele frequency in male samples of Ashkenazi Jewish ancestry
* [INTEGER]   `alternate_bases.nhomalt_asj_male`
  - Count of homozygous individuals in male samples of Ashkenazi Jewish ancestry
* [INTEGER]   `alternate_bases.AC_raw`
  - Alternate allele count for samples, before removing low-confidence genotypes
* [FLOAT]     `alternate_bases.AF_raw`
  - Alternate allele frequency in samples, before removing low-confidence genotypes
* [INTEGER]   `alternate_bases.nhomalt_raw`
  - Count of homozygous individuals in samples, before removing low-confidence genotypes
* [INTEGER]   `alternate_bases.AC_oth_male`
  - Alternate allele count for male samples of Other ancestry
* [FLOAT]     `alternate_bases.AF_oth_male`
  - Alternate allele frequency in male samples of Other ancestry
* [INTEGER]   `alternate_bases.nhomalt_oth_male`
  - Count of homozygous individuals in male samples of Other ancestry
* [INTEGER]   `alternate_bases.AC_nfe_male`
  - Alternate allele count for male samples of Non-Finnish European ancestry
* [FLOAT]     `alternate_bases.AF_nfe_male`
  - Alternate allele frequency in male samples of Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.nhomalt_nfe_male`
  - Count of homozygous individuals in male samples of Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.AC_asj`
  - Alternate allele count for samples of Ashkenazi Jewish ancestry
* [FLOAT]     `alternate_bases.AF_asj`
  - Alternate allele frequency in samples of Ashkenazi Jewish ancestry
* [INTEGER]   `alternate_bases.nhomalt_asj`
  - Count of homozygous individuals in samples of Ashkenazi Jewish ancestry
* [INTEGER]   `alternate_bases.AC_amr_male`
  - Alternate allele count for male samples of Latino ancestry
* [FLOAT]     `alternate_bases.AF_amr_male`
  - Alternate allele frequency in male samples of Latino ancestry
* [INTEGER]   `alternate_bases.nhomalt_amr_male`
  - Count of homozygous individuals in male samples of Latino ancestry
* [INTEGER]   `alternate_bases.nhomalt`
  - Count of homozygous individuals in samples
* [INTEGER]   `alternate_bases.AC_amr_female`
  - Alternate allele count for female samples of Latino ancestry
* [FLOAT]     `alternate_bases.AF_amr_female`
  - Alternate allele frequency in female samples of Latino ancestry
* [INTEGER]   `alternate_bases.nhomalt_amr_female`
  - Count of homozygous individuals in female samples of Latino ancestry
* [INTEGER]   `alternate_bases.AC_sas_female`
  - Alternate allele count for female samples of South Asian ancestry
* [FLOAT]     `alternate_bases.AF_sas_female`
  - Alternate allele frequency in female samples of South Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_sas_female`
  - Count of homozygous individuals in female samples of South Asian ancestry
* [INTEGER]   `alternate_bases.AC_fin`
  - Alternate allele count for samples of Finnish ancestry
* [FLOAT]     `alternate_bases.AF_fin`
  - Alternate allele frequency in samples of Finnish ancestry
* [INTEGER]   `alternate_bases.nhomalt_fin`
  - Count of homozygous individuals in samples of Finnish ancestry
* [INTEGER]   `alternate_bases.AC_afr_female`
  - Alternate allele count for female samples of African-American/African ancestry
* [FLOAT]     `alternate_bases.AF_afr_female`
  - Alternate allele frequency in female samples of African-American/African ancestry
* [INTEGER]   `alternate_bases.nhomalt_afr_female`
  - Count of homozygous individuals in female samples of African-American/African ancestry
* [INTEGER]   `alternate_bases.AC_sas_male`
  - Alternate allele count for male samples of South Asian ancestry
* [FLOAT]     `alternate_bases.AF_sas_male`
  - Alternate allele frequency in male samples of South Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_sas_male`
  - Count of homozygous individuals in male samples of South Asian ancestry
* [INTEGER]   `alternate_bases.AC_amr`
  - Alternate allele count for samples of Latino ancestry
* [FLOAT]     `alternate_bases.AF_amr`
  - Alternate allele frequency in samples of Latino ancestry
* [INTEGER]   `alternate_bases.nhomalt_amr`
  - Count of homozygous individuals in samples of Latino ancestry
* [INTEGER]   `alternate_bases.AC_nfe`
  - Alternate allele count for samples of Non-Finnish European ancestry
* [FLOAT]     `alternate_bases.AF_nfe`
  - Alternate allele frequency in samples of Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.nhomalt_nfe`
  - Count of homozygous individuals in samples of Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.AC_eas`
  - Alternate allele count for samples of East Asian ancestry
* [FLOAT]     `alternate_bases.AF_eas`
  - Alternate allele frequency in samples of East Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_eas`
  - Count of homozygous individuals in samples of East Asian ancestry
* [INTEGER]   `alternate_bases.AC_ami_male`
  - Alternate allele count for male samples of Amish ancestry
* [FLOAT]     `alternate_bases.AF_ami_male`
  - Alternate allele frequency in male samples of Amish ancestry
* [INTEGER]   `alternate_bases.nhomalt_ami_male`
  - Count of homozygous individuals in male samples of Amish ancestry
* [INTEGER]   `alternate_bases.AC_fin_female`
  - Alternate allele count for female samples of Finnish ancestry
* [FLOAT]     `alternate_bases.AF_fin_female`
  - Alternate allele frequency in female samples of Finnish ancestry
* [INTEGER]   `alternate_bases.nhomalt_fin_female`
  - Count of homozygous individuals in female samples of Finnish ancestry
* [FLOAT]     `alternate_bases.faf95_afr`
  - Filtering allele frequency (using Poisson 95% CI) for samples of African-American/African ancestry
* [FLOAT]     `alternate_bases.faf99_afr`
  - Filtering allele frequency (using Poisson 99% CI) for samples of African-American/African ancestry
* [FLOAT]     `alternate_bases.faf95_sas`
  - Filtering allele frequency (using Poisson 95% CI) for samples of South Asian ancestry
* [FLOAT]     `alternate_bases.faf99_sas`
  - Filtering allele frequency (using Poisson 99% CI) for samples of South Asian ancestry
* [FLOAT]     `alternate_bases.faf95_amr`
  - Filtering allele frequency (using Poisson 95% CI) for samples of Latino ancestry
* [FLOAT]     `alternate_bases.faf99_amr`
  - Filtering allele frequency (using Poisson 99% CI) for samples of Latino ancestry
* [FLOAT]     `alternate_bases.faf95_nfe`
  - Filtering allele frequency (using Poisson 95% CI) for samples of Non-Finnish European ancestry
* [FLOAT]     `alternate_bases.faf99_nfe`
  - Filtering allele frequency (using Poisson 99% CI) for samples of Non-Finnish European ancestry
* [FLOAT]     `alternate_bases.faf95_eas`
  - Filtering allele frequency (using Poisson 95% CI) for samples of East Asian ancestry
* [FLOAT]     `alternate_bases.faf99_eas`
  - Filtering allele frequency (using Poisson 99% CI) for samples of East Asian ancestry
* [RECORD]    `alternate_bases.vep`
  - List of vep annotations for this alternate.
* [STRING]    `alternate_bases.vep.allele`
  - The ALT part of the annotation field.
* [STRING]    `alternate_bases.vep.Consequence`
  - Consequence type of this variant
* [STRING]    `alternate_bases.vep.IMPACT`
  - The impact modifier for the consequence type
* [STRING]    `alternate_bases.vep.SYMBOL`
  - The gene symbol
* [STRING]    `alternate_bases.vep.Gene`
  - Ensembl stable ID of affected gene
* [STRING]    `alternate_bases.vep.Feature_type`
  - Type of feature. Currently one of Transcript, RegulatoryFeature, MotifFeature.
* [STRING]    `alternate_bases.vep.Feature`
  - Ensembl stable ID of feature
* [STRING]    `alternate_bases.vep.BIOTYPE`
  - Biotype of transcript or regulatory feature
* [STRING]    `alternate_bases.vep.EXON`
  - The exon number (out of total number)
* [STRING]    `alternate_bases.vep.INTRON`
  - The intron number (out of total number)
* [STRING]    `alternate_bases.vep.empty`
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
* [INTEGER]   `AN`
  - Total number of alleles in samples
* [BOOLEAN]   `non_par`
* [BOOLEAN]   `lcr`
  - Variant falls within a low complexity region
* [STRING]    `variant_type`
  - Variant type (snv, indel, multi-snv, multi-indel, or mixed)
* [FLOAT]     `ReadPosRankSum`
  - Z-score from Wilcoxon rank sum test of alternate vs. reference read position bias
* [FLOAT]     `MQRankSum`
  - Z-score from Wilcoxon rank sum test of alternate vs. reference read mapping qualities
* [FLOAT]     `RAW_MQ`
* [INTEGER]   `DP`
  - Depth of informative coverage for each sample; reads with MQ=255 or with bad mates are filtered
* [INTEGER]   `MQ_DP`
* [INTEGER]   `VarDP`
* [FLOAT]     `MQ`
  - Root mean square of the mapping quality of reads across all samples
* [FLOAT]     `QD`
  - Variant call confidence normalized by depth of sample reads supporting a variant
* [FLOAT]     `FS`
  - Phred-scaled p-value of Fisher's exact test for strand bias
* [INTEGER]   `SB`
* [FLOAT]     `InbreedingCoeff`
  - Inbreeding coefficient as estimated from the genotype likelihoods per-sample when compared against the Hardy-Weinberg expectation
* [FLOAT]     `AS_VQSLOD`
  - Log-odds ratio of being a true variant versus being a false positive under the trained allele-specific VQSR Gaussian mixture model
* [BOOLEAN]   `NEGATIVE_TRAIN_SITE`
  - Variant was used to build the negative training set of low-quality variants for VQSR
* [BOOLEAN]   `POSITIVE_TRAIN_SITE`
  - Variant was used to build the positive training set of high-quality variants for VQSR
* [STRING]    `culprit`
  - Worst-performing annotation in the VQSR Gaussian mixture model
* [FLOAT]     `SOR`
  - Strand bias estimated by the symmetric odds ratio test
* [INTEGER]   `AN_asj_female`
  - Total number of alleles in female samples of Ashkenazi Jewish ancestry
* [INTEGER]   `AN_eas_female`
  - Total number of alleles in female samples of East Asian ancestry
* [INTEGER]   `AN_afr_male`
  - Total number of alleles in male samples of African-American/African ancestry
* [INTEGER]   `AN_female`
  - Total number of alleles in female samples
* [INTEGER]   `AN_fin_male`
  - Total number of alleles in male samples of Finnish ancestry
* [INTEGER]   `AN_oth_female`
  - Total number of alleles in female samples of Other ancestry
* [INTEGER]   `AN_ami`
  - Total number of alleles in samples of Amish ancestry
* [INTEGER]   `AN_oth`
  - Total number of alleles in samples of Other ancestry
* [INTEGER]   `AN_male`
  - Total number of alleles in male samples
* [INTEGER]   `AN_ami_female`
  - Total number of alleles in female samples of Amish ancestry
* [INTEGER]   `AN_afr`
  - Total number of alleles in samples of African-American/African ancestry
* [INTEGER]   `AN_eas_male`
  - Total number of alleles in male samples of East Asian ancestry
* [INTEGER]   `AN_sas`
  - Total number of alleles in samples of South Asian ancestry
* [INTEGER]   `AN_nfe_female`
  - Total number of alleles in female samples of Non-Finnish European ancestry
* [INTEGER]   `AN_asj_male`
  - Total number of alleles in male samples of Ashkenazi Jewish ancestry
* [INTEGER]   `AN_raw`
  - Total number of alleles in samples, before removing low-confidence genotypes
* [INTEGER]   `AN_oth_male`
  - Total number of alleles in male samples of Other ancestry
* [INTEGER]   `AN_nfe_male`
  - Total number of alleles in male samples of Non-Finnish European ancestry
* [INTEGER]   `AN_asj`
  - Total number of alleles in samples of Ashkenazi Jewish ancestry
* [INTEGER]   `AN_amr_male`
  - Total number of alleles in male samples of Latino ancestry
* [INTEGER]   `AN_amr_female`
  - Total number of alleles in female samples of Latino ancestry
* [INTEGER]   `AN_sas_female`
  - Total number of alleles in female samples of South Asian ancestry
* [INTEGER]   `AN_fin`
  - Total number of alleles in samples of Finnish ancestry
* [INTEGER]   `AN_afr_female`
  - Total number of alleles in female samples of African-American/African ancestry
* [INTEGER]   `AN_sas_male`
  - Total number of alleles in male samples of South Asian ancestry
* [INTEGER]   `AN_amr`
  - Total number of alleles in samples of Latino ancestry
* [INTEGER]   `AN_nfe`
  - Total number of alleles in samples of Non-Finnish European ancestry
* [INTEGER]   `AN_eas`
  - Total number of alleles in samples of East Asian ancestry
* [INTEGER]   `AN_ami_male`
  - Total number of alleles in male samples of Amish ancestry
* [INTEGER]   `AN_fin_female`
  - Total number of alleles in female samples of Finnish ancestry
* [FLOAT]     `faf95_adj`
* [FLOAT]     `faf99_adj`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
