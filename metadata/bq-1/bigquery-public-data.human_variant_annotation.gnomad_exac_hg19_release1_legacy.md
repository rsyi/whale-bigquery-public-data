# `human_variant_annotation.gnomad_exac_hg19_release1_legacy`
`bq-1` | `bigquery-public-data`
Source: 
gs://gnomad-public/legacy/exacv1_downloads/release1/ExAC.r1.sites.vep.vcf.gz

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
  - InbreedingCoeff_Filter
LowQual
NewCut_Filter
VQSRTrancheINDEL95.00to96.00
VQSRTrancheINDEL96.00to97.00
VQSRTrancheINDEL97.00to99.00
VQSRTrancheINDEL99.00to99.50
VQSRTrancheINDEL99.50to99.90
VQSRTrancheINDEL99.90to99.95
VQSRTrancheINDEL99.95to100.00+
VQSRTrancheINDEL99.95to100.00
VQSRTrancheSNP99.60to99.80
VQSRTrancheSNP99.80to99.90
VQSRTrancheSNP99.90to99.95
VQSRTrancheSNP99.95to100.00+
VQSRTrancheSNP99.95to100.00
AC_Adj0_Filter
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
* [INTEGER]   `AC`
  - Allele count in genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `AC_AFR`
  - African/African American Allele Counts
* [INTEGER]   `AC_AMR`
  - American Allele Counts
* [INTEGER]   `AC_Adj`
  - Adjusted Allele Counts
* [STRING]    `AC_CONSANGUINEOUS`
  - Allele count among individuals with F > 0.05
* [INTEGER]   `AC_EAS`
  - East Asian Allele Counts
* [STRING]    `AC_FEMALE`
  - Allele count among females
* [INTEGER]   `AC_FIN`
  - Finnish Allele Counts
* [INTEGER]   `AC_Hemi`
  - Adjusted Hemizygous Counts
* [INTEGER]   `AC_Het`
  - Adjusted Heterozygous Counts
* [INTEGER]   `AC_Hom`
  - Adjusted Homozygous Counts
* [STRING]    `AC_MALE`
  - Allele count among males
* [INTEGER]   `AC_NFE`
  - Non-Finnish European Allele Counts
* [INTEGER]   `AC_OTH`
  - Other Allele Counts
* [STRING]    `AC_POPMAX`
  - AC in the population with the max AF
* [INTEGER]   `AC_SAS`
  - South Asian Allele Counts
* [FLOAT]     `AF`
  - Allele Frequency, for each ALT allele, in the same order as listed
* [STRING]    `AGE_HISTOGRAM_HET`
  - Histogram of ages of allele carriers; Bins: <30|30|35|40|45|50|55|60|65|70|75|80+
* [STRING]    `AGE_HISTOGRAM_HOM`
  - Histogram of ages of homozygous allele carriers; Bins: <30|30|35|40|45|50|55|60|65|70|75|80+
* [INTEGER]   `AN`
  - Total number of alleles in called genotypes
* [INTEGER]   `AN_AFR`
  - African/African American Chromosome Count
* [INTEGER]   `AN_AMR`
  - American Chromosome Count
* [INTEGER]   `AN_Adj`
  - Adjusted Chromosome Count
* [INTEGER]   `AN_CONSANGUINEOUS`
  - Allele number among individuals with F > 0.05
* [INTEGER]   `AN_EAS`
  - East Asian Chromosome Count
* [INTEGER]   `AN_FEMALE`
  - Allele number among females
* [INTEGER]   `AN_FIN`
  - Finnish Chromosome Count
* [INTEGER]   `AN_MALE`
  - Allele number among males
* [INTEGER]   `AN_NFE`
  - Non-Finnish European Chromosome Count
* [INTEGER]   `AN_OTH`
  - Other Chromosome Count
* [STRING]    `AN_POPMAX`
  - AN in the population with the max AF
* [INTEGER]   `AN_SAS`
  - South Asian Chromosome Count
* [FLOAT]     `BaseQRankSum`
  - Z-score from Wilcoxon rank sum test of Alt Vs. Ref base qualities
* [STRING]    `CSQ`
  - Consequence annotations from Ensembl VEP. Format: Allele|Consequence|IMPACT|SYMBOL|Gene|Feature_type|Feature|BIOTYPE|EXON|INTRON|HGVSc|HGVSp|cDNA_position|CDS_position|Protein_position|Amino_acids|Codons|Existing_variation|ALLELE_NUM|DISTANCE|STRAND|FLAGS|VARIANT_CLASS|MINIMISED|SYMBOL_SOURCE|HGNC_ID|CANONICAL|TSL|APPRIS|CCDS|ENSP|SWISSPROT|TREMBL|UNIPARC|GENE_PHENO|SIFT|PolyPhen|DOMAINS|HGVS_OFFSET|GMAF|AFR_MAF|AMR_MAF|EAS_MAF|EUR_MAF|SAS_MAF|AA_MAF|EA_MAF|ExAC_MAF|ExAC_Adj_MAF|ExAC_AFR_MAF|ExAC_AMR_MAF|ExAC_EAS_MAF|ExAC_FIN_MAF|ExAC_NFE_MAF|ExAC_OTH_MAF|ExAC_SAS_MAF|CLIN_SIG|SOMATIC|PHENO|PUBMED|MOTIF_NAME|MOTIF_POS|HIGH_INF_POS|MOTIF_SCORE_CHANGE|LoF|LoF_filter|LoF_flags|LoF_info|context|ancestral
