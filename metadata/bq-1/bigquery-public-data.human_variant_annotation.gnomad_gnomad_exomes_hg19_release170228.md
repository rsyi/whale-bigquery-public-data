# `human_variant_annotation.gnomad_gnomad_exomes_hg19_release170228`
`bq-1` | `bigquery-public-data`
Source: gs://gnomad-public/release-170228/vcf/exomes/gnomad.exomes.r2.0.1.sites.vcf.gz

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
  - RF: Failed random forests filters (SNV cutoff 0.1, indels cutoff 0.2)
AC0: Allele Count is zero (i.e. no high-confidence genotype (GQ >= 20, DP >= 10, AB => 0.2 for het calls))
InbreedingCoeff: InbreedingCoeff < -0.3
LCR: In a low complexity region
SEGDUP: In a segmental duplication region
PASS: All filters passed for at least one of the alleles at that site (see AS_FilterStatus for allele-specific filter status)
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
* [STRING]    `AB_HIST_ALL`
  - Histogram for Allele Balance in heterozygous individuals; 100*AD[i_alt]/sum(AD); Midpoints of histogram bins: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [STRING]    `AB_HIST_ALT`
  - Histogram for Allele Balance in heterozygous individuals for each allele; 100*AD[i_alt]/sum(AD); Midpoints of histogram bins: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [STRING]    `AB_MEDIAN`
  - Median allele balance in heterozygote carriers of each allele
* [INTEGER]   `AC`
  - Allele count in genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_AFR`
  - Allele count in African/African American genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_AFR_Female`
  - Allele count in African/African American Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_AFR_Male`
  - Allele count in African/African American Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_AMR`
  - Allele count in Admixed American genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_AMR_Female`
  - Allele count in Admixed American Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_AMR_Male`
  - Allele count in Admixed American Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_ASJ`
  - Allele count in Ashkenazi Jewish genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_ASJ_Female`
  - Allele count in Ashkenazi Jewish Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_ASJ_Male`
  - Allele count in Ashkenazi Jewish Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_EAS`
  - Allele count in East Asian genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_EAS_Female`
  - Allele count in East Asian Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_EAS_Male`
  - Allele count in East Asian Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_FIN`
  - Allele count in Finnish genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_FIN_Female`
  - Allele count in Finnish Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_FIN_Male`
  - Allele count in Finnish Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_Female`
  - Allele count in Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_Male`
  - Allele count in Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_NFE`
  - Allele count in Non-Finnish European genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_NFE_Female`
  - Allele count in Non-Finnish European Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_NFE_Male`
  - Allele count in Non-Finnish European Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_OTH`
  - Allele count in Other (population not assigned) genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_OTH_Female`
  - Allele count in Other (population not assigned) Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_OTH_Male`
  - Allele count in Other (population not assigned) Male genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AC_POPMAX`
  - AC in the population with the max AF
* [INTEGER]   `AC_SAS`
  - Allele count in South Asian genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_SAS_Female`
  - Allele count in South Asian Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_SAS_Male`
  - Allele count in South Asian Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_raw`
  - Allele counts before filtering low-confidence genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF`
  - Allele Frequency among genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_AFR`
  - Allele Frequency among African/African American genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_AFR_Female`
  - Allele Frequency among African/African American Female genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_AFR_Male`
  - Allele Frequency among African/African American Male genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_AMR`
  - Allele Frequency among Admixed American genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_AMR_Female`
  - Allele Frequency among Admixed American Female genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_AMR_Male`
  - Allele Frequency among Admixed American Male genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_ASJ`
  - Allele Frequency among Ashkenazi Jewish genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_ASJ_Female`
  - Allele Frequency among Ashkenazi Jewish Female genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_ASJ_Male`
  - Allele Frequency among Ashkenazi Jewish Male genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_EAS`
  - Allele Frequency among East Asian genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_EAS_Female`
  - Allele Frequency among East Asian Female genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_EAS_Male`
  - Allele Frequency among East Asian Male genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_FIN`
  - Allele Frequency among Finnish genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_FIN_Female`
  - Allele Frequency among Finnish Female genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_FIN_Male`
  - Allele Frequency among Finnish Male genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_Female`
  - Allele Frequency among Female genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_Male`
  - Allele Frequency among Male genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_NFE`
  - Allele Frequency among Non-Finnish European genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_NFE_Female`
  - Allele Frequency among Non-Finnish European Female genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_NFE_Male`
  - Allele Frequency among Non-Finnish European Male genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_OTH`
  - Allele Frequency among Other (population not assigned) genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_OTH_Female`
  - Allele Frequency among Other (population not assigned) Female genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_OTH_Male`
  - Allele Frequency among Other (population not assigned) Male genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_POPMAX`
  - Maximum Allele Frequency across populations (excluding OTH)
