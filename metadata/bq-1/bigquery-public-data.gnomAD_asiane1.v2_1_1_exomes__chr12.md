# `gnomAD_asiane1.v2_1_1_exomes__chr12`
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
* [STRING]    `alternate_bases.allele_type`
  - Allele type (snv, ins, del, or mixed)
* [INTEGER]   `alternate_bases.n_alt_alleles`
  - Total number of alternate alleles observed at variant locus
* [FLOAT]     `alternate_bases.pab_max`
  - Maximum p-value over callset for binomial test of observed allele balance for a heterozygous genotype, given expectation of AB=0.5
* [STRING]    `alternate_bases.gq_hist_alt_bin_freq`
  - Histogram for GQ in heterozygous individuals; bin edges are: 0|5|10|15|20|25|30|35|40|45|50|55|60|65|70|75|80|85|90|95|100
* [STRING]    `alternate_bases.gq_hist_all_bin_freq`
  - Histogram for GQ; bin edges are: 0|5|10|15|20|25|30|35|40|45|50|55|60|65|70|75|80|85|90|95|100
* [STRING]    `alternate_bases.dp_hist_alt_bin_freq`
  - Histogram for DP in heterozygous individuals; bin edges are: 0|5|10|15|20|25|30|35|40|45|50|55|60|65|70|75|80|85|90|95|100
* [INTEGER]   `alternate_bases.dp_hist_alt_n_larger`
  - Count of DP values falling above highest histogram bin edge
* [STRING]    `alternate_bases.dp_hist_all_bin_freq`
  - Histogram for DP; bin edges are: 0|5|10|15|20|25|30|35|40|45|50|55|60|65|70|75|80|85|90|95|100
* [INTEGER]   `alternate_bases.dp_hist_all_n_larger`
  - Count of DP values falling above highest histogram bin edge
* [STRING]    `alternate_bases.ab_hist_alt_bin_freq`
  - Histogram for AB in heterozygous individuals; bin edges are: 0.00|0.05|0.10|0.15|0.20|0.25|0.30|0.35|0.40|0.45|0.50|0.55|0.60|0.65|0.70|0.75|0.80|0.85|0.90|0.95|1.00
* [INTEGER]   `alternate_bases.AC_nfe_seu`
  - Alternate allele count for samples of Southern European ancestry
* [FLOAT]     `alternate_bases.AF_nfe_seu`
  - Alternate allele frequency in samples of Southern European ancestry
* [INTEGER]   `alternate_bases.nhomalt_nfe_seu`
  - Count of homozygous individuals in samples of Southern European ancestry
* [INTEGER]   `alternate_bases.controls_AC_afr_male`
  - Alternate allele count for male samples of African-American/African ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_afr_male`
  - Alternate allele frequency in male samples of African-American/African ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_afr_male`
  - Count of homozygous individuals in male samples of African-American/African ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_eas_kor`
  - Alternate allele count for samples of Korean ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_eas_kor`
  - Alternate allele frequency in samples of Korean ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_eas_kor`
  - Count of homozygous individuals in samples of Korean ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_topmed_AC_amr`
  - Alternate allele count for samples of Latino ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_amr`
  - Alternate allele frequency in samples of Latino ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_amr`
  - Count of homozygous individuals in samples of Latino ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_cancer_AC_asj_female`
  - Alternate allele count for female samples of Ashkenazi Jewish ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_asj_female`
  - Alternate allele frequency in female samples of Ashkenazi Jewish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_asj_female`
  - Count of homozygous individuals in female samples of Ashkenazi Jewish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.AC_raw`
  - Alternate allele count for samples, before removing low-confidence genotypes
* [FLOAT]     `alternate_bases.AF_raw`
  - Alternate allele frequency in samples, before removing low-confidence genotypes
* [INTEGER]   `alternate_bases.nhomalt_raw`
  - Count of homozygous individuals in samples, before removing low-confidence genotypes
* [INTEGER]   `alternate_bases.AC_fin_female`
  - Alternate allele count for female samples of Finnish ancestry
* [FLOAT]     `alternate_bases.AF_fin_female`
  - Alternate allele frequency in female samples of Finnish ancestry
* [INTEGER]   `alternate_bases.nhomalt_fin_female`
  - Count of homozygous individuals in female samples of Finnish ancestry
* [INTEGER]   `alternate_bases.non_cancer_AC_oth_female`
  - Alternate allele count for female samples of Other ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_oth_female`
  - Alternate allele frequency in female samples of Other ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_oth_female`
  - Count of homozygous individuals in female samples of Other ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.AC_nfe_bgr`
  - Alternate allele count for samples of Bulgarian (Eastern European) ancestry
* [FLOAT]     `alternate_bases.AF_nfe_bgr`
  - Alternate allele frequency in samples of Bulgarian (Eastern European) ancestry
* [INTEGER]   `alternate_bases.nhomalt_nfe_bgr`
  - Count of homozygous individuals in samples of Bulgarian (Eastern European) ancestry
* [INTEGER]   `alternate_bases.non_neuro_AC_asj_female`
  - Alternate allele count for female samples of Ashkenazi Jewish ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_asj_female`
  - Alternate allele frequency in female samples of Ashkenazi Jewish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_asj_female`
  - Count of homozygous individuals in female samples of Ashkenazi Jewish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.AC_sas_male`
  - Alternate allele count for male samples of South Asian ancestry
* [FLOAT]     `alternate_bases.AF_sas_male`
  - Alternate allele frequency in male samples of South Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_sas_male`
  - Count of homozygous individuals in male samples of South Asian ancestry
* [INTEGER]   `alternate_bases.non_neuro_AC_afr_male`
  - Alternate allele count for male samples of African-American/African ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_afr_male`
  - Alternate allele frequency in male samples of African-American/African ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_afr_male`
  - Count of homozygous individuals in male samples of African-American/African ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.AC_afr_male`
  - Alternate allele count for male samples of African-American/African ancestry
* [FLOAT]     `alternate_bases.AF_afr_male`
  - Alternate allele frequency in male samples of African-American/African ancestry
* [INTEGER]   `alternate_bases.nhomalt_afr_male`
  - Count of homozygous individuals in male samples of African-American/African ancestry
* [INTEGER]   `alternate_bases.AC_afr`
  - Alternate allele count for samples of African-American/African ancestry
* [FLOAT]     `alternate_bases.AF_afr`
  - Alternate allele frequency in samples of African-American/African ancestry
* [INTEGER]   `alternate_bases.nhomalt_afr`
  - Count of homozygous individuals in samples of African-American/African ancestry
* [INTEGER]   `alternate_bases.controls_AC_nfe_swe`
  - Alternate allele count for samples of Swedish ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_nfe_swe`
  - Alternate allele frequency in samples of Swedish ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_nfe_swe`
  - Count of homozygous individuals in samples of Swedish ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_afr_female`
  - Alternate allele count for female samples of African-American/African ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_afr_female`
  - Alternate allele frequency in female samples of African-American/African ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_afr_female`
  - Count of homozygous individuals in female samples of African-American/African ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_topmed_AC_amr_female`
  - Alternate allele count for female samples of Latino ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_amr_female`
  - Alternate allele frequency in female samples of Latino ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_amr_female`
  - Count of homozygous individuals in female samples of Latino ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_cancer_AC_female`
  - Alternate allele count for female samples in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_female`
  - Alternate allele frequency in female samples in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_female`
  - Count of homozygous individuals in female samples in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_AC_nfe_onf`
  - Alternate allele count for samples of Other Non-Finnish European ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_nfe_onf`
  - Alternate allele frequency in samples of Other Non-Finnish European ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_nfe_onf`
  - Count of homozygous individuals in samples of Other Non-Finnish European ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_AC_male`
  - Alternate allele count for male samples in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_male`
  - Alternate allele frequency in male samples in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_male`
  - Count of homozygous individuals in male samples in the non_cancer subset
* [INTEGER]   `alternate_bases.non_topmed_AC_oth_female`
  - Alternate allele count for female samples of Other ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_oth_female`
  - Alternate allele frequency in female samples of Other ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_oth_female`
  - Count of homozygous individuals in female samples of Other ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.AC_eas_female`
  - Alternate allele count for female samples of East Asian ancestry
* [FLOAT]     `alternate_bases.AF_eas_female`
  - Alternate allele frequency in female samples of East Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_eas_female`
  - Count of homozygous individuals in female samples of East Asian ancestry
* [INTEGER]   `alternate_bases.non_cancer_AC_sas_female`
  - Alternate allele count for female samples of South Asian ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_sas_female`
  - Alternate allele frequency in female samples of South Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_sas_female`
  - Count of homozygous individuals in female samples of South Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.AC_afr_female`
  - Alternate allele count for female samples of African-American/African ancestry
* [FLOAT]     `alternate_bases.AF_afr_female`
  - Alternate allele frequency in female samples of African-American/African ancestry
* [INTEGER]   `alternate_bases.nhomalt_afr_female`
  - Count of homozygous individuals in female samples of African-American/African ancestry
* [INTEGER]   `alternate_bases.AC_sas`
  - Alternate allele count for samples of South Asian ancestry
* [FLOAT]     `alternate_bases.AF_sas`
  - Alternate allele frequency in samples of South Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_sas`
  - Count of homozygous individuals in samples of South Asian ancestry
* [INTEGER]   `alternate_bases.non_neuro_AC_female`
  - Alternate allele count for female samples in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_female`
  - Alternate allele frequency in female samples in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_female`
  - Count of homozygous individuals in female samples in the non_neuro subset
* [INTEGER]   `alternate_bases.controls_AC_afr`
  - Alternate allele count for samples of African-American/African ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_afr`
  - Alternate allele frequency in samples of African-American/African ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_afr`
  - Count of homozygous individuals in samples of African-American/African ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_eas_jpn`
  - Alternate allele count for samples of Japanese ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_eas_jpn`
  - Alternate allele frequency in samples of Japanese ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_eas_jpn`
  - Count of homozygous individuals in samples of Japanese ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.AC_nfe_onf`
  - Alternate allele count for samples of Other Non-Finnish European ancestry
* [FLOAT]     `alternate_bases.AF_nfe_onf`
  - Alternate allele frequency in samples of Other Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.nhomalt_nfe_onf`
  - Count of homozygous individuals in samples of Other Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.non_cancer_AC_amr_male`
  - Alternate allele count for male samples of Latino ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_amr_male`
  - Alternate allele frequency in male samples of Latino ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_amr_male`
  - Count of homozygous individuals in male samples of Latino ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.controls_AC_fin_male`
  - Alternate allele count for male samples of Finnish ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_fin_male`
  - Alternate allele frequency in male samples of Finnish ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_fin_male`
  - Count of homozygous individuals in male samples of Finnish ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_nfe_nwe`
  - Alternate allele count for samples of North-Western European ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_nfe_nwe`
  - Alternate allele frequency in samples of North-Western European ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_nfe_nwe`
  - Count of homozygous individuals in samples of North-Western European ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.AC_fin_male`
  - Alternate allele count for male samples of Finnish ancestry
* [FLOAT]     `alternate_bases.AF_fin_male`
  - Alternate allele frequency in male samples of Finnish ancestry
* [INTEGER]   `alternate_bases.nhomalt_fin_male`
  - Count of homozygous individuals in male samples of Finnish ancestry
* [INTEGER]   `alternate_bases.AC_nfe_female`
  - Alternate allele count for female samples of Non-Finnish European ancestry
* [FLOAT]     `alternate_bases.AF_nfe_female`
  - Alternate allele frequency in female samples of Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.nhomalt_nfe_female`
  - Count of homozygous individuals in female samples of Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.AC_amr`
  - Alternate allele count for samples of Latino ancestry
* [FLOAT]     `alternate_bases.AF_amr`
  - Alternate allele frequency in samples of Latino ancestry
* [INTEGER]   `alternate_bases.nhomalt_amr`
  - Count of homozygous individuals in samples of Latino ancestry
