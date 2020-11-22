# `human_variant_annotation.gnomad_gnomad_exomes_hg19_release_2_0_2`
`bq-1` | `bigquery-public-data`
Source: gs://gnomad-public/release/2.0.2/vcf/exomes/gnomad.exomes.r2.0.2.sites.vcf.bgz

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
  - Allele Frequency among genotypes, for each ALT allele, in the same order as listed
* [STRING]    `alternate_bases.GQ_HIST_ALT`
  - Histogram for GQ for each allele; Midpoints of histogram bins: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [STRING]    `alternate_bases.DP_HIST_ALT`
  - Histogram for DP for each allele; Midpoints of histogram bins: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [STRING]    `alternate_bases.AB_HIST_ALT`
  - Histogram for Allele Balance in heterozygous individuals for each allele; 100*AD[i_alt]/sum(AD); Midpoints of histogram bins: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [INTEGER]   `alternate_bases.AC_AFR`
  - Allele count in African/African American genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_AMR`
  - Allele count in Admixed American genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_ASJ`
  - Allele count in Ashkenazi Jewish genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_EAS`
  - Allele count in East Asian genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_FIN`
  - Allele count in Finnish genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_NFE`
  - Allele count in Non-Finnish European genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_OTH`
  - Allele count in Other (population not assigned) genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_SAS`
  - Allele count in South Asian genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_Male`
  - Allele count in Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_Female`
  - Allele count in Female genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_AFR`
  - Allele Frequency among African/African American genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_AMR`
  - Allele Frequency among Admixed American genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_ASJ`
  - Allele Frequency among Ashkenazi Jewish genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_EAS`
  - Allele Frequency among East Asian genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_FIN`
  - Allele Frequency among Finnish genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_NFE`
  - Allele Frequency among Non-Finnish European genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_OTH`
  - Allele Frequency among Other (population not assigned) genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_SAS`
  - Allele Frequency among South Asian genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_Male`
  - Allele Frequency among Male genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_Female`
  - Allele Frequency among Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_raw`
  - Allele counts before filtering low-confidence genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_raw`
  - Allele frequency before filtering low-confidence genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.Hom_AFR`
  - Count of homozygous African/African American individuals
* [INTEGER]   `alternate_bases.Hom_AMR`
  - Count of homozygous Admixed American individuals
* [INTEGER]   `alternate_bases.Hom_ASJ`
  - Count of homozygous Ashkenazi Jewish individuals
* [INTEGER]   `alternate_bases.Hom_EAS`
  - Count of homozygous East Asian individuals
* [INTEGER]   `alternate_bases.Hom_FIN`
  - Count of homozygous Finnish individuals
* [INTEGER]   `alternate_bases.Hom_NFE`
  - Count of homozygous Non-Finnish European individuals
* [INTEGER]   `alternate_bases.Hom_OTH`
  - Count of homozygous Other (population not assigned) individuals
* [INTEGER]   `alternate_bases.Hom_SAS`
  - Count of homozygous South Asian individuals
* [INTEGER]   `alternate_bases.Hom_Male`
  - Count of homozygous Male individuals
* [INTEGER]   `alternate_bases.Hom_Female`
  - Count of homozygous Female individuals
* [INTEGER]   `alternate_bases.Hom_raw`
  - Count of homozygous individuals in raw genotypes before filtering low-confidence genotypes
* [INTEGER]   `alternate_bases.Hom`
  - Count of homozygous individuals
* [STRING]    `alternate_bases.POPMAX`
  - Population with max AF
* [INTEGER]   `alternate_bases.AC_POPMAX`
  - AC in the population with the max AF
* [INTEGER]   `alternate_bases.AN_POPMAX`
  - AN in the population with the max AF
* [FLOAT]     `alternate_bases.AF_POPMAX`
  - Maximum Allele Frequency across populations (excluding OTH)
* [INTEGER]   `alternate_bases.DP_MEDIAN`
  - Median DP in carriers of each allele
* [FLOAT]     `alternate_bases.DREF_MEDIAN`
  - Median dosage of homozygous reference in carriers of each allele
* [INTEGER]   `alternate_bases.GQ_MEDIAN`
  - Median GQ in carriers of each allele