* [STRING]    `AF_SAS`
  - Allele Frequency among South Asian genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_SAS_Female`
  - Allele Frequency among South Asian Female genotypes, for each ALT allele, in the same order as listed
* [STRING]    `AF_SAS_Male`
  - Allele Frequency among South Asian Male genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `AF_raw`
  - Allele frequency before filtering low-confidence genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AN`
  - Total number of alleles in called genotypes
* [INTEGER]   `AN_AFR`
  - Total number of alleles in African/African American called genotypes
* [INTEGER]   `AN_AFR_Female`
  - Total number of alleles in African/African American Female called genotypes
* [INTEGER]   `AN_AFR_Male`
  - Total number of alleles in African/African American Male called genotypes
* [INTEGER]   `AN_AMR`
  - Total number of alleles in Admixed American called genotypes
* [INTEGER]   `AN_AMR_Female`
  - Total number of alleles in Admixed American Female called genotypes
* [INTEGER]   `AN_AMR_Male`
  - Total number of alleles in Admixed American Male called genotypes
* [INTEGER]   `AN_ASJ`
  - Total number of alleles in Ashkenazi Jewish called genotypes
* [INTEGER]   `AN_ASJ_Female`
  - Total number of alleles in Ashkenazi Jewish Female called genotypes
* [INTEGER]   `AN_ASJ_Male`
  - Total number of alleles in Ashkenazi Jewish Male called genotypes
* [INTEGER]   `AN_EAS`
  - Total number of alleles in East Asian called genotypes
* [INTEGER]   `AN_EAS_Female`
  - Total number of alleles in East Asian Female called genotypes
* [INTEGER]   `AN_EAS_Male`
  - Total number of alleles in East Asian Male called genotypes
* [INTEGER]   `AN_FIN`
  - Total number of alleles in Finnish called genotypes
* [INTEGER]   `AN_FIN_Female`
  - Total number of alleles in Finnish Female called genotypes
* [INTEGER]   `AN_FIN_Male`
  - Total number of alleles in Finnish Male called genotypes
* [INTEGER]   `AN_Female`
  - Total number of alleles in Female called genotypes
* [INTEGER]   `AN_Male`
  - Total number of alleles in Male called genotypes
* [INTEGER]   `AN_NFE`
  - Total number of alleles in Non-Finnish European called genotypes
* [INTEGER]   `AN_NFE_Female`
  - Total number of alleles in Non-Finnish European Female called genotypes
* [INTEGER]   `AN_NFE_Male`
  - Total number of alleles in Non-Finnish European Male called genotypes
* [INTEGER]   `AN_OTH`
  - Total number of alleles in Other (population not assigned) called genotypes
* [INTEGER]   `AN_OTH_Female`
  - Total number of alleles in Other (population not assigned) Female called genotypes
* [INTEGER]   `AN_OTH_Male`
  - Total number of alleles in Other (population not assigned) Male called genotypes
* [STRING]    `AN_POPMAX`
  - AN in the population with the max AF
* [INTEGER]   `AN_SAS`
  - Total number of alleles in South Asian called genotypes
* [INTEGER]   `AN_SAS_Female`
  - Total number of alleles in South Asian Female called genotypes
* [INTEGER]   `AN_SAS_Male`
  - Total number of alleles in South Asian Male called genotypes
* [INTEGER]   `AN_raw`
  - Total number of alleles before filtering low-confidence genotypes
* [STRING]    `AS_FilterStatus`
  - Random Forests filter status for each allele
* [STRING]    `AS_RF`
  - Random Forests probability for each allele
* [INTEGER]   `AS_RF_NEGATIVE_TRAIN`
  - Contains the indices of all alleles used as negative examples during training of random forests
* [INTEGER]   `AS_RF_POSITIVE_TRAIN`
  - Contains the indices of all alleles used as positive examples during training of random forests
* [FLOAT]     `BaseQRankSum`
  - Z-score from Wilcoxon rank sum test of Alt Vs. Ref base qualities