* [INTEGER]   `alternate_bases.non_topmed_AC_nfe_male`
  - Alternate allele count for male samples of Non-Finnish European ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_nfe_male`
  - Alternate allele frequency in male samples of Non-Finnish European ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_nfe_male`
  - Count of homozygous individuals in male samples of Non-Finnish European ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_neuro_AC_sas`
  - Alternate allele count for samples of South Asian ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_sas`
  - Alternate allele frequency in samples of South Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_sas`
  - Count of homozygous individuals in samples of South Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_cancer_AC_fin_male`
  - Alternate allele count for male samples of Finnish ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_fin_male`
  - Alternate allele frequency in male samples of Finnish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_fin_male`
  - Count of homozygous individuals in male samples of Finnish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_AC_nfe_seu`
  - Alternate allele count for samples of Southern European ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_nfe_seu`
  - Alternate allele frequency in samples of Southern European ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_nfe_seu`
  - Count of homozygous individuals in samples of Southern European ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.AC_eas`
  - Alternate allele count for samples of East Asian ancestry
* [FLOAT]     `alternate_bases.AF_eas`
  - Alternate allele frequency in samples of East Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_eas`
  - Count of homozygous individuals in samples of East Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt`
  - Count of homozygous individuals in samples
* [INTEGER]   `alternate_bases.non_neuro_AC_nfe_female`
  - Alternate allele count for female samples of Non-Finnish European ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_nfe_female`
  - Alternate allele frequency in female samples of Non-Finnish European ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_nfe_female`
  - Count of homozygous individuals in female samples of Non-Finnish European ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_AC_afr`
  - Alternate allele count for samples of African-American/African ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_afr`
  - Alternate allele frequency in samples of African-American/African ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_afr`
  - Count of homozygous individuals in samples of African-American/African ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.controls_AC_raw`
  - Alternate allele count for samples in the controls subset, before removing low-confidence genotypes
* [FLOAT]     `alternate_bases.controls_AF_raw`
  - Alternate allele frequency in samples in the controls subset, before removing low-confidence genotypes
* [INTEGER]   `alternate_bases.controls_nhomalt_raw`
  - Count of homozygous individuals in samples in the controls subset, before removing low-confidence genotypes
* [INTEGER]   `alternate_bases.non_cancer_AC_eas`
  - Alternate allele count for samples of East Asian ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_eas`
  - Alternate allele frequency in samples of East Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_eas`
  - Count of homozygous individuals in samples of East Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_AC_amr_female`
  - Alternate allele count for female samples of Latino ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_amr_female`
  - Alternate allele frequency in female samples of Latino ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_amr_female`
  - Count of homozygous individuals in female samples of Latino ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_neuro_AC_nfe_swe`
  - Alternate allele count for samples of Swedish ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_nfe_swe`
  - Alternate allele frequency in samples of Swedish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_nfe_swe`
  - Count of homozygous individuals in samples of Swedish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.controls_AC_male`
  - Alternate allele count for male samples in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_male`
  - Alternate allele frequency in male samples in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_male`
  - Count of homozygous individuals in male samples in the controls subset
* [INTEGER]   `alternate_bases.non_topmed_AC_male`
  - Alternate allele count for male samples in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_male`
  - Alternate allele frequency in male samples in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_male`
  - Count of homozygous individuals in male samples in the non_topmed subset
* [INTEGER]   `alternate_bases.controls_AC_eas_jpn`
  - Alternate allele count for samples of Japanese ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_eas_jpn`
  - Alternate allele frequency in samples of Japanese ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_eas_jpn`
  - Count of homozygous individuals in samples of Japanese ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_AC_nfe_female`
  - Alternate allele count for female samples of Non-Finnish European ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_nfe_female`
  - Alternate allele frequency in female samples of Non-Finnish European ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_nfe_female`
  - Count of homozygous individuals in female samples of Non-Finnish European ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_amr`
  - Alternate allele count for samples of Latino ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_amr`
  - Alternate allele frequency in samples of Latino ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_amr`
  - Count of homozygous individuals in samples of Latino ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_AC_eas_female`
  - Alternate allele count for female samples of East Asian ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_eas_female`
  - Alternate allele frequency in female samples of East Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_eas_female`
  - Count of homozygous individuals in female samples of East Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.AC_asj_male`
  - Alternate allele count for male samples of Ashkenazi Jewish ancestry
* [FLOAT]     `alternate_bases.AF_asj_male`
  - Alternate allele frequency in male samples of Ashkenazi Jewish ancestry
* [INTEGER]   `alternate_bases.nhomalt_asj_male`
  - Count of homozygous individuals in male samples of Ashkenazi Jewish ancestry
* [INTEGER]   `alternate_bases.controls_AC_nfe_male`
  - Alternate allele count for male samples of Non-Finnish European ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_nfe_male`
  - Alternate allele frequency in male samples of Non-Finnish European ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_nfe_male`
  - Count of homozygous individuals in male samples of Non-Finnish European ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_fin`
  - Alternate allele count for samples of Finnish ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_fin`
  - Alternate allele frequency in samples of Finnish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_fin`
  - Count of homozygous individuals in samples of Finnish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_topmed_AC_sas`
  - Alternate allele count for samples of South Asian ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_sas`
  - Alternate allele frequency in samples of South Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_sas`
  - Count of homozygous individuals in samples of South Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_cancer_AC_nfe_female`
  - Alternate allele count for female samples of Non-Finnish European ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_nfe_female`
  - Alternate allele frequency in female samples of Non-Finnish European ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_nfe_female`
  - Count of homozygous individuals in female samples of Non-Finnish European ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.AC_oth_female`
  - Alternate allele count for female samples of Other ancestry
* [FLOAT]     `alternate_bases.AF_oth_female`
  - Alternate allele frequency in female samples of Other ancestry
* [INTEGER]   `alternate_bases.nhomalt_oth_female`
  - Count of homozygous individuals in female samples of Other ancestry
* [INTEGER]   `alternate_bases.non_cancer_AC_asj`
  - Alternate allele count for samples of Ashkenazi Jewish ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_asj`
  - Alternate allele frequency in samples of Ashkenazi Jewish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_asj`
  - Count of homozygous individuals in samples of Ashkenazi Jewish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.AC_nfe_swe`
  - Alternate allele count for samples of Swedish ancestry
* [FLOAT]     `alternate_bases.AF_nfe_swe`
  - Alternate allele frequency in samples of Swedish ancestry
* [INTEGER]   `alternate_bases.nhomalt_nfe_swe`
  - Count of homozygous individuals in samples of Swedish ancestry
* [INTEGER]   `alternate_bases.controls_AC_nfe`
  - Alternate allele count for samples of Non-Finnish European ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_nfe`
  - Alternate allele frequency in samples of Non-Finnish European ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_nfe`
  - Count of homozygous individuals in samples of Non-Finnish European ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_AC_oth_female`
  - Alternate allele count for female samples of Other ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_oth_female`
  - Alternate allele frequency in female samples of Other ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_oth_female`
  - Count of homozygous individuals in female samples of Other ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_AC_asj`
  - Alternate allele count for samples of Ashkenazi Jewish ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_asj`
  - Alternate allele frequency in samples of Ashkenazi Jewish ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_asj`
  - Count of homozygous individuals in samples of Ashkenazi Jewish ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_amr_male`
  - Alternate allele count for male samples of Latino ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_amr_male`
  - Alternate allele frequency in male samples of Latino ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_amr_male`
  - Count of homozygous individuals in male samples of Latino ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.controls_AC_nfe_nwe`
  - Alternate allele count for samples of North-Western European ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_nfe_nwe`
  - Alternate allele frequency in samples of North-Western European ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_nfe_nwe`
  - Count of homozygous individuals in samples of North-Western European ancestry in the controls subset
* [INTEGER]   `alternate_bases.AC_nfe_nwe`
  - Alternate allele count for samples of North-Western European ancestry
* [FLOAT]     `alternate_bases.AF_nfe_nwe`
  - Alternate allele frequency in samples of North-Western European ancestry
* [INTEGER]   `alternate_bases.nhomalt_nfe_nwe`
  - Count of homozygous individuals in samples of North-Western European ancestry
* [INTEGER]   `alternate_bases.controls_AC_nfe_seu`
  - Alternate allele count for samples of Southern European ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_nfe_seu`
  - Alternate allele frequency in samples of Southern European ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_nfe_seu`
  - Count of homozygous individuals in samples of Southern European ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_AC_sas_female`
  - Alternate allele count for female samples of South Asian ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_sas_female`
  - Alternate allele frequency in female samples of South Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_sas_female`
  - Count of homozygous individuals in female samples of South Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_amr_female`
  - Alternate allele count for female samples of Latino ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_amr_female`
  - Alternate allele frequency in female samples of Latino ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_amr_female`
  - Count of homozygous individuals in female samples of Latino ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_cancer_AC_eas_jpn`
  - Alternate allele count for samples of Japanese ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_eas_jpn`
  - Alternate allele frequency in samples of Japanese ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_eas_jpn`
  - Count of homozygous individuals in samples of Japanese ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_neuro_AC_nfe_onf`
  - Alternate allele count for samples of Other Non-Finnish European ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_nfe_onf`
  - Alternate allele frequency in samples of Other Non-Finnish European ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_nfe_onf`
  - Count of homozygous individuals in samples of Other Non-Finnish European ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_topmed_AC_eas_male`
  - Alternate allele count for male samples of East Asian ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_eas_male`
  - Alternate allele frequency in male samples of East Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_eas_male`
  - Count of homozygous individuals in male samples of East Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.AC_eas_jpn`
  - Alternate allele count for samples of Japanese ancestry
* [FLOAT]     `alternate_bases.AF_eas_jpn`
  - Alternate allele frequency in samples of Japanese ancestry
* [INTEGER]   `alternate_bases.nhomalt_eas_jpn`
  - Count of homozygous individuals in samples of Japanese ancestry
* [INTEGER]   `alternate_bases.non_cancer_AC_afr_male`
  - Alternate allele count for male samples of African-American/African ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_afr_male`
  - Alternate allele frequency in male samples of African-American/African ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_afr_male`
  - Count of homozygous individuals in male samples of African-American/African ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_AC_afr`
  - Alternate allele count for samples of African-American/African ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_afr`
  - Alternate allele frequency in samples of African-American/African ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_afr`
  - Count of homozygous individuals in samples of African-American/African ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.controls_AC_amr_female`
  - Alternate allele count for female samples of Latino ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_amr_female`
  - Alternate allele frequency in female samples of Latino ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_amr_female`
  - Count of homozygous individuals in female samples of Latino ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_fin_male`
  - Alternate allele count for male samples of Finnish ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_fin_male`
  - Alternate allele frequency in male samples of Finnish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_fin_male`
  - Count of homozygous individuals in male samples of Finnish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.AC_female`
  - Alternate allele count for female samples
* [FLOAT]     `alternate_bases.AF_female`
  - Alternate allele frequency in female samples
* [INTEGER]   `alternate_bases.nhomalt_female`
  - Count of homozygous individuals in female samples
