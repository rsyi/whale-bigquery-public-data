# `human_variant_annotation.gnomad_exac_hg19_release1`
`bq-1` | `bigquery-public-data`
Source: gs://gnomad-public/legacy/exacv1_downloads/release1/ExAC.r1.sites.vep.vcf.gz

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
* [INTEGER]   `alternate_bases.AC_AFR`
  - African/African American Allele Counts
* [INTEGER]   `alternate_bases.AC_AMR`
  - American Allele Counts
* [INTEGER]   `alternate_bases.AC_Adj`
  - Adjusted Allele Counts
* [INTEGER]   `alternate_bases.AC_EAS`
  - East Asian Allele Counts
* [INTEGER]   `alternate_bases.AC_FIN`
  - Finnish Allele Counts
* [INTEGER]   `alternate_bases.AC_Hemi`
  - Adjusted Hemizygous Counts
* [INTEGER]   `alternate_bases.AC_Hom`
  - Adjusted Homozygous Counts
* [INTEGER]   `alternate_bases.AC_NFE`
  - Non-Finnish European Allele Counts
* [INTEGER]   `alternate_bases.AC_OTH`
  - Other Allele Counts
* [INTEGER]   `alternate_bases.AC_SAS`
  - South Asian Allele Counts
* [FLOAT]     `alternate_bases.AF`
  - Allele Frequency, for each ALT allele, in the same order as listed
* [INTEGER]   `alternate_bases.Hemi_AFR`
  - African/African American Hemizygous Counts
* [INTEGER]   `alternate_bases.Hemi_AMR`
  - American Hemizygous Counts
* [INTEGER]   `alternate_bases.Hemi_EAS`
  - East Asian Hemizygous Counts
* [INTEGER]   `alternate_bases.Hemi_FIN`
  - Finnish Hemizygous Counts
* [INTEGER]   `alternate_bases.Hemi_NFE`
  - Non-Finnish European Hemizygous Counts
* [INTEGER]   `alternate_bases.Hemi_OTH`
  - Other Hemizygous Counts
* [INTEGER]   `alternate_bases.Hemi_SAS`
  - South Asian Hemizygous Counts
* [INTEGER]   `alternate_bases.Hom_AFR`
  - African/African American Homozygous Counts
* [INTEGER]   `alternate_bases.Hom_AMR`
  - American Homozygous Counts
* [INTEGER]   `alternate_bases.Hom_EAS`
  - East Asian Homozygous Counts
* [INTEGER]   `alternate_bases.Hom_FIN`
  - Finnish Homozygous Counts
* [INTEGER]   `alternate_bases.Hom_NFE`
  - Non-Finnish European Homozygous Counts
* [INTEGER]   `alternate_bases.Hom_OTH`
  - Other Homozygous Counts
* [INTEGER]   `alternate_bases.Hom_SAS`
  - South Asian Homozygous Counts
* [INTEGER]   `alternate_bases.MLEAC`
  - Maximum likelihood expectation (MLE) for the allele counts (not necessarily the same as the AC), for each ALT allele, in the same order as listed
* [FLOAT]     `alternate_bases.MLEAF`
  - Maximum likelihood expectation (MLE) for the allele frequency (not necessarily the same as the AF), for each ALT allele, in the same order as listed
* [STRING]    `alternate_bases.DOUBLETON_DIST`
  - Euclidean distance of carriers of doubletons
* [STRING]    `alternate_bases.AC_MALE`
  - Allele count among males
* [STRING]    `alternate_bases.AC_FEMALE`
  - Allele count among females
* [STRING]    `alternate_bases.AC_CONSANGUINEOUS`
  - Allele count among individuals with F > 0.05
* [STRING]    `alternate_bases.Hom_CONSANGUINEOUS`
  - Homozygote count among individuals with F > 0.05
* [STRING]    `alternate_bases.AGE_HISTOGRAM_HET`
  - Histogram of ages of allele carriers; Bins: <30|30|35|40|45|50|55|60|65|70|75|80+
* [STRING]    `alternate_bases.AGE_HISTOGRAM_HOM`
  - Histogram of ages of homozygous allele carriers; Bins: <30|30|35|40|45|50|55|60|65|70|75|80+
* [STRING]    `alternate_bases.AC_POPMAX`
  - AC in the population with the max AF
* [STRING]    `alternate_bases.AN_POPMAX`
  - AN in the population with the max AF
* [STRING]    `alternate_bases.POPMAX`
  - Population with max AF
* [STRING]    `alternate_bases.clinvar_measureset_id`
  - Clinvar Measureset ID
* [STRING]    `alternate_bases.clinvar_conflicted`
  - Clinvar Conflicted Status
* [STRING]    `alternate_bases.clinvar_pathogenic`
  - Clinvar Pathogenic Status
* [STRING]    `alternate_bases.clinvar_mut`
  - Clinvar MUT Flag (is disease allele REF?)