* [STRING]    `CSQ`
  - Consequence annotations from Ensembl VEP. Format: Allele|Consequence|IMPACT|SYMBOL|Gene|Feature_type|Feature|BIOTYPE|EXON|INTRON|HGVSc|HGVSp|cDNA_position|CDS_position|Protein_position|Amino_acids|Codons|Existing_variation|ALLELE_NUM|DISTANCE|STRAND|FLAGS|VARIANT_CLASS|MINIMISED|SYMBOL_SOURCE|HGNC_ID|CANONICAL|TSL|APPRIS|CCDS|ENSP|SWISSPROT|TREMBL|UNIPARC|GENE_PHENO|SIFT|PolyPhen|DOMAINS|HGVS_OFFSET|GMAF|AFR_MAF|AMR_MAF|EAS_MAF|EUR_MAF|SAS_MAF|AA_MAF|EA_MAF|ExAC_MAF|ExAC_Adj_MAF|ExAC_AFR_MAF|ExAC_AMR_MAF|ExAC_EAS_MAF|ExAC_FIN_MAF|ExAC_NFE_MAF|ExAC_OTH_MAF|ExAC_SAS_MAF|CLIN_SIG|SOMATIC|PHENO|PUBMED|MOTIF_NAME|MOTIF_POS|HIGH_INF_POS|MOTIF_SCORE_CHANGE|LoF|LoF_filter|LoF_flags|LoF_info
* [FLOAT]     `ClippingRankSum`
  - Z-score from Wilcoxon rank sum test of Alt vs. Ref number of hard clipped bases
* [BOOLEAN]   `DB`
  - dbSNP Membership
* [INTEGER]   `DP`
  - Approximate read depth; some reads may have been filtered
* [STRING]    `DP_HIST_ALL`
  - Histogram for DP; Midpoints of histogram bins: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [STRING]    `DP_HIST_ALT`
  - Histogram for DP for each allele; Midpoints of histogram bins: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [STRING]    `DP_MEDIAN`
  - Median DP in carriers of each allele
* [FLOAT]     `DREF_MEDIAN`
  - Median dosage of homozygous reference in carriers of each allele
* [FLOAT]     `FS`
  - Phred-scaled p-value using Fisher's exact test to detect strand bias
* [INTEGER]   `GC`
  - Count of individuals for each genotype
* [INTEGER]   `GC_AFR`
  - Count of African/African American individuals for each genotype
* [INTEGER]   `GC_AFR_Female`
  - Count of African/African American Female individuals for each genotype
* [INTEGER]   `GC_AFR_Male`
  - Count of African/African American Male individuals for each genotype
* [INTEGER]   `GC_AMR`
  - Count of Admixed American individuals for each genotype
* [INTEGER]   `GC_AMR_Female`
  - Count of Admixed American Female individuals for each genotype
* [INTEGER]   `GC_AMR_Male`
  - Count of Admixed American Male individuals for each genotype
* [INTEGER]   `GC_ASJ`
  - Count of Ashkenazi Jewish individuals for each genotype
* [INTEGER]   `GC_ASJ_Female`
  - Count of Ashkenazi Jewish Female individuals for each genotype
* [INTEGER]   `GC_ASJ_Male`
  - Count of Ashkenazi Jewish Male individuals for each genotype
* [INTEGER]   `GC_EAS`
  - Count of East Asian individuals for each genotype
* [INTEGER]   `GC_EAS_Female`
  - Count of East Asian Female individuals for each genotype
* [INTEGER]   `GC_EAS_Male`
  - Count of East Asian Male individuals for each genotype
* [INTEGER]   `GC_FIN`
  - Count of Finnish individuals for each genotype
* [INTEGER]   `GC_FIN_Female`
  - Count of Finnish Female individuals for each genotype
* [INTEGER]   `GC_FIN_Male`
  - Count of Finnish Male individuals for each genotype
* [INTEGER]   `GC_Female`
  - Count of Female individuals for each genotype
* [INTEGER]   `GC_Male`
  - Count of Male individuals for each genotype
* [INTEGER]   `GC_NFE`
  - Count of Non-Finnish European individuals for each genotype
* [INTEGER]   `GC_NFE_Female`
  - Count of Non-Finnish European Female individuals for each genotype
* [INTEGER]   `GC_NFE_Male`
  - Count of Non-Finnish European Male individuals for each genotype
* [INTEGER]   `GC_OTH`
  - Count of Other (population not assigned) individuals for each genotype
* [INTEGER]   `GC_OTH_Female`
  - Count of Other (population not assigned) Female individuals for each genotype
* [INTEGER]   `GC_OTH_Male`
  - Count of Other (population not assigned) Male individuals for each genotype
* [INTEGER]   `GC_SAS`
  - Count of South Asian individuals for each genotype
* [INTEGER]   `GC_SAS_Female`
  - Count of South Asian Female individuals for each genotype
* [INTEGER]   `GC_SAS_Male`
  - Count of South Asian Male individuals for each genotype