* [INTEGER]   `alternate_bases.non_neuro_AC_nfe_bgr`
  - Alternate allele count for samples of Bulgarian (Eastern European) ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_nfe_bgr`
  - Alternate allele frequency in samples of Bulgarian (Eastern European) ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_nfe_bgr`
  - Count of homozygous individuals in samples of Bulgarian (Eastern European) ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_AC_oth_male`
  - Alternate allele count for male samples of Other ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_oth_male`
  - Alternate allele frequency in male samples of Other ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_oth_male`
  - Count of homozygous individuals in male samples of Other ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_topmed_AC_nfe_est`
  - Alternate allele count for samples of Estonian ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_nfe_est`
  - Alternate allele frequency in samples of Estonian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_nfe_est`
  - Count of homozygous individuals in samples of Estonian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_AC_nfe_nwe`
  - Alternate allele count for samples of North-Western European ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_nfe_nwe`
  - Alternate allele frequency in samples of North-Western European ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_nfe_nwe`
  - Count of homozygous individuals in samples of North-Western European ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_AC_amr_male`
  - Alternate allele count for male samples of Latino ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_amr_male`
  - Alternate allele frequency in male samples of Latino ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_amr_male`
  - Count of homozygous individuals in male samples of Latino ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_cancer_AC_amr`
  - Alternate allele count for samples of Latino ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_amr`
  - Alternate allele frequency in samples of Latino ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_amr`
  - Count of homozygous individuals in samples of Latino ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_topmed_AC_nfe_swe`
  - Alternate allele count for samples of Swedish ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_nfe_swe`
  - Alternate allele frequency in samples of Swedish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_nfe_swe`
  - Count of homozygous individuals in samples of Swedish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_AC_nfe_onf`
  - Alternate allele count for samples of Other Non-Finnish European ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_nfe_onf`
  - Alternate allele frequency in samples of Other Non-Finnish European ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_nfe_onf`
  - Count of homozygous individuals in samples of Other Non-Finnish European ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.controls_AC_eas_kor`
  - Alternate allele count for samples of Korean ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_eas_kor`
  - Alternate allele frequency in samples of Korean ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_eas_kor`
  - Count of homozygous individuals in samples of Korean ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_topmed_AC_eas_oea`
  - Alternate allele count for samples of Other East Asian ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_eas_oea`
  - Alternate allele frequency in samples of Other East Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_eas_oea`
  - Count of homozygous individuals in samples of Other East Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.controls_AC_eas_male`
  - Alternate allele count for male samples of East Asian ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_eas_male`
  - Alternate allele frequency in male samples of East Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_eas_male`
  - Count of homozygous individuals in male samples of East Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_AC_oth_male`
  - Alternate allele count for male samples of Other ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_oth_male`
  - Alternate allele frequency in male samples of Other ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_oth_male`
  - Count of homozygous individuals in male samples of Other ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_topmed_AC`
  - Alternate allele count for samples in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF`
  - Alternate allele frequency in samples in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt`
  - Count of homozygous individuals in samples in the non_topmed subset
* [INTEGER]   `alternate_bases.controls_AC_fin`
  - Alternate allele count for samples of Finnish ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_fin`
  - Alternate allele frequency in samples of Finnish ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_fin`
  - Count of homozygous individuals in samples of Finnish ancestry in the controls subset
* [INTEGER]   `alternate_bases.AC_eas_kor`
  - Alternate allele count for samples of Korean ancestry
* [FLOAT]     `alternate_bases.AF_eas_kor`
  - Alternate allele frequency in samples of Korean ancestry
* [INTEGER]   `alternate_bases.nhomalt_eas_kor`
  - Count of homozygous individuals in samples of Korean ancestry
* [INTEGER]   `alternate_bases.non_neuro_AC_nfe`
  - Alternate allele count for samples of Non-Finnish European ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_nfe`
  - Alternate allele frequency in samples of Non-Finnish European ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_nfe`
  - Count of homozygous individuals in samples of Non-Finnish European ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_AC_fin_female`
  - Alternate allele count for female samples of Finnish ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_fin_female`
  - Alternate allele frequency in female samples of Finnish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_fin_female`
  - Count of homozygous individuals in female samples of Finnish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_cancer_AC_nfe_male`
  - Alternate allele count for male samples of Non-Finnish European ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_nfe_male`
  - Alternate allele frequency in male samples of Non-Finnish European ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_nfe_male`
  - Count of homozygous individuals in male samples of Non-Finnish European ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.controls_AC_eas_oea`
  - Alternate allele count for samples of Other East Asian ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_eas_oea`
  - Alternate allele frequency in samples of Other East Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_eas_oea`
  - Count of homozygous individuals in samples of Other East Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_topmed_AC_nfe_seu`
  - Alternate allele count for samples of Southern European ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_nfe_seu`
  - Alternate allele frequency in samples of Southern European ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_nfe_seu`
  - Count of homozygous individuals in samples of Southern European ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.controls_AC_eas_female`
  - Alternate allele count for female samples of East Asian ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_eas_female`
  - Alternate allele frequency in female samples of East Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_eas_female`
  - Count of homozygous individuals in female samples of East Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_topmed_AC_asj`
  - Alternate allele count for samples of Ashkenazi Jewish ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_asj`
  - Alternate allele frequency in samples of Ashkenazi Jewish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_asj`
  - Count of homozygous individuals in samples of Ashkenazi Jewish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.controls_AC_nfe_onf`
  - Alternate allele count for samples of Other Non-Finnish European ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_nfe_onf`
  - Alternate allele frequency in samples of Other Non-Finnish European ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_nfe_onf`
  - Count of homozygous individuals in samples of Other Non-Finnish European ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC`
  - Alternate allele count for samples in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF`
  - Alternate allele frequency in samples in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt`
  - Count of homozygous individuals in samples in the non_neuro subset
* [INTEGER]   `alternate_bases.AC_eas_oea`
  - Alternate allele count for samples of Other East Asian ancestry
* [FLOAT]     `alternate_bases.AF_eas_oea`
  - Alternate allele frequency in samples of Other East Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_eas_oea`
  - Count of homozygous individuals in samples of Other East Asian ancestry
* [INTEGER]   `alternate_bases.non_topmed_AC_nfe`
  - Alternate allele count for samples of Non-Finnish European ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_nfe`
  - Alternate allele frequency in samples of Non-Finnish European ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_nfe`
  - Count of homozygous individuals in samples of Non-Finnish European ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_cancer_AC_oth`
  - Alternate allele count for samples of Other ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_oth`
  - Alternate allele frequency in samples of Other ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_oth`
  - Count of homozygous individuals in samples of Other ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_topmed_AC_raw`
  - Alternate allele count for samples in the non_topmed subset, before removing low-confidence genotypes
* [FLOAT]     `alternate_bases.non_topmed_AF_raw`
  - Alternate allele frequency in samples in the non_topmed subset, before removing low-confidence genotypes
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_raw`
  - Count of homozygous individuals in samples in the non_topmed subset, before removing low-confidence genotypes
* [INTEGER]   `alternate_bases.non_neuro_AC_nfe_est`
  - Alternate allele count for samples of Estonian ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_nfe_est`
  - Alternate allele frequency in samples of Estonian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_nfe_est`
  - Count of homozygous individuals in samples of Estonian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_topmed_AC_oth_male`
  - Alternate allele count for male samples of Other ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_oth_male`
  - Alternate allele frequency in male samples of Other ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_oth_male`
  - Count of homozygous individuals in male samples of Other ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_cancer_AC_oth_male`
  - Alternate allele count for male samples of Other ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_oth_male`
  - Alternate allele frequency in male samples of Other ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_oth_male`
  - Count of homozygous individuals in male samples of Other ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.AC_nfe_est`
  - Alternate allele count for samples of Estonian ancestry
* [FLOAT]     `alternate_bases.AF_nfe_est`
  - Alternate allele frequency in samples of Estonian ancestry
* [INTEGER]   `alternate_bases.nhomalt_nfe_est`
  - Count of homozygous individuals in samples of Estonian ancestry
* [INTEGER]   `alternate_bases.non_cancer_AC_afr_female`
  - Alternate allele count for female samples of African-American/African ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_afr_female`
  - Alternate allele frequency in female samples of African-American/African ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_afr_female`
  - Count of homozygous individuals in female samples of African-American/African ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_topmed_AC_afr_male`
  - Alternate allele count for male samples of African-American/African ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_afr_male`
  - Alternate allele frequency in male samples of African-American/African ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_afr_male`
  - Count of homozygous individuals in male samples of African-American/African ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.AC_eas_male`
  - Alternate allele count for male samples of East Asian ancestry
* [FLOAT]     `alternate_bases.AF_eas_male`
  - Alternate allele frequency in male samples of East Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_eas_male`
  - Count of homozygous individuals in male samples of East Asian ancestry
* [INTEGER]   `alternate_bases.controls_AC_eas`
  - Alternate allele count for samples of East Asian ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_eas`
  - Alternate allele frequency in samples of East Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_eas`
  - Count of homozygous individuals in samples of East Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_eas_male`
  - Alternate allele count for male samples of East Asian ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_eas_male`
  - Alternate allele frequency in male samples of East Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_eas_male`
  - Count of homozygous individuals in male samples of East Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_cancer_AC_nfe_nwe`
  - Alternate allele count for samples of North-Western European ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_nfe_nwe`
  - Alternate allele frequency in samples of North-Western European ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_nfe_nwe`
  - Count of homozygous individuals in samples of North-Western European ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.controls_AC_sas`
  - Alternate allele count for samples of South Asian ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_sas`
  - Alternate allele frequency in samples of South Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_sas`
  - Count of homozygous individuals in samples of South Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_sas_male`
  - Alternate allele count for male samples of South Asian ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_sas_male`
  - Alternate allele frequency in male samples of South Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_sas_male`
  - Count of homozygous individuals in male samples of South Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_AC_asj_male`
  - Alternate allele count for male samples of Ashkenazi Jewish ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_asj_male`
  - Alternate allele frequency in male samples of Ashkenazi Jewish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_asj_male`
  - Count of homozygous individuals in male samples of Ashkenazi Jewish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_cancer_AC_nfe_bgr`
  - Alternate allele count for samples of Bulgarian (Eastern European) ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_nfe_bgr`
  - Alternate allele frequency in samples of Bulgarian (Eastern European) ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_nfe_bgr`
  - Count of homozygous individuals in samples of Bulgarian (Eastern European) ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.controls_AC_oth`
  - Alternate allele count for samples of Other ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_oth`
  - Alternate allele frequency in samples of Other ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_oth`
  - Count of homozygous individuals in samples of Other ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_cancer_AC_eas_female`
  - Alternate allele count for female samples of East Asian ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_eas_female`
  - Alternate allele frequency in female samples of East Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_eas_female`
  - Count of homozygous individuals in female samples of East Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.AC_nfe`
  - Alternate allele count for samples of Non-Finnish European ancestry
* [FLOAT]     `alternate_bases.AF_nfe`
  - Alternate allele frequency in samples of Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.nhomalt_nfe`
  - Count of homozygous individuals in samples of Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.non_topmed_AC_female`
  - Alternate allele count for female samples in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_female`
  - Alternate allele frequency in female samples in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_female`
  - Count of homozygous individuals in female samples in the non_topmed subset
* [INTEGER]   `alternate_bases.non_neuro_AC_asj`
  - Alternate allele count for samples of Ashkenazi Jewish ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_asj`
  - Alternate allele frequency in samples of Ashkenazi Jewish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_asj`
  - Count of homozygous individuals in samples of Ashkenazi Jewish ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_topmed_AC_eas_female`
  - Alternate allele count for female samples of East Asian ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_eas_female`
  - Alternate allele frequency in female samples of East Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_eas_female`
  - Count of homozygous individuals in female samples of East Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_neuro_AC_raw`
  - Alternate allele count for samples in the non_neuro subset, before removing low-confidence genotypes
* [FLOAT]     `alternate_bases.non_neuro_AF_raw`
  - Alternate allele frequency in samples in the non_neuro subset, before removing low-confidence genotypes
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_raw`
  - Count of homozygous individuals in samples in the non_neuro subset, before removing low-confidence genotypes
* [INTEGER]   `alternate_bases.non_topmed_AC_eas`
  - Alternate allele count for samples of East Asian ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_eas`
  - Alternate allele frequency in samples of East Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_eas`
  - Count of homozygous individuals in samples of East Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_AC_fin_male`
  - Alternate allele count for male samples of Finnish ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_fin_male`
  - Alternate allele frequency in male samples of Finnish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_fin_male`
  - Count of homozygous individuals in male samples of Finnish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_cancer_AC_asj_male`
  - Alternate allele count for male samples of Ashkenazi Jewish ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_asj_male`
  - Alternate allele frequency in male samples of Ashkenazi Jewish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_asj_male`
  - Count of homozygous individuals in male samples of Ashkenazi Jewish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.AC_fin`
  - Alternate allele count for samples of Finnish ancestry
* [FLOAT]     `alternate_bases.AF_fin`
  - Alternate allele frequency in samples of Finnish ancestry
* [INTEGER]   `alternate_bases.nhomalt_fin`
  - Count of homozygous individuals in samples of Finnish ancestry
* [INTEGER]   `alternate_bases.AC_nfe_male`
  - Alternate allele count for male samples of Non-Finnish European ancestry
* [FLOAT]     `alternate_bases.AF_nfe_male`
  - Alternate allele frequency in male samples of Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.nhomalt_nfe_male`
  - Count of homozygous individuals in male samples of Non-Finnish European ancestry