* [FLOAT]     `alternate_bases.AB_MEDIAN`
  - Median allele balance in heterozygote carriers of each allele
* [FLOAT]     `alternate_bases.AS_RF`
  - Random Forests probability for each allele
* [STRING]    `alternate_bases.AS_FilterStatus`
  - Random Forests filter status for each allele
* [INTEGER]   `alternate_bases.AC_AFR_Male`
  - Allele count in African/African American Male genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_AMR_Male`
  - Allele Frequency among Admixed American Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.Hemi_NFE`
  - Count of hemizygous Non-Finnish European individuals
* [INTEGER]   `alternate_bases.Hemi_AFR`
  - Count of hemizygous African/African American individuals
* [INTEGER]   `alternate_bases.AC_ASJ_Female`
  - Allele count in Ashkenazi Jewish Female genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_FIN_Female`
  - Allele Frequency among Finnish Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_OTH_Female`
  - Allele count in Other (population not assigned) Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_NFE_Female`
  - Allele count in Non-Finnish European Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_EAS_Male`
  - Allele count in East Asian Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_OTH_Male`
  - Allele count in Other (population not assigned) Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.Hemi_AMR`
  - Count of hemizygous Admixed American individuals
* [INTEGER]   `alternate_bases.AC_NFE_Male`
  - Allele count in Non-Finnish European Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.Hemi`
  - Count of hemizygous individuals
* [INTEGER]   `alternate_bases.Hemi_SAS`
  - Count of hemizygous South Asian individuals
* [FLOAT]     `alternate_bases.AF_FIN_Male`
  - Allele Frequency among Finnish Male genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_AFR_Male`
  - Allele Frequency among African/African American Male genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_SAS_Male`
  - Allele Frequency among South Asian Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.Hemi_ASJ`
  - Count of hemizygous Ashkenazi Jewish individuals
* [INTEGER]   `alternate_bases.Hemi_raw`
  - Count of hemizygous individuals in raw genotypes before filtering low-confidence genotypes
* [FLOAT]     `alternate_bases.AF_OTH_Male`
  - Allele Frequency among Other (population not assigned) Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_SAS_Female`
  - Allele count in South Asian Female genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_NFE_Female`
  - Allele Frequency among Non-Finnish European Female genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_EAS_Female`
  - Allele Frequency among East Asian Female genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_EAS_Male`
  - Allele Frequency among East Asian Male genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_SAS_Female`
  - Allele Frequency among South Asian Female genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_AFR_Female`
  - Allele Frequency among African/African American Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_FIN_Female`
  - Allele count in Finnish Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.Hemi_OTH`
  - Count of hemizygous Other (population not assigned) individuals
* [INTEGER]   `alternate_bases.AC_AFR_Female`
  - Allele count in African/African American Female genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_AMR_Female`
  - Allele Frequency among Admixed American Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_AMR_Male`
  - Allele count in Admixed American Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_SAS_Male`
  - Allele count in South Asian Male genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_ASJ_Male`
  - Allele Frequency among Ashkenazi Jewish Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_EAS_Female`
  - Allele count in East Asian Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_AMR_Female`
  - Allele count in Admixed American Female genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.Hemi_FIN`
  - Count of hemizygous Finnish individuals
* [INTEGER]   `alternate_bases.AC_FIN_Male`
  - Allele count in Finnish Male genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_ASJ_Female`
  - Allele Frequency among Ashkenazi Jewish Female genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_OTH_Female`
  - Allele Frequency among Other (population not assigned) Female genotypes, for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.AF_NFE_Male`
  - Allele Frequency among Non-Finnish European Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.AC_ASJ_Male`
  - Allele count in Ashkenazi Jewish Male genotypes, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.Hemi_EAS`
  - Count of hemizygous East Asian individuals
* [RECORD]    `alternate_bases.CSQ`
  - List of CSQ annotations for this alternate.
* [STRING]    `alternate_bases.CSQ.allele`
  - The ALT part of the annotation field.
* [STRING]    `alternate_bases.CSQ.Consequence`
  - Consequence type of this variant
* [STRING]    `alternate_bases.CSQ.IMPACT`
  - The impact modifier for the consequence type