* [FLOAT]     `ClippingRankSum`
  - Z-score From Wilcoxon rank sum test of Alt vs. Ref number of hard clipped bases
* [BOOLEAN]   `DB`
  - dbSNP Membership
* [STRING]    `DOUBLETON_DIST`
  - Euclidean distance of carriers of doubletons
* [INTEGER]   `DP`
  - Approximate read depth; some reads may have been filtered
* [STRING]    `DP_HIST`
  - Histogram for DP; Mids: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [STRING]    `ESP_AC`
  - Allele Count in ESP
* [STRING]    `ESP_AF_GLOBAL`
  - Overall allele frequency in ESP
* [STRING]    `ESP_AF_POPMAX`
  - Max allele frequency across populations in ESP
* [FLOAT]     `FS`
  - Phred-scaled p-value using Fisher's exact test to detect strand bias
* [STRING]    `GQ_HIST`
  - Histogram for GQ; Mids: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [FLOAT]     `GQ_MEAN`
  - Mean of all GQ values
* [FLOAT]     `GQ_STDDEV`
  - Standard deviation of all GQ values
* [INTEGER]   `Hemi_AFR`
  - African/African American Hemizygous Counts
* [INTEGER]   `Hemi_AMR`
  - American Hemizygous Counts
* [INTEGER]   `Hemi_EAS`
  - East Asian Hemizygous Counts
* [INTEGER]   `Hemi_FIN`
  - Finnish Hemizygous Counts
* [INTEGER]   `Hemi_NFE`
  - Non-Finnish European Hemizygous Counts
* [INTEGER]   `Hemi_OTH`
  - Other Hemizygous Counts
* [INTEGER]   `Hemi_SAS`
  - South Asian Hemizygous Counts
* [INTEGER]   `Het_AFR`
  - African/African American Heterozygous Counts
* [INTEGER]   `Het_AMR`
  - American Heterozygous Counts
* [INTEGER]   `Het_EAS`
  - East Asian Heterozygous Counts
* [INTEGER]   `Het_FIN`
  - Finnish Heterozygous Counts
* [INTEGER]   `Het_NFE`
  - Non-Finnish European Heterozygous Counts
* [INTEGER]   `Het_OTH`
  - Other Heterozygous Counts
* [INTEGER]   `Het_SAS`
  - South Asian Heterozygous Counts
* [INTEGER]   `Hom_AFR`
  - African/African American Homozygous Counts
* [INTEGER]   `Hom_AMR`
  - American Homozygous Counts
* [STRING]    `Hom_CONSANGUINEOUS`
  - Homozygote count among individuals with F > 0.05
* [INTEGER]   `Hom_EAS`
  - East Asian Homozygous Counts
* [INTEGER]   `Hom_FIN`
  - Finnish Homozygous Counts
* [INTEGER]   `Hom_NFE`
  - Non-Finnish European Homozygous Counts
* [INTEGER]   `Hom_OTH`
  - Other Homozygous Counts
* [INTEGER]   `Hom_SAS`
  - South Asian Homozygous Counts
* [FLOAT]     `InbreedingCoeff`
  - Inbreeding coefficient as estimated from the genotype likelihoods per-sample when compared against the Hardy-Weinberg expectation
* [STRING]    `K1_RUN`
  - Number of ensuing single nucleotide repeats.
* [STRING]    `K2_RUN`
  - Number of ensuing di-nucleotide repeats.
* [STRING]    `K3_RUN`
  - Number of ensuing tri-nucleotide repeats.
* [STRING]    `KG_AC`
  - Allele Count in 1000 Genomes
* [STRING]    `KG_AF_GLOBAL`
  - Overall allele frequency in 1000 Genomes
* [STRING]    `KG_AF_POPMAX`
  - Max allele frequency across populations in 1000 Genomes
* [FLOAT]     `MQ`
  - RMS Mapping Quality
* [INTEGER]   `MQ0`
  - Total Mapping Quality Zero Reads
* [FLOAT]     `MQRankSum`
  - Z-score From Wilcoxon rank sum test of Alt vs. Ref read mapping qualities
* [INTEGER]   `NCC`
  - Number of no-called samples
* [BOOLEAN]   `NEGATIVE_TRAIN_SITE`
  - This variant was used to build the negative training set of bad variants
* [STRING]    `POPMAX`
  - Population with max AF
* [BOOLEAN]   `POSITIVE_TRAIN_SITE`
  - This variant was used to build the positive training set of good variants
* [FLOAT]     `QD`
  - Variant Confidence/Quality by Depth
* [FLOAT]     `ReadPosRankSum`
  - Z-score from Wilcoxon rank sum test of Alt vs. Ref read position bias
* [FLOAT]     `VQSLOD`
  - Log odds ratio of being a true variant versus being false under the trained gaussian mixture model
* [STRING]    `clinvar_conflicted`
  - Clinvar Conflicted Status
* [STRING]    `clinvar_measureset_id`
  - Clinvar Measureset ID
* [STRING]    `clinvar_mut`
  - Clinvar MUT Flag (is disease allele REF?)
* [STRING]    `clinvar_pathogenic`
  - Clinvar Pathogenic Status
* [STRING]    `culprit`
  - The annotation which was the worst performing in the Gaussian mixture model, likely the reason why the variant was filtered out

-------------------------------------------------------------------------------
*Do not make edits above this line.*