* [INTEGER]   `alternate_bases.non_topmed_AC_eas_kor`
  - Alternate allele count for samples of Korean ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_eas_kor`
  - Alternate allele frequency in samples of Korean ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_eas_kor`
  - Count of homozygous individuals in samples of Korean ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.controls_AC_amr_male`
  - Alternate allele count for male samples of Latino ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_amr_male`
  - Alternate allele frequency in male samples of Latino ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_amr_male`
  - Count of homozygous individuals in male samples of Latino ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_eas_oea`
  - Alternate allele count for samples of Other East Asian ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_eas_oea`
  - Alternate allele frequency in samples of Other East Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_eas_oea`
  - Count of homozygous individuals in samples of Other East Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.AC_sas_female`
  - Alternate allele count for female samples of South Asian ancestry
* [FLOAT]     `alternate_bases.AF_sas_female`
  - Alternate allele frequency in female samples of South Asian ancestry
* [INTEGER]   `alternate_bases.nhomalt_sas_female`
  - Count of homozygous individuals in female samples of South Asian ancestry
* [INTEGER]   `alternate_bases.controls_AC_afr_female`
  - Alternate allele count for female samples of African-American/African ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_afr_female`
  - Alternate allele frequency in female samples of African-American/African ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_afr_female`
  - Count of homozygous individuals in female samples of African-American/African ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_AC_amr`
  - Alternate allele count for samples of Latino ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_amr`
  - Alternate allele frequency in samples of Latino ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_amr`
  - Count of homozygous individuals in samples of Latino ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_topmed_AC_eas_jpn`
  - Alternate allele count for samples of Japanese ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_eas_jpn`
  - Alternate allele frequency in samples of Japanese ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_eas_jpn`
  - Count of homozygous individuals in samples of Japanese ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.AC_asj_female`
  - Alternate allele count for female samples of Ashkenazi Jewish ancestry
* [FLOAT]     `alternate_bases.AF_asj_female`
  - Alternate allele frequency in female samples of Ashkenazi Jewish ancestry
* [INTEGER]   `alternate_bases.nhomalt_asj_female`
  - Count of homozygous individuals in female samples of Ashkenazi Jewish ancestry
* [INTEGER]   `alternate_bases.non_topmed_AC_nfe_bgr`
  - Alternate allele count for samples of Bulgarian (Eastern European) ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_nfe_bgr`
  - Alternate allele frequency in samples of Bulgarian (Eastern European) ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_nfe_bgr`
  - Count of homozygous individuals in samples of Bulgarian (Eastern European) ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_cancer_AC_nfe_est`
  - Alternate allele count for samples of Estonian ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_nfe_est`
  - Alternate allele frequency in samples of Estonian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_nfe_est`
  - Count of homozygous individuals in samples of Estonian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_neuro_AC_eas`
  - Alternate allele count for samples of East Asian ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_eas`
  - Alternate allele frequency in samples of East Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_eas`
  - Count of homozygous individuals in samples of East Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_cancer_AC_nfe`
  - Alternate allele count for samples of Non-Finnish European ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_nfe`
  - Alternate allele frequency in samples of Non-Finnish European ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_nfe`
  - Count of homozygous individuals in samples of Non-Finnish European ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_neuro_AC_male`
  - Alternate allele count for male samples in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_male`
  - Alternate allele frequency in male samples in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_male`
  - Count of homozygous individuals in male samples in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_AC_sas_female`
  - Alternate allele count for female samples of South Asian ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_sas_female`
  - Alternate allele frequency in female samples of South Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_sas_female`
  - Count of homozygous individuals in female samples of South Asian ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.AC_asj`
  - Alternate allele count for samples of Ashkenazi Jewish ancestry
* [FLOAT]     `alternate_bases.AF_asj`
  - Alternate allele frequency in samples of Ashkenazi Jewish ancestry
* [INTEGER]   `alternate_bases.nhomalt_asj`
  - Count of homozygous individuals in samples of Ashkenazi Jewish ancestry
* [INTEGER]   `alternate_bases.controls_AC_nfe_est`
  - Alternate allele count for samples of Estonian ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_nfe_est`
  - Alternate allele frequency in samples of Estonian ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_nfe_est`
  - Count of homozygous individuals in samples of Estonian ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_topmed_AC_asj_female`
  - Alternate allele count for female samples of Ashkenazi Jewish ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_asj_female`
  - Alternate allele frequency in female samples of Ashkenazi Jewish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_asj_female`
  - Count of homozygous individuals in female samples of Ashkenazi Jewish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_cancer_AC_nfe_swe`
  - Alternate allele count for samples of Swedish ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_nfe_swe`
  - Alternate allele frequency in samples of Swedish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_nfe_swe`
  - Count of homozygous individuals in samples of Swedish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_AC`
  - Alternate allele count for samples in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF`
  - Alternate allele frequency in samples in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt`
  - Count of homozygous individuals in samples in the non_cancer subset
* [INTEGER]   `alternate_bases.non_topmed_AC_oth`
  - Alternate allele count for samples of Other ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_oth`
  - Alternate allele frequency in samples of Other ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_oth`
  - Count of homozygous individuals in samples of Other ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_AC_fin_female`
  - Alternate allele count for female samples of Finnish ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_fin_female`
  - Alternate allele frequency in female samples of Finnish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_fin_female`
  - Count of homozygous individuals in female samples of Finnish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_cancer_AC_fin_female`
  - Alternate allele count for female samples of Finnish ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_fin_female`
  - Alternate allele frequency in female samples of Finnish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_fin_female`
  - Count of homozygous individuals in female samples of Finnish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.AC_oth`
  - Alternate allele count for samples of Other ancestry
* [FLOAT]     `alternate_bases.AF_oth`
  - Alternate allele frequency in samples of Other ancestry
* [INTEGER]   `alternate_bases.nhomalt_oth`
  - Count of homozygous individuals in samples of Other ancestry
* [INTEGER]   `alternate_bases.non_neuro_AC_nfe_male`
  - Alternate allele count for male samples of Non-Finnish European ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_nfe_male`
  - Alternate allele frequency in male samples of Non-Finnish European ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_nfe_male`
  - Count of homozygous individuals in male samples of Non-Finnish European ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.controls_AC_female`
  - Alternate allele count for female samples in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_female`
  - Alternate allele frequency in female samples in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_female`
  - Count of homozygous individuals in female samples in the controls subset
* [INTEGER]   `alternate_bases.non_cancer_AC_fin`
  - Alternate allele count for samples of Finnish ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_fin`
  - Alternate allele frequency in samples of Finnish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_fin`
  - Count of homozygous individuals in samples of Finnish ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_topmed_AC_fin`
  - Alternate allele count for samples of Finnish ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_fin`
  - Alternate allele frequency in samples of Finnish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_fin`
  - Count of homozygous individuals in samples of Finnish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_cancer_AC_eas_oea`
  - Alternate allele count for samples of Other East Asian ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_eas_oea`
  - Alternate allele frequency in samples of Other East Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_eas_oea`
  - Count of homozygous individuals in samples of Other East Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_topmed_AC_nfe_female`
  - Alternate allele count for female samples of Non-Finnish European ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_nfe_female`
  - Alternate allele frequency in female samples of Non-Finnish European ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_nfe_female`
  - Count of homozygous individuals in female samples of Non-Finnish European ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_cancer_AC_sas_male`
  - Alternate allele count for male samples of South Asian ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_sas_male`
  - Alternate allele frequency in male samples of South Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_sas_male`
  - Count of homozygous individuals in male samples of South Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.controls_AC_asj_male`
  - Alternate allele count for male samples of Ashkenazi Jewish ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_asj_male`
  - Alternate allele frequency in male samples of Ashkenazi Jewish ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_asj_male`
  - Count of homozygous individuals in male samples of Ashkenazi Jewish ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_cancer_AC_raw`
  - Alternate allele count for samples in the non_cancer subset, before removing low-confidence genotypes
* [FLOAT]     `alternate_bases.non_cancer_AF_raw`
  - Alternate allele frequency in samples in the non_cancer subset, before removing low-confidence genotypes
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_raw`
  - Count of homozygous individuals in samples in the non_cancer subset, before removing low-confidence genotypes
* [INTEGER]   `alternate_bases.non_cancer_AC_eas_male`
  - Alternate allele count for male samples of East Asian ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_eas_male`
  - Alternate allele frequency in male samples of East Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_eas_male`
  - Count of homozygous individuals in male samples of East Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_topmed_AC_asj_male`
  - Alternate allele count for male samples of Ashkenazi Jewish ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_asj_male`
  - Alternate allele frequency in male samples of Ashkenazi Jewish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_asj_male`
  - Count of homozygous individuals in male samples of Ashkenazi Jewish ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_neuro_AC_oth`
  - Alternate allele count for samples of Other ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_oth`
  - Alternate allele frequency in samples of Other ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_oth`
  - Count of homozygous individuals in samples of Other ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.AC_male`
  - Alternate allele count for male samples
* [FLOAT]     `alternate_bases.AF_male`
  - Alternate allele frequency in male samples
* [INTEGER]   `alternate_bases.nhomalt_male`
  - Count of homozygous individuals in male samples
* [INTEGER]   `alternate_bases.controls_AC_fin_female`
  - Alternate allele count for female samples of Finnish ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_fin_female`
  - Alternate allele frequency in female samples of Finnish ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_fin_female`
  - Count of homozygous individuals in female samples of Finnish ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_AC_nfe_bgr`
  - Alternate allele count for samples of Bulgarian (Eastern European) ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_nfe_bgr`
  - Alternate allele frequency in samples of Bulgarian (Eastern European) ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_nfe_bgr`
  - Count of homozygous individuals in samples of Bulgarian (Eastern European) ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_AC_asj_female`
  - Alternate allele count for female samples of Ashkenazi Jewish ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_asj_female`
  - Alternate allele frequency in female samples of Ashkenazi Jewish ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_asj_female`
  - Count of homozygous individuals in female samples of Ashkenazi Jewish ancestry in the controls subset
* [INTEGER]   `alternate_bases.AC_amr_male`
  - Alternate allele count for male samples of Latino ancestry
* [FLOAT]     `alternate_bases.AF_amr_male`
  - Alternate allele frequency in male samples of Latino ancestry
* [INTEGER]   `alternate_bases.nhomalt_amr_male`
  - Count of homozygous individuals in male samples of Latino ancestry
* [INTEGER]   `alternate_bases.AC_amr_female`
  - Alternate allele count for female samples of Latino ancestry
* [FLOAT]     `alternate_bases.AF_amr_female`
  - Alternate allele frequency in female samples of Latino ancestry
* [INTEGER]   `alternate_bases.nhomalt_amr_female`
  - Count of homozygous individuals in female samples of Latino ancestry
* [INTEGER]   `alternate_bases.non_topmed_AC_sas_male`
  - Alternate allele count for male samples of South Asian ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_sas_male`
  - Alternate allele frequency in male samples of South Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_sas_male`
  - Count of homozygous individuals in male samples of South Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.AC_oth_male`
  - Alternate allele count for male samples of Other ancestry
* [FLOAT]     `alternate_bases.AF_oth_male`
  - Alternate allele frequency in male samples of Other ancestry
* [INTEGER]   `alternate_bases.nhomalt_oth_male`
  - Count of homozygous individuals in male samples of Other ancestry