* [STRING]    `alternate_bases.CSQ.SYMBOL`
  - The gene symbol
* [STRING]    `alternate_bases.CSQ.Gene`
  - Ensembl stable ID of affected gene
* [STRING]    `alternate_bases.CSQ.Feature_type`
  - Type of feature. Currently one of Transcript, RegulatoryFeature, MotifFeature.
* [STRING]    `alternate_bases.CSQ.Feature`
  - Ensembl stable ID of feature
* [STRING]    `alternate_bases.CSQ.BIOTYPE`
  - Biotype of transcript or regulatory feature
* [STRING]    `alternate_bases.CSQ.EXON`
  - The exon number (out of total number)
* [STRING]    `alternate_bases.CSQ.INTRON`
  - The intron number (out of total number)
* [STRING]    `alternate_bases.CSQ.HGVSc`
  - The HGVS coding sequence name
* [STRING]    `alternate_bases.CSQ.HGVSp`
  - The HGVS protein sequence name
* [STRING]    `alternate_bases.CSQ.cDNA_position`
  - Relative position of base pair in cDNA sequence
* [STRING]    `alternate_bases.CSQ.CDS_position`
  - Relative position of base pair in coding sequence
* [STRING]    `alternate_bases.CSQ.Protein_position`
  - Relative position of amino acid in protein
* [STRING]    `alternate_bases.CSQ.Amino_acids`
  - Reference and variant amino acids. Only given if the variant affects the protein-coding sequence
* [STRING]    `alternate_bases.CSQ.Codons`
  - The alternative codons with the variant base in upper case
* [STRING]    `alternate_bases.CSQ.Existing_variation`
  - Known identifier of existing variant
* [STRING]    `alternate_bases.CSQ.ALLELE_NUM`
  - Allele number from input; 0 is reference, 1 is first alternate etc
* [STRING]    `alternate_bases.CSQ.DISTANCE`
  - Shortest distance from variant to transcript
* [STRING]    `alternate_bases.CSQ.STRAND`
  - The DNA strand (1 or -1) on which the transcript/feature lies
* [STRING]    `alternate_bases.CSQ.FLAGS`
  - Transcript quality flags (cds_start_NF, cds_start_NF)
* [STRING]    `alternate_bases.CSQ.VARIANT_CLASS`
  - Sequence Ontology variant class
* [STRING]    `alternate_bases.CSQ.MINIMISED`
  - Alleles in this variant have been converted to minimal representation before consequence calculation
* [STRING]    `alternate_bases.CSQ.SYMBOL_SOURCE`
  - The source of the gene symbol
* [STRING]    `alternate_bases.CSQ.HGNC_ID`
  - HUGO Gene Nomenclature Committee approved symbol
* [STRING]    `alternate_bases.CSQ.CANONICAL`
  - A flag indicating if the transcript is denoted as the canonical transcript for this gene
* [STRING]    `alternate_bases.CSQ.TSL`
  - Transcript support level. NB: not available for GRCh37
* [STRING]    `alternate_bases.CSQ.APPRIS`
  - Annotates alternatively spliced transcripts as primary or alternate based on a range of computational methods. NB: not available for GRCh37
* [STRING]    `alternate_bases.CSQ.CCDS`
  - The CCDS identifer for this transcript, where applicable
* [STRING]    `alternate_bases.CSQ.ENSP`
  - The Ensembl protein identifier of the affected transcript
* [STRING]    `alternate_bases.CSQ.SWISSPROT`
  - Best match UniProtKB/Swiss-Prot accession of protein product
* [STRING]    `alternate_bases.CSQ.TREMBL`
  - Best match UniProtKB/TrEMBL accession of protein product
* [STRING]    `alternate_bases.CSQ.UNIPARC`
  - Best match UniParc accession of protein product
* [STRING]    `alternate_bases.CSQ.GENE_PHENO`
  - Indicates if overlapped gene is associated with a phenotype, disease or trait
* [STRING]    `alternate_bases.CSQ.SIFT`
  - The SIFT prediction and/or score, with both given as prediction(score)
* [STRING]    `alternate_bases.CSQ.PolyPhen`
  - The PolyPhen prediction and/or score