* [STRING]    `alternate_bases.K1_RUN`
  - Number of ensuing single nucleotide repeats.
* [STRING]    `alternate_bases.K2_RUN`
  - Number of ensuing di-nucleotide repeats.
* [STRING]    `alternate_bases.K3_RUN`
  - Number of ensuing tri-nucleotide repeats.
* [STRING]    `alternate_bases.ESP_AF_POPMAX`
  - Max allele frequency across populations in ESP
* [STRING]    `alternate_bases.ESP_AF_GLOBAL`
  - Overall allele frequency in ESP
* [STRING]    `alternate_bases.ESP_AC`
  - Allele Count in ESP
* [STRING]    `alternate_bases.KG_AF_POPMAX`
  - Max allele frequency across populations in 1000 Genomes
* [STRING]    `alternate_bases.KG_AF_GLOBAL`
  - Overall allele frequency in 1000 Genomes
* [STRING]    `alternate_bases.KG_AC`
  - Allele Count in 1000 Genomes
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
* [STRING]    `alternate_bases.CSQ.context`
* [STRING]    `alternate_bases.CSQ.ancestral`
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
* [INTEGER]   `call.MIN_DP`
  - Minimum DP observed within the GVCF block
* [INTEGER]   `call.PL`
  - Normalized, Phred-scaled likelihoods for genotypes as defined in the VCF specification
* [INTEGER]   `call.SB`
  - Per-sample component statistics which comprise the Fisher's Exact Test to detect strand bias.
* [INTEGER]   `AC_Het`
  - Adjusted Heterozygous Counts
* [INTEGER]   `AN`
  - Total number of alleles in called genotypes
* [INTEGER]   `AN_AFR`
  - African/African American Chromosome Count
* [INTEGER]   `AN_AMR`
  - American Chromosome Count
* [INTEGER]   `AN_Adj`
  - Adjusted Chromosome Count
* [INTEGER]   `AN_EAS`
  - East Asian Chromosome Count
* [INTEGER]   `AN_FIN`
  - Finnish Chromosome Count
* [INTEGER]   `AN_NFE`
  - Non-Finnish European Chromosome Count
* [INTEGER]   `AN_OTH`
  - Other Chromosome Count
* [INTEGER]   `AN_SAS`
  - South Asian Chromosome Count
* [FLOAT]     `BaseQRankSum`
  - Z-score from Wilcoxon rank sum test of Alt Vs. Ref base qualities
* [INTEGER]   `CCC`
  - Number of called chromosomes
* [FLOAT]     `ClippingRankSum`
  - Z-score From Wilcoxon rank sum test of Alt vs. Ref number of hard clipped bases
* [BOOLEAN]   `DB`
  - dbSNP Membership
* [INTEGER]   `DP`
  - Approximate read depth; some reads may have been filtered
* [BOOLEAN]   `DS`
  - Were any of the samples downsampled?
* [FLOAT]     `FS`
  - Phred-scaled p-value using Fisher's exact test to detect strand bias
* [FLOAT]     `GQ_MEAN`
  - Mean of all GQ values
* [FLOAT]     `GQ_STDDEV`
  - Standard deviation of all GQ values
* [FLOAT]     `HWP`
  - P value from test of Hardy Weinberg Equilibrium
* [FLOAT]     `HaplotypeScore`
  - Consistency of the site with at most two segregating haplotypes
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
* [FLOAT]     `InbreedingCoeff`
  - Inbreeding coefficient as estimated from the genotype likelihoods per-sample when compared against the Hardy-Weinberg expectation
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
* [BOOLEAN]   `POSITIVE_TRAIN_SITE`
  - This variant was used to build the positive training set of good variants
* [FLOAT]     `QD`
  - Variant Confidence/Quality by Depth
* [FLOAT]     `ReadPosRankSum`
  - Z-score from Wilcoxon rank sum test of Alt vs. Ref read position bias
* [FLOAT]     `VQSLOD`
  - Log odds ratio of being a true variant versus being false under the trained gaussian mixture model
* [STRING]    `culprit`
  - The annotation which was the worst performing in the Gaussian mixture model, likely the reason why the variant was filtered out
* [STRING]    `DP_HIST`
  - Histogram for DP; Mids: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [STRING]    `GQ_HIST`
  - Histogram for GQ; Mids: 2.5|7.5|12.5|17.5|22.5|27.5|32.5|37.5|42.5|47.5|52.5|57.5|62.5|67.5|72.5|77.5|82.5|87.5|92.5|97.5
* [STRING]    `AN_MALE`
  - Allele number among males
* [STRING]    `AN_FEMALE`
  - Allele number among females
* [STRING]    `AN_CONSANGUINEOUS`
  - Allele number among individuals with F > 0.05
* [DATE]      `partition_date_please_ignore`
  - Column required by BigQuery partitioning/clustering logic. See https://cloud.google.com/bigquery/docs/clustered-tables

-------------------------------------------------------------------------------
*Do not make edits above this line.*