* [INTEGER]   `alternate_bases.non_cancer_AC_sas`
  - Alternate allele count for samples of South Asian ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_sas`
  - Alternate allele frequency in samples of South Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_sas`
  - Count of homozygous individuals in samples of South Asian ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_neuro_AC_nfe_seu`
  - Alternate allele count for samples of Southern European ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_nfe_seu`
  - Alternate allele frequency in samples of Southern European ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_nfe_seu`
  - Count of homozygous individuals in samples of Southern European ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_cancer_AC_eas_kor`
  - Alternate allele count for samples of Korean ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_eas_kor`
  - Alternate allele frequency in samples of Korean ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_eas_kor`
  - Count of homozygous individuals in samples of Korean ancestry in the non_cancer subset
* [INTEGER]   `alternate_bases.non_topmed_AC_afr_female`
  - Alternate allele count for female samples of African-American/African ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_afr_female`
  - Alternate allele frequency in female samples of African-American/African ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_afr_female`
  - Count of homozygous individuals in female samples of African-American/African ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.controls_AC_sas_male`
  - Alternate allele count for male samples of South Asian ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_sas_male`
  - Alternate allele frequency in male samples of South Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_sas_male`
  - Count of homozygous individuals in male samples of South Asian ancestry in the controls subset
* [INTEGER]   `alternate_bases.non_topmed_AC_sas_female`
  - Alternate allele count for female samples of South Asian ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_sas_female`
  - Alternate allele frequency in female samples of South Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_sas_female`
  - Count of homozygous individuals in female samples of South Asian ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_AC_afr`
  - Alternate allele count for samples of African-American/African ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_afr`
  - Alternate allele frequency in samples of African-American/African ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_afr`
  - Count of homozygous individuals in samples of African-American/African ancestry in the non_topmed subset
* [INTEGER]   `alternate_bases.controls_AC`
  - Alternate allele count for samples in the controls subset
* [FLOAT]     `alternate_bases.controls_AF`
  - Alternate allele frequency in samples in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt`
  - Count of homozygous individuals in samples in the controls subset
* [INTEGER]   `alternate_bases.non_neuro_AC_oth_female`
  - Alternate allele count for female samples of Other ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_oth_female`
  - Alternate allele frequency in female samples of Other ancestry in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_oth_female`
  - Count of homozygous individuals in female samples of Other ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_topmed_faf95_amr`
  - Filtering allele frequency (using Poisson 95% CI) for samples of Latino ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_faf99_amr`
  - Filtering allele frequency (using Poisson 99% CI) for samples of Latino ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.faf95_afr`
  - Filtering allele frequency (using Poisson 95% CI) for samples of African-American/African ancestry
* [FLOAT]     `alternate_bases.faf99_afr`
  - Filtering allele frequency (using Poisson 99% CI) for samples of African-American/African ancestry
* [FLOAT]     `alternate_bases.faf95_sas`
  - Filtering allele frequency (using Poisson 95% CI) for samples of South Asian ancestry
* [FLOAT]     `alternate_bases.faf99_sas`
  - Filtering allele frequency (using Poisson 99% CI) for samples of South Asian ancestry
* [FLOAT]     `alternate_bases.controls_faf95_afr`
  - Filtering allele frequency (using Poisson 95% CI) for samples of African-American/African ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_faf99_afr`
  - Filtering allele frequency (using Poisson 99% CI) for samples of African-American/African ancestry in the controls subset
* [FLOAT]     `alternate_bases.faf95_amr`
  - Filtering allele frequency (using Poisson 95% CI) for samples of Latino ancestry
* [FLOAT]     `alternate_bases.faf99_amr`
  - Filtering allele frequency (using Poisson 99% CI) for samples of Latino ancestry
* [FLOAT]     `alternate_bases.non_neuro_faf95_sas`
  - Filtering allele frequency (using Poisson 95% CI) for samples of South Asian ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_faf99_sas`
  - Filtering allele frequency (using Poisson 99% CI) for samples of South Asian ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.faf95_eas`
  - Filtering allele frequency (using Poisson 95% CI) for samples of East Asian ancestry
* [FLOAT]     `alternate_bases.faf99_eas`
  - Filtering allele frequency (using Poisson 99% CI) for samples of East Asian ancestry
* [FLOAT]     `alternate_bases.faf95`
  - Filtering allele frequency (using Poisson 95% CI) for samples
* [FLOAT]     `alternate_bases.faf99`
  - Filtering allele frequency (using Poisson 99% CI) for samples
* [FLOAT]     `alternate_bases.non_neuro_faf95_afr`
  - Filtering allele frequency (using Poisson 95% CI) for samples of African-American/African ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_faf99_afr`
  - Filtering allele frequency (using Poisson 99% CI) for samples of African-American/African ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_cancer_faf95_eas`
  - Filtering allele frequency (using Poisson 95% CI) for samples of East Asian ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_faf99_eas`
  - Filtering allele frequency (using Poisson 99% CI) for samples of East Asian ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_neuro_faf95_amr`
  - Filtering allele frequency (using Poisson 95% CI) for samples of Latino ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_faf99_amr`
  - Filtering allele frequency (using Poisson 99% CI) for samples of Latino ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_topmed_faf95_sas`
  - Filtering allele frequency (using Poisson 95% CI) for samples of South Asian ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_faf99_sas`
  - Filtering allele frequency (using Poisson 99% CI) for samples of South Asian ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.controls_faf95_nfe`
  - Filtering allele frequency (using Poisson 95% CI) for samples of Non-Finnish European ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_faf99_nfe`
  - Filtering allele frequency (using Poisson 99% CI) for samples of Non-Finnish European ancestry in the controls subset
* [FLOAT]     `alternate_bases.non_cancer_faf95_afr`
  - Filtering allele frequency (using Poisson 95% CI) for samples of African-American/African ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_faf99_afr`
  - Filtering allele frequency (using Poisson 99% CI) for samples of African-American/African ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_faf95_amr`
  - Filtering allele frequency (using Poisson 95% CI) for samples of Latino ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_faf99_amr`
  - Filtering allele frequency (using Poisson 99% CI) for samples of Latino ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_topmed_faf95`
  - Filtering allele frequency (using Poisson 95% CI) for samples in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_faf99`
  - Filtering allele frequency (using Poisson 99% CI) for samples in the non_topmed subset
* [FLOAT]     `alternate_bases.non_neuro_faf95_nfe`
  - Filtering allele frequency (using Poisson 95% CI) for samples of Non-Finnish European ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_faf99_nfe`
  - Filtering allele frequency (using Poisson 99% CI) for samples of Non-Finnish European ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_faf95`
  - Filtering allele frequency (using Poisson 95% CI) for samples in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_faf99`
  - Filtering allele frequency (using Poisson 99% CI) for samples in the non_neuro subset
* [FLOAT]     `alternate_bases.non_topmed_faf95_nfe`
  - Filtering allele frequency (using Poisson 95% CI) for samples of Non-Finnish European ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_faf99_nfe`
  - Filtering allele frequency (using Poisson 99% CI) for samples of Non-Finnish European ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.controls_faf95_eas`
  - Filtering allele frequency (using Poisson 95% CI) for samples of East Asian ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_faf99_eas`
  - Filtering allele frequency (using Poisson 99% CI) for samples of East Asian ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_faf95_sas`
  - Filtering allele frequency (using Poisson 95% CI) for samples of South Asian ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_faf99_sas`
  - Filtering allele frequency (using Poisson 99% CI) for samples of South Asian ancestry in the controls subset
* [FLOAT]     `alternate_bases.faf95_nfe`
  - Filtering allele frequency (using Poisson 95% CI) for samples of Non-Finnish European ancestry
* [FLOAT]     `alternate_bases.faf99_nfe`
  - Filtering allele frequency (using Poisson 99% CI) for samples of Non-Finnish European ancestry
* [FLOAT]     `alternate_bases.non_topmed_faf95_eas`
  - Filtering allele frequency (using Poisson 95% CI) for samples of East Asian ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_faf99_eas`
  - Filtering allele frequency (using Poisson 99% CI) for samples of East Asian ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.controls_faf95_amr`
  - Filtering allele frequency (using Poisson 95% CI) for samples of Latino ancestry in the controls subset
* [FLOAT]     `alternate_bases.controls_faf99_amr`
  - Filtering allele frequency (using Poisson 99% CI) for samples of Latino ancestry in the controls subset
* [FLOAT]     `alternate_bases.non_neuro_faf95_eas`
  - Filtering allele frequency (using Poisson 95% CI) for samples of East Asian ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_faf99_eas`
  - Filtering allele frequency (using Poisson 99% CI) for samples of East Asian ancestry in the non_neuro subset
* [FLOAT]     `alternate_bases.non_cancer_faf95_nfe`
  - Filtering allele frequency (using Poisson 95% CI) for samples of Non-Finnish European ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_faf99_nfe`
  - Filtering allele frequency (using Poisson 99% CI) for samples of Non-Finnish European ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_faf95`
  - Filtering allele frequency (using Poisson 95% CI) for samples in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_faf99`
  - Filtering allele frequency (using Poisson 99% CI) for samples in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_faf95_sas`
  - Filtering allele frequency (using Poisson 95% CI) for samples of South Asian ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_faf99_sas`
  - Filtering allele frequency (using Poisson 99% CI) for samples of South Asian ancestry in the non_cancer subset
* [FLOAT]     `alternate_bases.non_topmed_faf95_afr`
  - Filtering allele frequency (using Poisson 95% CI) for samples of African-American/African ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_faf99_afr`
  - Filtering allele frequency (using Poisson 99% CI) for samples of African-American/African ancestry in the non_topmed subset
* [FLOAT]     `alternate_bases.controls_faf95`
  - Filtering allele frequency (using Poisson 95% CI) for samples in the controls subset
* [FLOAT]     `alternate_bases.controls_faf99`
  - Filtering allele frequency (using Poisson 99% CI) for samples in the controls subset
* [STRING]    `alternate_bases.popmax`
  - Population with maximum AF
* [INTEGER]   `alternate_bases.AC_popmax`
  - Allele count in the population with the maximum AF
* [INTEGER]   `alternate_bases.AN_popmax`
  - Total number of alleles in the population with the maximum AF
* [FLOAT]     `alternate_bases.AF_popmax`
  - Maximum allele frequency across populations (excluding samples of Ashkenazi, Finnish, and indeterminate ancestry)
* [INTEGER]   `alternate_bases.nhomalt_popmax`
  - Count of homozygous individuals in the population with the maximum allele frequency
* [STRING]    `alternate_bases.age_hist_het_bin_freq`
  - Histogram of ages of heterozygous individuals; bin edges are: 30.0|35.0|40.0|45.0|50.0|55.0|60.0|65.0|70.0|75.0|80.0; total number of individuals of any genotype bin: 2547|3423|4546|8487|10355|12693|11933|10534|8882|5991|4136|1935
* [INTEGER]   `alternate_bases.age_hist_het_n_smaller`
  - Count of age values falling below lowest histogram bin edge for heterozygous individuals
* [INTEGER]   `alternate_bases.age_hist_het_n_larger`
  - Count of age values falling above highest histogram bin edge for heterozygous individuals
* [STRING]    `alternate_bases.age_hist_hom_bin_freq`
  - Histogram of ages of homozygous alternate individuals; bin edges are: 30.0|35.0|40.0|45.0|50.0|55.0|60.0|65.0|70.0|75.0|80.0; total number of individuals of any genotype bin: 2547|3423|4546|8487|10355|12693|11933|10534|8882|5991|4136|1935
* [INTEGER]   `alternate_bases.age_hist_hom_n_smaller`
  - Count of age values falling below lowest histogram bin edge for homozygous alternate individuals
* [INTEGER]   `alternate_bases.age_hist_hom_n_larger`
  - Count of age values falling above highest histogram bin edge for homozygous alternate individuals