* [STRING]    `alternate_bases.CSQ.DOMAINS`
  - The source and identifer of any overlapping protein domains
* [STRING]    `alternate_bases.CSQ.HGVS_OFFSET`
  - Indicates by how many bases the HGVS notations for this variant have been shifted
* [STRING]    `alternate_bases.CSQ.GMAF`
* [STRING]    `alternate_bases.CSQ.AFR_MAF`
* [STRING]    `alternate_bases.CSQ.AMR_MAF`
* [STRING]    `alternate_bases.CSQ.EAS_MAF`
* [STRING]    `alternate_bases.CSQ.EUR_MAF`
* [STRING]    `alternate_bases.CSQ.SAS_MAF`
* [STRING]    `alternate_bases.CSQ.AA_MAF`
* [STRING]    `alternate_bases.CSQ.EA_MAF`
* [STRING]    `alternate_bases.CSQ.ExAC_MAF`
* [STRING]    `alternate_bases.CSQ.ExAC_Adj_MAF`
* [STRING]    `alternate_bases.CSQ.ExAC_AFR_MAF`
* [STRING]    `alternate_bases.CSQ.ExAC_AMR_MAF`
* [STRING]    `alternate_bases.CSQ.ExAC_EAS_MAF`
* [STRING]    `alternate_bases.CSQ.ExAC_FIN_MAF`
* [STRING]    `alternate_bases.CSQ.ExAC_NFE_MAF`
* [STRING]    `alternate_bases.CSQ.ExAC_OTH_MAF`
* [STRING]    `alternate_bases.CSQ.ExAC_SAS_MAF`
* [STRING]    `alternate_bases.CSQ.CLIN_SIG`
  - ClinVar clinical significance of the dbSNP variant
* [STRING]    `alternate_bases.CSQ.SOMATIC`
  - Somatic status of existing variant(s); multiple values correspond to multiple values in the Existing_variation field
* [STRING]    `alternate_bases.CSQ.PHENO`
  - Indicates if existing variant is associated with a phenotype, disease or trait; multiple values correspond to multiple values in the Existing_variation field
* [STRING]    `alternate_bases.CSQ.PUBMED`
  - Pubmed ID(s) of publications that cite existing variant
* [STRING]    `alternate_bases.CSQ.MOTIF_NAME`
  - The source and identifier of a transcription factor binding profile aligned at this position
* [STRING]    `alternate_bases.CSQ.MOTIF_POS`
  - The relative position of the variation in the aligned TFBP
* [STRING]    `alternate_bases.CSQ.HIGH_INF_POS`
  - A flag indicating if the variant falls in a high information position of a transcription factor binding profile (TFBP)
* [STRING]    `alternate_bases.CSQ.MOTIF_SCORE_CHANGE`
  - The difference in motif score of the reference and variant sequences for the TFBP
* [STRING]    `alternate_bases.CSQ.LoF`
* [STRING]    `alternate_bases.CSQ.LoF_filter`
* [STRING]    `alternate_bases.CSQ.LoF_flags`
* [STRING]    `alternate_bases.CSQ.LoF_info`
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
  - Read Depth
* [INTEGER]   `call.GQ`
  - Genotype Quality
* [INTEGER]   `call.PL`
  - Normalized, Phred-scaled likelihoods for genotypes as defined in the VCF specification
* [INTEGER]   `AN`
  - Total number of alleles in called genotypes
* [FLOAT]     `BaseQRankSum`
  - Z-score from Wilcoxon rank sum test of Alt Vs. Ref base qualities
* [FLOAT]     `ClippingRankSum`
  - Z-score from Wilcoxon rank sum test of Alt vs. Ref number of hard clipped bases
* [BOOLEAN]   `DB`
  - dbSNP Membership
* [INTEGER]   `DP`
  - Approximate read depth; some reads may have been filtered
* [FLOAT]     `FS`
  - Phred-scaled p-value using Fisher's exact test to detect strand bias
* [FLOAT]     `InbreedingCoeff`
  - Inbreeding coefficient as estimated from the genotype likelihoods per-sample when compared against the Hardy-Weinberg expectation
* [FLOAT]     `MQ`
  - RMS Mapping Quality
* [FLOAT]     `MQRankSum`
  - Z-score from Wilcoxon rank sum test of Alt vs. Ref read mapping qualities