* [INTEGER]   `GC_raw`
  - Raw count of individuals for each genotype before filtering low-confidence genotypes
* [STRING]    `GQ_HIST_ALL`
  - Histogram for GQ; Midpoints of histogram bins: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [STRING]    `GQ_HIST_ALT`
  - Histogram for GQ for each allele; Midpoints of histogram bins: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [INTEGER]   `GQ_MEDIAN`
  - Median GQ in carriers of each allele
* [STRING]    `Hemi`
  - Count of hemizygous individuals
* [STRING]    `Hemi_AFR`
  - Count of hemizygous African/African American individuals
* [STRING]    `Hemi_AMR`
  - Count of hemizygous Admixed American individuals
* [STRING]    `Hemi_ASJ`
  - Count of hemizygous Ashkenazi Jewish individuals
* [STRING]    `Hemi_EAS`
  - Count of hemizygous East Asian individuals
* [STRING]    `Hemi_FIN`
  - Count of hemizygous Finnish individuals
* [STRING]    `Hemi_NFE`
  - Count of hemizygous Non-Finnish European individuals
* [STRING]    `Hemi_OTH`
  - Count of hemizygous Other (population not assigned) individuals
* [STRING]    `Hemi_SAS`
  - Count of hemizygous South Asian individuals
* [STRING]    `Hemi_raw`
  - Count of hemizygous individuals in raw genotypes before filtering low-confidence genotypes
* [INTEGER]   `Hom`
  - Count of homozygous individuals
* [INTEGER]   `Hom_AFR`
  - Count of homozygous African/African American individuals
* [INTEGER]   `Hom_AMR`
  - Count of homozygous Admixed American individuals
* [INTEGER]   `Hom_ASJ`
  - Count of homozygous Ashkenazi Jewish individuals
* [INTEGER]   `Hom_EAS`
  - Count of homozygous East Asian individuals
* [INTEGER]   `Hom_FIN`
  - Count of homozygous Finnish individuals
* [INTEGER]   `Hom_Female`
  - Count of homozygous Female individuals
* [INTEGER]   `Hom_Male`
  - Count of homozygous Male individuals
* [INTEGER]   `Hom_NFE`
  - Count of homozygous Non-Finnish European individuals
* [INTEGER]   `Hom_OTH`
  - Count of homozygous Other (population not assigned) individuals
* [INTEGER]   `Hom_SAS`
  - Count of homozygous South Asian individuals
* [INTEGER]   `Hom_raw`
  - Count of homozygous individuals in raw genotypes before filtering low-confidence genotypes
* [FLOAT]     `InbreedingCoeff`
  - Inbreeding coefficient as estimated from the genotype likelihoods per-sample when compared against the Hardy-Weinberg expectation
* [FLOAT]     `MQ`
  - RMS Mapping Quality
* [FLOAT]     `MQRankSum`
  - Z-score from Wilcoxon rank sum test of Alt vs. Ref read mapping qualities
* [STRING]    `POPMAX`
  - Population with max AF
* [FLOAT]     `QD`
  - Variant Confidence/Quality by Depth
* [FLOAT]     `ReadPosRankSum`
  - Z-score from Wilcoxon rank sum test of Alt vs. Ref read position bias
* [FLOAT]     `SOR`
  - Symmetric Odds Ratio of 2x2 contingency table to detect strand bias
* [INTEGER]   `STAR_AC`
  - AC of deletions spanning this position
* [INTEGER]   `STAR_AC_raw`
  - Allele counts of deletions spanning this position before filtering low-confidence genotypes
* [INTEGER]   `STAR_Hemi`
  - Count of individuals hemizygous for a deletion spanning this position
* [INTEGER]   `STAR_Hom`
  - Count of individuals homozygous for a deletion spanning this position
* [FLOAT]     `VQSLOD`
  - Log odds ratio of being a true variant versus being false under the trained VQSR gaussian mixture model (deprecated; see AS_RF)
* [BOOLEAN]   `VQSR_NEGATIVE_TRAIN_SITE`
  - This variant was used to build the negative training set of bad variants for VQSR (deprecated; see AS_RF_NEGATIVE_TRAIN)
* [BOOLEAN]   `VQSR_POSITIVE_TRAIN_SITE`
  - This variant was used to build the positive training set of good variants for VQSR (deprecated; see AS_RF_POSITIVE_TRAIN)
* [STRING]    `VQSR_culprit`
  - The annotation which was the worst performing in the VQSR Gaussian mixture model (deprecated; see AS_RF)

-------------------------------------------------------------------------------
*Do not make edits above this line.*