* [STRING]    `alternate_bases.non_topmed_popmax`
  - Population with maximum AF in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_AC_popmax`
  - Allele count in the population with the maximum AF in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_AN_popmax`
  - Total number of alleles in the population with the maximum AF in the non_topmed subset
* [FLOAT]     `alternate_bases.non_topmed_AF_popmax`
  - Maximum allele frequency across populations (excluding samples of Ashkenazi, Finnish, and indeterminate ancestry) in the non_topmed subset
* [INTEGER]   `alternate_bases.non_topmed_nhomalt_popmax`
  - Count of homozygous individuals in the population with the maximum allele frequency in the non_topmed subset
* [STRING]    `alternate_bases.non_neuro_popmax`
  - Population with maximum AF in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_AC_popmax`
  - Allele count in the population with the maximum AF in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_AN_popmax`
  - Total number of alleles in the population with the maximum AF in the non_neuro subset
* [FLOAT]     `alternate_bases.non_neuro_AF_popmax`
  - Maximum allele frequency across populations (excluding samples of Ashkenazi, Finnish, and indeterminate ancestry) in the non_neuro subset
* [INTEGER]   `alternate_bases.non_neuro_nhomalt_popmax`
  - Count of homozygous individuals in the population with the maximum allele frequency in the non_neuro subset
* [STRING]    `alternate_bases.non_cancer_popmax`
  - Population with maximum AF in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_AC_popmax`
  - Allele count in the population with the maximum AF in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_AN_popmax`
  - Total number of alleles in the population with the maximum AF in the non_cancer subset
* [FLOAT]     `alternate_bases.non_cancer_AF_popmax`
  - Maximum allele frequency across populations (excluding samples of Ashkenazi, Finnish, and indeterminate ancestry) in the non_cancer subset
* [INTEGER]   `alternate_bases.non_cancer_nhomalt_popmax`
  - Count of homozygous individuals in the population with the maximum allele frequency in the non_cancer subset
* [STRING]    `alternate_bases.controls_popmax`
  - Population with maximum AF in the controls subset
* [INTEGER]   `alternate_bases.controls_AC_popmax`
  - Allele count in the population with the maximum AF in the controls subset
* [INTEGER]   `alternate_bases.controls_AN_popmax`
  - Total number of alleles in the population with the maximum AF in the controls subset
* [FLOAT]     `alternate_bases.controls_AF_popmax`
  - Maximum allele frequency across populations (excluding samples of Ashkenazi, Finnish, and indeterminate ancestry) in the controls subset
* [INTEGER]   `alternate_bases.controls_nhomalt_popmax`
  - Count of homozygous individuals in the population with the maximum allele frequency in the controls subset
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
* [STRING]    `alternate_bases.vep.HGVSc`
  - The HGVS coding sequence name
* [STRING]    `alternate_bases.vep.HGVSp`
  - The HGVS protein sequence name
* [STRING]    `alternate_bases.vep.cDNA_position`
  - Relative position of base pair in cDNA sequence
* [STRING]    `alternate_bases.vep.CDS_position`
  - Relative position of base pair in coding sequence
* [STRING]    `alternate_bases.vep.Protein_position`
  - Relative position of amino acid in protein
* [STRING]    `alternate_bases.vep.Amino_acids`
  - Reference and variant amino acids. Only given if the variant affects the protein-coding sequence
* [STRING]    `alternate_bases.vep.Codons`
  - The alternative codons with the variant base in upper case
* [STRING]    `alternate_bases.vep.Existing_variation`
  - Known identifier of existing variant
* [INTEGER]   `alternate_bases.vep.ALLELE_NUM`
  - Allele number from input; 0 is reference, 1 is first alternate etc
* [INTEGER]   `alternate_bases.vep.DISTANCE`
  - Shortest distance from variant to transcript
* [INTEGER]   `alternate_bases.vep.STRAND`
  - The DNA strand (1 or -1) on which the transcript/feature lies
* [STRING]    `alternate_bases.vep.FLAGS`
  - Transcript quality flags (cds_start_NF, cds_start_NF)
* [STRING]    `alternate_bases.vep.VARIANT_CLASS`
  - Sequence Ontology variant class
* [INTEGER]   `alternate_bases.vep.MINIMISED`
  - Alleles in this variant have been converted to minimal representation before consequence calculation
* [STRING]    `alternate_bases.vep.SYMBOL_SOURCE`
  - The source of the gene symbol
* [INTEGER]   `alternate_bases.vep.HGNC_ID`
  - HUGO Gene Nomenclature Committee approved symbol
* [STRING]    `alternate_bases.vep.CANONICAL`
  - A flag indicating if the transcript is denoted as the canonical transcript for this gene
* [STRING]    `alternate_bases.vep.TSL`
  - Transcript support level. NB: not available for GRCh37
* [STRING]    `alternate_bases.vep.APPRIS`
  - Annotates alternatively spliced transcripts as primary or alternate based on a range of computational methods. NB: not available for GRCh37
* [STRING]    `alternate_bases.vep.CCDS`
  - The CCDS identifer for this transcript, where applicable
* [STRING]    `alternate_bases.vep.ENSP`
  - The Ensembl protein identifier of the affected transcript
* [STRING]    `alternate_bases.vep.SWISSPROT`
  - Best match UniProtKB/Swiss-Prot accession of protein product
* [STRING]    `alternate_bases.vep.TREMBL`
  - Best match UniProtKB/TrEMBL accession of protein product
* [STRING]    `alternate_bases.vep.UNIPARC`
  - Best match UniParc accession of protein product
* [INTEGER]   `alternate_bases.vep.GENE_PHENO`
  - Indicates if overlapped gene is associated with a phenotype, disease or trait
* [STRING]    `alternate_bases.vep.SIFT`
  - The SIFT prediction and/or score, with both given as prediction(score)
* [STRING]    `alternate_bases.vep.PolyPhen`
  - The PolyPhen prediction and/or score
* [STRING]    `alternate_bases.vep.DOMAINS`
  - The source and identifer of any overlapping protein domains
* [INTEGER]   `alternate_bases.vep.HGVS_OFFSET`
  - Indicates by how many bases the HGVS notations for this variant have been shifted
* [STRING]    `alternate_bases.vep.GMAF`
* [STRING]    `alternate_bases.vep.AFR_MAF`
* [STRING]    `alternate_bases.vep.AMR_MAF`
* [STRING]    `alternate_bases.vep.EAS_MAF`
* [STRING]    `alternate_bases.vep.EUR_MAF`
* [STRING]    `alternate_bases.vep.SAS_MAF`
* [STRING]    `alternate_bases.vep.AA_MAF`
* [STRING]    `alternate_bases.vep.EA_MAF`
* [STRING]    `alternate_bases.vep.ExAC_MAF`
* [STRING]    `alternate_bases.vep.ExAC_Adj_MAF`
* [STRING]    `alternate_bases.vep.ExAC_AFR_MAF`
* [STRING]    `alternate_bases.vep.ExAC_AMR_MAF`
* [STRING]    `alternate_bases.vep.ExAC_EAS_MAF`
* [STRING]    `alternate_bases.vep.ExAC_FIN_MAF`
* [STRING]    `alternate_bases.vep.ExAC_NFE_MAF`
* [STRING]    `alternate_bases.vep.ExAC_OTH_MAF`
* [STRING]    `alternate_bases.vep.ExAC_SAS_MAF`
* [STRING]    `alternate_bases.vep.CLIN_SIG`
  - ClinVar clinical significance of the dbSNP variant
* [STRING]    `alternate_bases.vep.SOMATIC`
  - Somatic status of existing variant(s); multiple values correspond to multiple values in the Existing_variation field
* [STRING]    `alternate_bases.vep.PHENO`
  - Indicates if existing variant is associated with a phenotype, disease or trait; multiple values correspond to multiple values in the Existing_variation field
* [STRING]    `alternate_bases.vep.PUBMED`
  - Pubmed ID(s) of publications that cite existing variant
* [STRING]    `alternate_bases.vep.MOTIF_NAME`
  - The source and identifier of a transcription factor binding profile aligned at this position
* [INTEGER]   `alternate_bases.vep.MOTIF_POS`
  - The relative position of the variation in the aligned TFBP
* [STRING]    `alternate_bases.vep.HIGH_INF_POS`
  - A flag indicating if the variant falls in a high information position of a transcription factor binding profile (TFBP)
* [FLOAT]     `alternate_bases.vep.MOTIF_SCORE_CHANGE`
  - The difference in motif score of the reference and variant sequences for the TFBP
* [STRING]    `alternate_bases.vep.LoF`
* [STRING]    `alternate_bases.vep.LoF_filter`
* [STRING]    `alternate_bases.vep.LoF_flags`
* [STRING]    `alternate_bases.vep.LoF_info`
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
* [FLOAT]     `rf_tp_probability`
  - Random forest prediction probability for a site being a true variant
* [FLOAT]     `FS`
  - Phred-scaled p-value of Fisher's exact test for strand bias
* [FLOAT]     `InbreedingCoeff`
  - Inbreeding coefficient as estimated from the genotype likelihoods per-sample when compared against the Hardy-Weinberg expectation
* [FLOAT]     `MQ`
  - Root mean square of the mapping quality of reads across all samples
* [FLOAT]     `MQRankSum`
  - Z-score from Wilcoxon rank sum test of alternate vs. reference read mapping qualities
* [FLOAT]     `QD`
  - Variant call confidence normalized by depth of sample reads supporting a variant
* [FLOAT]     `ReadPosRankSum`
  - Z-score from Wilcoxon rank sum test of alternate vs. reference read position bias
* [FLOAT]     `SOR`
  - Strand bias estimated by the symmetric odds ratio test
* [BOOLEAN]   `VQSR_POSITIVE_TRAIN_SITE`
  - Variant was used to build the positive training set of high-quality variants for VQSR
* [BOOLEAN]   `VQSR_NEGATIVE_TRAIN_SITE`
  - Variant was used to build the negative training set of low-quality variants for VQSR
* [FLOAT]     `BaseQRankSum`
  - Z-score from Wilcoxon rank sum test of alternate vs. reference base qualities
* [FLOAT]     `ClippingRankSum`
  - Z-score from Wilcoxon rank sum test of alternate vs. reference number of hard clipped bases
* [INTEGER]   `DP`
  - Depth of informative coverage for each sample; reads with MQ=255 or with bad mates are filtered
* [FLOAT]     `VQSLOD`
  - Log-odds ratio of being a true variant versus being a false positive under the trained VQSR Gaussian mixture model
* [STRING]    `VQSR_culprit`
  - Worst-performing annotation in the VQSR Gaussian mixture model
* [BOOLEAN]   `segdup`
  - Variant falls within a segmental duplication region
* [BOOLEAN]   `lcr`
  - Variant falls within a low complexity region
* [BOOLEAN]   `decoy`
  - Variant falls within a reference decoy region
* [BOOLEAN]   `nonpar`
  - Variant (on sex chromosome) falls outside a pseudoautosomal region
* [BOOLEAN]   `rf_positive_label`
  - Variant was labelled as a positive example for training of random forest model
* [BOOLEAN]   `rf_negative_label`
  - Variant was labelled as a negative example for training of random forest model
* [STRING]    `rf_label`
  - Random forest training label
* [BOOLEAN]   `rf_train`
  - Variant was used in training random forest model
* [BOOLEAN]   `transmitted_singleton`
  - Variant was a callset-wide doubleton that was transmitted within a family (i.e., a singleton amongst unrelated sampes in cohort)
* [STRING]    `variant_type`
  - Variant type (snv, indel, multi-snv, multi-indel, or mixed)
* [BOOLEAN]   `was_mixed`
  - Variant type was mixed
* [BOOLEAN]   `has_star`
  - Variant locus coincides with a spanning deletion (represented by a star) observed elsewhere in the callset
* [INTEGER]   `AN_nfe_seu`
  - Total number of alleles in samples of Southern European ancestry