* [FLOAT]     `QD`
  - Variant Confidence/Quality by Depth
* [FLOAT]     `ReadPosRankSum`
  - Z-score from Wilcoxon rank sum test of Alt vs. Ref read position bias
* [FLOAT]     `SOR`
  - Symmetric Odds Ratio of 2x2 contingency table to detect strand bias
* [FLOAT]     `VQSLOD`
  - Log odds ratio of being a true variant versus being false under the trained VQSR gaussian mixture model (deprecated; see AS_RF)
* [STRING]    `VQSR_culprit`
  - The annotation which was the worst performing in the VQSR Gaussian mixture model (deprecated; see AS_RF)
* [BOOLEAN]   `VQSR_NEGATIVE_TRAIN_SITE`
  - This variant was used to build the negative training set of bad variants for VQSR (deprecated; see AS_RF_NEGATIVE_TRAIN)
* [BOOLEAN]   `VQSR_POSITIVE_TRAIN_SITE`
  - This variant was used to build the positive training set of good variants for VQSR (deprecated; see AS_RF_POSITIVE_TRAIN)
* [STRING]    `GQ_HIST_ALL`
  - Histogram for GQ; Midpoints of histogram bins: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [STRING]    `DP_HIST_ALL`
  - Histogram for DP; Midpoints of histogram bins: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [STRING]    `AB_HIST_ALL`
  - Histogram for Allele Balance in heterozygous individuals; 100*AD[i_alt]/sum(AD); Midpoints of histogram bins: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [INTEGER]   `AN_AFR`
  - Total number of alleles in African/African American called genotypes
* [INTEGER]   `AN_AMR`
  - Total number of alleles in Admixed American called genotypes
* [INTEGER]   `AN_ASJ`
  - Total number of alleles in Ashkenazi Jewish called genotypes
* [INTEGER]   `AN_EAS`
  - Total number of alleles in East Asian called genotypes
* [INTEGER]   `AN_FIN`
  - Total number of alleles in Finnish called genotypes
* [INTEGER]   `AN_NFE`
  - Total number of alleles in Non-Finnish European called genotypes
* [INTEGER]   `AN_OTH`
  - Total number of alleles in Other (population not assigned) called genotypes
* [INTEGER]   `AN_SAS`
  - Total number of alleles in South Asian called genotypes
* [INTEGER]   `AN_Male`
  - Total number of alleles in Male called genotypes
* [INTEGER]   `AN_Female`
  - Total number of alleles in Female called genotypes
* [INTEGER]   `GC_AFR`
  - Count of African/African American individuals for each genotype
* [INTEGER]   `GC_AMR`
  - Count of Admixed American individuals for each genotype
* [INTEGER]   `GC_ASJ`
  - Count of Ashkenazi Jewish individuals for each genotype
* [INTEGER]   `GC_EAS`
  - Count of East Asian individuals for each genotype
* [INTEGER]   `GC_FIN`
  - Count of Finnish individuals for each genotype
* [INTEGER]   `GC_NFE`
  - Count of Non-Finnish European individuals for each genotype
* [INTEGER]   `GC_OTH`
  - Count of Other (population not assigned) individuals for each genotype
* [INTEGER]   `GC_SAS`
  - Count of South Asian individuals for each genotype
* [INTEGER]   `GC_Male`
  - Count of Male individuals for each genotype
* [INTEGER]   `GC_Female`
  - Count of Female individuals for each genotype
* [INTEGER]   `AN_raw`
  - Total number of alleles before filtering low-confidence genotypes
* [INTEGER]   `GC_raw`
  - Raw count of individuals for each genotype before filtering low-confidence genotypes
* [INTEGER]   `GC`
  - Count of individuals for each genotype
* [INTEGER]   `STAR_AC`
  - AC of deletions spanning this position
* [INTEGER]   `STAR_AC_raw`
  - Allele counts of deletions spanning this position before filtering low-confidence genotypes
* [INTEGER]   `STAR_Hom`
  - Count of individuals homozygous for a deletion spanning this position
* [INTEGER]   `AS_RF_POSITIVE_TRAIN`
  - Contains the indices of all alleles used as positive examples during training of random forests