* [INTEGER]   `controls_AN_afr_male`
  - Total number of alleles in male samples of African-American/African ancestry in the controls subset
* [INTEGER]   `non_neuro_AN_eas_kor`
  - Total number of alleles in samples of Korean ancestry in the non_neuro subset
* [INTEGER]   `non_topmed_AN_amr`
  - Total number of alleles in samples of Latino ancestry in the non_topmed subset
* [INTEGER]   `non_cancer_AN_asj_female`
  - Total number of alleles in female samples of Ashkenazi Jewish ancestry in the non_cancer subset
* [INTEGER]   `AN_raw`
  - Total number of alleles in samples, before removing low-confidence genotypes
* [INTEGER]   `AN_fin_female`
  - Total number of alleles in female samples of Finnish ancestry
* [INTEGER]   `non_cancer_AN_oth_female`
  - Total number of alleles in female samples of Other ancestry in the non_cancer subset
* [INTEGER]   `AN_nfe_bgr`
  - Total number of alleles in samples of Bulgarian (Eastern European) ancestry
* [INTEGER]   `non_neuro_AN_asj_female`
  - Total number of alleles in female samples of Ashkenazi Jewish ancestry in the non_neuro subset
* [INTEGER]   `AN_sas_male`
  - Total number of alleles in male samples of South Asian ancestry
* [INTEGER]   `non_neuro_AN_afr_male`
  - Total number of alleles in male samples of African-American/African ancestry in the non_neuro subset
* [INTEGER]   `AN_afr_male`
  - Total number of alleles in male samples of African-American/African ancestry
* [INTEGER]   `AN_afr`
  - Total number of alleles in samples of African-American/African ancestry
* [INTEGER]   `controls_AN_nfe_swe`
  - Total number of alleles in samples of Swedish ancestry in the controls subset
* [INTEGER]   `non_neuro_AN_afr_female`
  - Total number of alleles in female samples of African-American/African ancestry in the non_neuro subset
* [INTEGER]   `non_topmed_AN_amr_female`
  - Total number of alleles in female samples of Latino ancestry in the non_topmed subset
* [INTEGER]   `non_cancer_AN_female`
  - Total number of alleles in female samples in the non_cancer subset
* [INTEGER]   `non_cancer_AN_nfe_onf`
  - Total number of alleles in samples of Other Non-Finnish European ancestry in the non_cancer subset
* [INTEGER]   `non_cancer_AN_male`
  - Total number of alleles in male samples in the non_cancer subset
* [INTEGER]   `non_topmed_AN_oth_female`
  - Total number of alleles in female samples of Other ancestry in the non_topmed subset
* [INTEGER]   `AN_eas_female`
  - Total number of alleles in female samples of East Asian ancestry
* [INTEGER]   `non_cancer_AN_sas_female`
  - Total number of alleles in female samples of South Asian ancestry in the non_cancer subset
* [INTEGER]   `AN_afr_female`
  - Total number of alleles in female samples of African-American/African ancestry
* [INTEGER]   `AN_sas`
  - Total number of alleles in samples of South Asian ancestry
* [INTEGER]   `non_neuro_AN_female`
  - Total number of alleles in female samples in the non_neuro subset
* [INTEGER]   `controls_AN_afr`
  - Total number of alleles in samples of African-American/African ancestry in the controls subset
* [INTEGER]   `non_neuro_AN_eas_jpn`
  - Total number of alleles in samples of Japanese ancestry in the non_neuro subset
* [INTEGER]   `AN_nfe_onf`
  - Total number of alleles in samples of Other Non-Finnish European ancestry
* [INTEGER]   `non_cancer_AN_amr_male`
  - Total number of alleles in male samples of Latino ancestry in the non_cancer subset
* [INTEGER]   `controls_AN_fin_male`
  - Total number of alleles in male samples of Finnish ancestry in the controls subset
* [INTEGER]   `non_neuro_AN_nfe_nwe`
  - Total number of alleles in samples of North-Western European ancestry in the non_neuro subset
* [INTEGER]   `AN_fin_male`
  - Total number of alleles in male samples of Finnish ancestry
* [INTEGER]   `AN_nfe_female`
  - Total number of alleles in female samples of Non-Finnish European ancestry
* [INTEGER]   `AN_amr`
  - Total number of alleles in samples of Latino ancestry
* [INTEGER]   `non_topmed_AN_nfe_male`
  - Total number of alleles in male samples of Non-Finnish European ancestry in the non_topmed subset
* [INTEGER]   `non_neuro_AN_sas`
  - Total number of alleles in samples of South Asian ancestry in the non_neuro subset
* [INTEGER]   `non_cancer_AN_fin_male`
  - Total number of alleles in male samples of Finnish ancestry in the non_cancer subset
* [INTEGER]   `non_cancer_AN_nfe_seu`
  - Total number of alleles in samples of Southern European ancestry in the non_cancer subset
* [INTEGER]   `AN_eas`
  - Total number of alleles in samples of East Asian ancestry
* [INTEGER]   `non_neuro_AN_nfe_female`
  - Total number of alleles in female samples of Non-Finnish European ancestry in the non_neuro subset
* [INTEGER]   `non_neuro_AN_afr`
  - Total number of alleles in samples of African-American/African ancestry in the non_neuro subset
* [INTEGER]   `controls_AN_raw`
  - Total number of alleles in samples in the controls subset, before removing low-confidence genotypes
* [INTEGER]   `non_cancer_AN_eas`
  - Total number of alleles in samples of East Asian ancestry in the non_cancer subset
* [INTEGER]   `non_cancer_AN_amr_female`
  - Total number of alleles in female samples of Latino ancestry in the non_cancer subset
* [INTEGER]   `non_neuro_AN_nfe_swe`
  - Total number of alleles in samples of Swedish ancestry in the non_neuro subset
* [INTEGER]   `controls_AN_male`
  - Total number of alleles in male samples in the controls subset
* [INTEGER]   `non_topmed_AN_male`
  - Total number of alleles in male samples in the non_topmed subset
* [INTEGER]   `controls_AN_eas_jpn`
  - Total number of alleles in samples of Japanese ancestry in the controls subset
* [INTEGER]   `controls_AN_nfe_female`
  - Total number of alleles in female samples of Non-Finnish European ancestry in the controls subset
* [INTEGER]   `non_neuro_AN_amr`
  - Total number of alleles in samples of Latino ancestry in the non_neuro subset
* [INTEGER]   `non_neuro_AN_eas_female`
  - Total number of alleles in female samples of East Asian ancestry in the non_neuro subset
* [INTEGER]   `AN_asj_male`
  - Total number of alleles in male samples of Ashkenazi Jewish ancestry
* [INTEGER]   `controls_AN_nfe_male`
  - Total number of alleles in male samples of Non-Finnish European ancestry in the controls subset
* [INTEGER]   `non_neuro_AN_fin`
  - Total number of alleles in samples of Finnish ancestry in the non_neuro subset
* [INTEGER]   `non_topmed_AN_sas`
  - Total number of alleles in samples of South Asian ancestry in the non_topmed subset
* [INTEGER]   `non_cancer_AN_nfe_female`
  - Total number of alleles in female samples of Non-Finnish European ancestry in the non_cancer subset
* [INTEGER]   `AN_oth_female`
  - Total number of alleles in female samples of Other ancestry
* [INTEGER]   `non_cancer_AN_asj`
  - Total number of alleles in samples of Ashkenazi Jewish ancestry in the non_cancer subset
* [INTEGER]   `AN_nfe_swe`
  - Total number of alleles in samples of Swedish ancestry
* [INTEGER]   `controls_AN_nfe`
  - Total number of alleles in samples of Non-Finnish European ancestry in the controls subset
* [INTEGER]   `controls_AN_oth_female`
  - Total number of alleles in female samples of Other ancestry in the controls subset
* [INTEGER]   `controls_AN_asj`
  - Total number of alleles in samples of Ashkenazi Jewish ancestry in the controls subset
* [INTEGER]   `non_neuro_AN_amr_male`
  - Total number of alleles in male samples of Latino ancestry in the non_neuro subset
* [INTEGER]   `controls_AN_nfe_nwe`
  - Total number of alleles in samples of North-Western European ancestry in the controls subset
* [INTEGER]   `AN_nfe_nwe`
  - Total number of alleles in samples of North-Western European ancestry
* [INTEGER]   `controls_AN_nfe_seu`
  - Total number of alleles in samples of Southern European ancestry in the controls subset
* [INTEGER]   `controls_AN_sas_female`
  - Total number of alleles in female samples of South Asian ancestry in the controls subset
* [INTEGER]   `non_neuro_AN_amr_female`
  - Total number of alleles in female samples of Latino ancestry in the non_neuro subset
* [INTEGER]   `non_cancer_AN_eas_jpn`
  - Total number of alleles in samples of Japanese ancestry in the non_cancer subset
* [INTEGER]   `non_neuro_AN_nfe_onf`
  - Total number of alleles in samples of Other Non-Finnish European ancestry in the non_neuro subset
* [INTEGER]   `non_topmed_AN_eas_male`
  - Total number of alleles in male samples of East Asian ancestry in the non_topmed subset
* [INTEGER]   `AN_eas_jpn`
  - Total number of alleles in samples of Japanese ancestry
* [INTEGER]   `non_cancer_AN_afr_male`
  - Total number of alleles in male samples of African-American/African ancestry in the non_cancer subset
* [INTEGER]   `non_cancer_AN_afr`
  - Total number of alleles in samples of African-American/African ancestry in the non_cancer subset
* [INTEGER]   `controls_AN_amr_female`
  - Total number of alleles in female samples of Latino ancestry in the controls subset
* [INTEGER]   `non_neuro_AN_fin_male`
  - Total number of alleles in male samples of Finnish ancestry in the non_neuro subset
* [INTEGER]   `AN_female`
  - Total number of alleles in female samples
* [INTEGER]   `non_neuro_AN_nfe_bgr`
  - Total number of alleles in samples of Bulgarian (Eastern European) ancestry in the non_neuro subset
* [INTEGER]   `non_neuro_AN_oth_male`
  - Total number of alleles in male samples of Other ancestry in the non_neuro subset
* [INTEGER]   `non_topmed_AN_nfe_est`
  - Total number of alleles in samples of Estonian ancestry in the non_topmed subset
* [INTEGER]   `non_topmed_AN_nfe_nwe`
  - Total number of alleles in samples of North-Western European ancestry in the non_topmed subset
* [INTEGER]   `non_topmed_AN_amr_male`
  - Total number of alleles in male samples of Latino ancestry in the non_topmed subset
* [INTEGER]   `non_cancer_AN_amr`
  - Total number of alleles in samples of Latino ancestry in the non_cancer subset
* [INTEGER]   `non_topmed_AN_nfe_swe`
  - Total number of alleles in samples of Swedish ancestry in the non_topmed subset
* [INTEGER]   `non_topmed_AN_nfe_onf`
  - Total number of alleles in samples of Other Non-Finnish European ancestry in the non_topmed subset
* [INTEGER]   `controls_AN_eas_kor`
  - Total number of alleles in samples of Korean ancestry in the controls subset
* [INTEGER]   `non_topmed_AN_eas_oea`
  - Total number of alleles in samples of Other East Asian ancestry in the non_topmed subset
* [INTEGER]   `controls_AN_eas_male`
  - Total number of alleles in male samples of East Asian ancestry in the controls subset
* [INTEGER]   `controls_AN_oth_male`
  - Total number of alleles in male samples of Other ancestry in the controls subset
* [INTEGER]   `non_topmed_AN`
  - Total number of alleles in samples in the non_topmed subset
* [INTEGER]   `controls_AN_fin`
  - Total number of alleles in samples of Finnish ancestry in the controls subset
* [INTEGER]   `AN_eas_kor`
  - Total number of alleles in samples of Korean ancestry
* [INTEGER]   `non_neuro_AN_nfe`
  - Total number of alleles in samples of Non-Finnish European ancestry in the non_neuro subset
* [INTEGER]   `non_neuro_AN_fin_female`
  - Total number of alleles in female samples of Finnish ancestry in the non_neuro subset
* [INTEGER]   `non_cancer_AN_nfe_male`
  - Total number of alleles in male samples of Non-Finnish European ancestry in the non_cancer subset
* [INTEGER]   `controls_AN_eas_oea`
  - Total number of alleles in samples of Other East Asian ancestry in the controls subset
* [INTEGER]   `non_topmed_AN_nfe_seu`
  - Total number of alleles in samples of Southern European ancestry in the non_topmed subset
* [INTEGER]   `controls_AN_eas_female`
  - Total number of alleles in female samples of East Asian ancestry in the controls subset
* [INTEGER]   `non_topmed_AN_asj`
  - Total number of alleles in samples of Ashkenazi Jewish ancestry in the non_topmed subset
* [INTEGER]   `controls_AN_nfe_onf`
  - Total number of alleles in samples of Other Non-Finnish European ancestry in the controls subset
* [INTEGER]   `non_neuro_AN`
  - Total number of alleles in samples in the non_neuro subset
* [INTEGER]   `AN_eas_oea`
  - Total number of alleles in samples of Other East Asian ancestry
* [INTEGER]   `non_topmed_AN_nfe`
  - Total number of alleles in samples of Non-Finnish European ancestry in the non_topmed subset
* [INTEGER]   `non_cancer_AN_oth`
  - Total number of alleles in samples of Other ancestry in the non_cancer subset
* [INTEGER]   `non_topmed_AN_raw`
  - Total number of alleles in samples in the non_topmed subset, before removing low-confidence genotypes
* [INTEGER]   `non_neuro_AN_nfe_est`
  - Total number of alleles in samples of Estonian ancestry in the non_neuro subset
* [INTEGER]   `non_topmed_AN_oth_male`
  - Total number of alleles in male samples of Other ancestry in the non_topmed subset
* [INTEGER]   `non_cancer_AN_oth_male`
  - Total number of alleles in male samples of Other ancestry in the non_cancer subset
* [INTEGER]   `AN_nfe_est`
  - Total number of alleles in samples of Estonian ancestry
* [INTEGER]   `non_cancer_AN_afr_female`
  - Total number of alleles in female samples of African-American/African ancestry in the non_cancer subset
* [INTEGER]   `non_topmed_AN_afr_male`
  - Total number of alleles in male samples of African-American/African ancestry in the non_topmed subset
* [INTEGER]   `AN_eas_male`
  - Total number of alleles in male samples of East Asian ancestry
* [INTEGER]   `controls_AN_eas`
  - Total number of alleles in samples of East Asian ancestry in the controls subset
* [INTEGER]   `non_neuro_AN_eas_male`
  - Total number of alleles in male samples of East Asian ancestry in the non_neuro subset
* [INTEGER]   `non_cancer_AN_nfe_nwe`
  - Total number of alleles in samples of North-Western European ancestry in the non_cancer subset
* [INTEGER]   `controls_AN_sas`
  - Total number of alleles in samples of South Asian ancestry in the controls subset
* [INTEGER]   `non_neuro_AN_sas_male`
  - Total number of alleles in male samples of South Asian ancestry in the non_neuro subset
* [INTEGER]   `non_neuro_AN_asj_male`
  - Total number of alleles in male samples of Ashkenazi Jewish ancestry in the non_neuro subset
* [INTEGER]   `non_cancer_AN_nfe_bgr`
  - Total number of alleles in samples of Bulgarian (Eastern European) ancestry in the non_cancer subset
* [INTEGER]   `controls_AN_oth`
  - Total number of alleles in samples of Other ancestry in the controls subset
* [INTEGER]   `non_cancer_AN_eas_female`
  - Total number of alleles in female samples of East Asian ancestry in the non_cancer subset
* [INTEGER]   `AN_nfe`
  - Total number of alleles in samples of Non-Finnish European ancestry
* [INTEGER]   `non_topmed_AN_female`
  - Total number of alleles in female samples in the non_topmed subset
* [INTEGER]   `non_neuro_AN_asj`
  - Total number of alleles in samples of Ashkenazi Jewish ancestry in the non_neuro subset
* [INTEGER]   `non_topmed_AN_eas_female`
  - Total number of alleles in female samples of East Asian ancestry in the non_topmed subset
* [INTEGER]   `non_neuro_AN_raw`
  - Total number of alleles in samples in the non_neuro subset, before removing low-confidence genotypes
* [INTEGER]   `non_topmed_AN_eas`
  - Total number of alleles in samples of East Asian ancestry in the non_topmed subset
* [INTEGER]   `non_topmed_AN_fin_male`
  - Total number of alleles in male samples of Finnish ancestry in the non_topmed subset
* [INTEGER]   `non_cancer_AN_asj_male`
  - Total number of alleles in male samples of Ashkenazi Jewish ancestry in the non_cancer subset
* [INTEGER]   `AN_fin`
  - Total number of alleles in samples of Finnish ancestry
* [INTEGER]   `AN_nfe_male`
  - Total number of alleles in male samples of Non-Finnish European ancestry
* [INTEGER]   `non_topmed_AN_eas_kor`
  - Total number of alleles in samples of Korean ancestry in the non_topmed subset
* [INTEGER]   `controls_AN_amr_male`
  - Total number of alleles in male samples of Latino ancestry in the controls subset
* [INTEGER]   `non_neuro_AN_eas_oea`
  - Total number of alleles in samples of Other East Asian ancestry in the non_neuro subset
* [INTEGER]   `AN_sas_female`
  - Total number of alleles in female samples of South Asian ancestry
* [INTEGER]   `controls_AN_afr_female`
  - Total number of alleles in female samples of African-American/African ancestry in the controls subset
* [INTEGER]   `controls_AN_amr`
  - Total number of alleles in samples of Latino ancestry in the controls subset
* [INTEGER]   `non_topmed_AN_eas_jpn`
  - Total number of alleles in samples of Japanese ancestry in the non_topmed subset
* [INTEGER]   `AN_asj_female`
  - Total number of alleles in female samples of Ashkenazi Jewish ancestry
* [INTEGER]   `non_topmed_AN_nfe_bgr`
  - Total number of alleles in samples of Bulgarian (Eastern European) ancestry in the non_topmed subset
* [INTEGER]   `non_cancer_AN_nfe_est`
  - Total number of alleles in samples of Estonian ancestry in the non_cancer subset
* [INTEGER]   `non_neuro_AN_eas`
  - Total number of alleles in samples of East Asian ancestry in the non_neuro subset
* [INTEGER]   `non_cancer_AN_nfe`
  - Total number of alleles in samples of Non-Finnish European ancestry in the non_cancer subset
* [INTEGER]   `non_neuro_AN_male`
  - Total number of alleles in male samples in the non_neuro subset
* [INTEGER]   `non_neuro_AN_sas_female`
  - Total number of alleles in female samples of South Asian ancestry in the non_neuro subset
* [INTEGER]   `AN_asj`
  - Total number of alleles in samples of Ashkenazi Jewish ancestry
* [INTEGER]   `controls_AN_nfe_est`
  - Total number of alleles in samples of Estonian ancestry in the controls subset
* [INTEGER]   `non_topmed_AN_asj_female`
  - Total number of alleles in female samples of Ashkenazi Jewish ancestry in the non_topmed subset
* [INTEGER]   `non_cancer_AN_nfe_swe`
  - Total number of alleles in samples of Swedish ancestry in the non_cancer subset
* [INTEGER]   `non_cancer_AN`
  - Total number of alleles in samples in the non_cancer subset
* [INTEGER]   `non_topmed_AN_oth`
  - Total number of alleles in samples of Other ancestry in the non_topmed subset
* [INTEGER]   `non_topmed_AN_fin_female`
  - Total number of alleles in female samples of Finnish ancestry in the non_topmed subset
* [INTEGER]   `non_cancer_AN_fin_female`
  - Total number of alleles in female samples of Finnish ancestry in the non_cancer subset
* [INTEGER]   `AN_oth`
  - Total number of alleles in samples of Other ancestry
* [INTEGER]   `non_neuro_AN_nfe_male`
  - Total number of alleles in male samples of Non-Finnish European ancestry in the non_neuro subset
* [INTEGER]   `controls_AN_female`
  - Total number of alleles in female samples in the controls subset
* [INTEGER]   `non_cancer_AN_fin`
  - Total number of alleles in samples of Finnish ancestry in the non_cancer subset
* [INTEGER]   `non_topmed_AN_fin`
  - Total number of alleles in samples of Finnish ancestry in the non_topmed subset
* [INTEGER]   `non_cancer_AN_eas_oea`
  - Total number of alleles in samples of Other East Asian ancestry in the non_cancer subset
* [INTEGER]   `non_topmed_AN_nfe_female`
  - Total number of alleles in female samples of Non-Finnish European ancestry in the non_topmed subset
* [INTEGER]   `non_cancer_AN_sas_male`
  - Total number of alleles in male samples of South Asian ancestry in the non_cancer subset
* [INTEGER]   `controls_AN_asj_male`
  - Total number of alleles in male samples of Ashkenazi Jewish ancestry in the controls subset
* [INTEGER]   `non_cancer_AN_raw`
  - Total number of alleles in samples in the non_cancer subset, before removing low-confidence genotypes
* [INTEGER]   `non_cancer_AN_eas_male`
  - Total number of alleles in male samples of East Asian ancestry in the non_cancer subset
* [INTEGER]   `non_topmed_AN_asj_male`
  - Total number of alleles in male samples of Ashkenazi Jewish ancestry in the non_topmed subset
* [INTEGER]   `non_neuro_AN_oth`
  - Total number of alleles in samples of Other ancestry in the non_neuro subset
* [INTEGER]   `AN_male`
  - Total number of alleles in male samples
* [INTEGER]   `controls_AN_fin_female`
  - Total number of alleles in female samples of Finnish ancestry in the controls subset
* [INTEGER]   `controls_AN_nfe_bgr`
  - Total number of alleles in samples of Bulgarian (Eastern European) ancestry in the controls subset
* [INTEGER]   `controls_AN_asj_female`
  - Total number of alleles in female samples of Ashkenazi Jewish ancestry in the controls subset
* [INTEGER]   `AN_amr_male`
  - Total number of alleles in male samples of Latino ancestry
* [INTEGER]   `AN_amr_female`
  - Total number of alleles in female samples of Latino ancestry
* [INTEGER]   `non_topmed_AN_sas_male`
  - Total number of alleles in male samples of South Asian ancestry in the non_topmed subset
* [INTEGER]   `AN_oth_male`
  - Total number of alleles in male samples of Other ancestry
* [INTEGER]   `non_cancer_AN_sas`
  - Total number of alleles in samples of South Asian ancestry in the non_cancer subset
* [INTEGER]   `non_neuro_AN_nfe_seu`
  - Total number of alleles in samples of Southern European ancestry in the non_neuro subset
* [INTEGER]   `non_cancer_AN_eas_kor`
  - Total number of alleles in samples of Korean ancestry in the non_cancer subset
* [INTEGER]   `non_topmed_AN_afr_female`
  - Total number of alleles in female samples of African-American/African ancestry in the non_topmed subset
* [INTEGER]   `controls_AN_sas_male`
  - Total number of alleles in male samples of South Asian ancestry in the controls subset
* [INTEGER]   `non_topmed_AN_sas_female`
  - Total number of alleles in female samples of South Asian ancestry in the non_topmed subset
* [INTEGER]   `non_topmed_AN_afr`
  - Total number of alleles in samples of African-American/African ancestry in the non_topmed subset
* [INTEGER]   `controls_AN`
  - Total number of alleles in samples in the controls subset
* [INTEGER]   `non_neuro_AN_oth_female`
  - Total number of alleles in female samples of Other ancestry in the non_neuro subset

-------------------------------------------------------------------------------
*Do not make edits above this line.*