* [INTEGER]   `AS_RF_NEGATIVE_TRAIN`
  - Contains the indices of all alleles used as negative examples during training of random forests
* [INTEGER]   `AN_FIN_Male`
  - Total number of alleles in Finnish Male called genotypes
* [INTEGER]   `AN_EAS_Female`
  - Total number of alleles in East Asian Female called genotypes
* [INTEGER]   `AN_NFE_Female`
  - Total number of alleles in Non-Finnish European Female called genotypes
* [INTEGER]   `AN_AMR_Female`
  - Total number of alleles in Admixed American Female called genotypes
* [INTEGER]   `AN_ASJ_Male`
  - Total number of alleles in Ashkenazi Jewish Male called genotypes
* [INTEGER]   `GC_OTH_Male`
  - Count of Other (population not assigned) Male individuals for each genotype
* [INTEGER]   `GC_FIN_Male`
  - Count of Finnish Male individuals for each genotype
* [INTEGER]   `GC_SAS_Male`
  - Count of South Asian Male individuals for each genotype
* [INTEGER]   `AN_FIN_Female`
  - Total number of alleles in Finnish Female called genotypes
* [INTEGER]   `GC_EAS_Male`
  - Count of East Asian Male individuals for each genotype
* [INTEGER]   `GC_ASJ_Female`
  - Count of Ashkenazi Jewish Female individuals for each genotype
* [INTEGER]   `GC_SAS_Female`
  - Count of South Asian Female individuals for each genotype
* [INTEGER]   `GC_ASJ_Male`
  - Count of Ashkenazi Jewish Male individuals for each genotype
* [INTEGER]   `AN_ASJ_Female`
  - Total number of alleles in Ashkenazi Jewish Female called genotypes
* [INTEGER]   `AN_OTH_Male`
  - Total number of alleles in Other (population not assigned) Male called genotypes
* [INTEGER]   `STAR_Hemi`
  - Count of individuals hemizygous for a deletion spanning this position
* [INTEGER]   `AN_SAS_Female`
  - Total number of alleles in South Asian Female called genotypes
* [INTEGER]   `AN_AFR_Female`
  - Total number of alleles in African/African American Female called genotypes
* [INTEGER]   `AN_OTH_Female`
  - Total number of alleles in Other (population not assigned) Female called genotypes
* [INTEGER]   `GC_AFR_Female`
  - Count of African/African American Female individuals for each genotype
* [INTEGER]   `GC_AMR_Male`
  - Count of Admixed American Male individuals for each genotype
* [INTEGER]   `GC_NFE_Male`
  - Count of Non-Finnish European Male individuals for each genotype
* [INTEGER]   `GC_NFE_Female`
  - Count of Non-Finnish European Female individuals for each genotype
* [INTEGER]   `AN_AFR_Male`
  - Total number of alleles in African/African American Male called genotypes
* [INTEGER]   `AN_NFE_Male`
  - Total number of alleles in Non-Finnish European Male called genotypes
* [INTEGER]   `GC_AMR_Female`
  - Count of Admixed American Female individuals for each genotype
* [INTEGER]   `GC_FIN_Female`
  - Count of Finnish Female individuals for each genotype
* [INTEGER]   `GC_EAS_Female`
  - Count of East Asian Female individuals for each genotype
* [INTEGER]   `GC_AFR_Male`
  - Count of African/African American Male individuals for each genotype
* [INTEGER]   `AN_SAS_Male`
  - Total number of alleles in South Asian Male called genotypes
* [INTEGER]   `AN_EAS_Male`
  - Total number of alleles in East Asian Male called genotypes
* [INTEGER]   `AN_AMR_Male`
  - Total number of alleles in Admixed American Male called genotypes
* [INTEGER]   `GC_OTH_Female`
  - Count of Other (population not assigned) Female individuals for each genotype
* [BOOLEAN]   `segdup`
  - In a segmental duplication region
* [BOOLEAN]   `lcr`
  - In a low complexity region
* [DATE]      `partition_date_please_ignore`
  - Column required by BigQuery partitioning/clustering logic. See https://cloud.google.com/bigquery/docs/clustered-tables

-------------------------------------------------------------------------------
*Do not make edits above this line.*
