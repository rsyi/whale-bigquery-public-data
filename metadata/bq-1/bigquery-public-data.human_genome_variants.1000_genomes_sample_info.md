# `human_genome_variants.1000_genomes_sample_info`
`bq-1` | `bigquery-public-data`
Source: 
http://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/working/20130606_sample_info/20130606_sample_info.txt

Description:
http://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/working/20130606_sample_info/README_20130606_sample_info

For more information see https://cloud.google.com/genomics/docs/public-datasets/1000-genomes

## Column details
* [STRING]    `Sample`
  - Sample ID
* [STRING]    `Family_ID`
  - Family ID
* [STRING]    `Population`
  - 3 letter population code
* [STRING]    `Population_Description`
  - Description of Population
* [STRING]    `Gender`
  - Gender
* [STRING]    `Relationship`
  - Relationship to other members of the family
* [STRING]    `Unexpected_Parent_Child`
  - sample id for unexpected parent child relationships
* [STRING]    `Non_Paternity`
  - sample ids for annotated non paternal relationships
* [STRING]    `Siblings`
  - sample ids for any siblings
* [STRING]    `Grandparents`
  - sample ids for any grand parents
* [STRING]    `Avuncular`
  - sample ids for any avuncular relationships
* [STRING]    `Half_Siblings`
  - sample ids for any half siblings
* [STRING]    `Unknown_Second_Order`
  - sample ids for any unknown second order relations
* [STRING]    `Third_Order`
  - sample ids for any third order cryptic relations. As mentioned above, this analysis was not as widely run as the other relatedness analyses and as such there may still be unannotated third order relations in the set
* [BOOLEAN]   `In_Low_Coverage_Pilot`
  - The sample is in the low coverage pilot experiment
* [STRING]    `LC_Pilot_Platforms`
  - low coverage pilot sequencing platforms 
* [STRING]    `LC_Pilot_Centers`
  - low coverage pilot sequencing centers
* [BOOLEAN]   `In_High_Coverage_Pilot`
  - The sample is in the high coverage pilot
* [STRING]    `HC_Pilot_Platforms`
  - high coverage sequencing platforms
* [STRING]    `HC_Pilot_Centers`
  - high coverage sequencing centers
* [BOOLEAN]   `In_Exon_Targetted_Pilot`
  - The Sample is in the exon targetted pilot experiment
* [STRING]    `ET_Pilot_Platforms`
  - exon targetted sequencing platforms,
* [STRING]    `ET_Pilot_Centers`
  - exon targetted sequencing centers,
* [BOOLEAN]   `Has_Sequence_in_Phase1`
  - Has sequence low coverage sequence in the 20101123.sequence.index file or exome sequence in the 20110522 sequence index file
* [STRING]    `Phase1_LC_Platform`
  - phase1 low coverage sequencing platforms
* [STRING]    `Phase1_LC_Centers`
  - phase1 low coverage sequencing centers
* [STRING]    `Phase1_E_Platform`
  - phase1 exome sequencing platforms
* [STRING]    `Phase1_E_Centers`
  - phase1 exome sequencing centers
* [BOOLEAN]   `In_Phase1_Integrated_Variant_Set`
  - The sample is genotyped in the phase1 integrated call set on autosomes and chrX
* [BOOLEAN]   `Has_Phase1_chrY_SNPS`
  - The sample is genotyped in the chrY phase1 snp set
* [BOOLEAN]   `Has_phase1_chrY_Deletions`
  - The sample is genotyepd in the chrY phase1 deletions
* [BOOLEAN]   `Has_phase1_chrMT_SNPs`
  - The sample is genotyped in the phase1 chrMT snps
* [STRING]    `Main_project_LC_Centers`
  - low coverage sequencing centers for final sequencing round
* [STRING]    `Main_project_LC_platform`
  - low coverage sequencing platform for final sequencing round
* [FLOAT]     `Total_LC_Sequence`
  - The total amount of low coverage sequence available
* [FLOAT]     `LC_Non_Duplicated_Aligned_Coverage`
  - The non duplicated aligned coverage for the low coverage sequence data.  This was calculated using the ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/alignment_indices/20130502.low_coverage.alignment.index.bas.gz file, the (mapped bases - duplicated bases) was summed for each sample and divided by 2.75GB and rounded to 2dp
* [STRING]    `Main_Project_E_Centers`
  - Exome sequencing centers for the final sequencing round
* [STRING]    `Main_Project_E_Platform`
  - Exome sequencing platform for the final sequencing round
* [FLOAT]     `Total_Exome_Sequence`
  - The total amount of exome sequence available
* [FLOAT]     `X_Targets_Covered_to_20x_or_greater`
  - The percentage of targets covered to 20x or greater as calculated by the picard function CalculateHsMetrics using these targets ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/reference/exome_pull_down_targets_phases1_and_2/20120518.consensus.annotation.bed
* [FLOAT]     `VerifyBam_E_Omni_Free`
  - Value from UMich's VerifyBamID BAM QC program http://genome.sph.umich.edu/wiki/VerifyBamID.  The Free measures use a statistical model based on the haplotypes discovered by the chip. The Chip measure considers the genotypes available for that individual from that chip. We use greater than 3% as a cut off for our our low coverage samples and greater than 3.5% for our exome samples.
* [FLOAT]     `VerifyBam_E_Affy_Free`
  - Value from UMich's VerifyBamID BAM QC program http://genome.sph.umich.edu/wiki/VerifyBamID.  The Free measures use a statistical model based on the haplotypes discovered by the chip. The Chip measure considers the genotypes available for that individual from that chip. We use greater than 3% as a cut off for our our low coverage samples and greater than 3.5% for our exome samples.
* [FLOAT]     `VerifyBam_E_Omni_Chip`
  - Value from UMich's VerifyBamID BAM QC program http://genome.sph.umich.edu/wiki/VerifyBamID.  The Free measures use a statistical model based on the haplotypes discovered by the chip. The Chip measure considers the genotypes available for that individual from that chip. We use greater than 3% as a cut off for our our low coverage samples and greater than 3.5% for our exome samples.
* [FLOAT]     `VerifyBam_E_Affy_Chip`
  - Value from UMich's VerifyBamID BAM QC program http://genome.sph.umich.edu/wiki/VerifyBamID.  The Free measures use a statistical model based on the haplotypes discovered by the chip. The Chip measure considers the genotypes available for that individual from that chip. We use greater than 3% as a cut off for our our low coverage samples and greater than 3.5% for our exome samples.
* [FLOAT]     `VerifyBam_LC_Omni_Free`
  - Value from UMich's VerifyBamID BAM QC program http://genome.sph.umich.edu/wiki/VerifyBamID.  The Free measures use a statistical model based on the haplotypes discovered by the chip. The Chip measure considers the genotypes available for that individual from that chip. We use greater than 3% as a cut off for our our low coverage samples and greater than 3.5% for our exome samples.
* [FLOAT]     `VerifyBam_LC_Affy_Free`
  - Value from UMich's VerifyBamID BAM QC program http://genome.sph.umich.edu/wiki/VerifyBamID.  The Free measures use a statistical model based on the haplotypes discovered by the chip. The Chip measure considers the genotypes available for that individual from that chip. We use greater than 3% as a cut off for our our low coverage samples and greater than 3.5% for our exome samples.
* [FLOAT]     `VerifyBam_LC_Omni_Chip`
  - Value from UMich's VerifyBamID BAM QC program http://genome.sph.umich.edu/wiki/VerifyBamID.  The Free measures use a statistical model based on the haplotypes discovered by the chip. The Chip measure considers the genotypes available for that individual from that chip. We use greater than 3% as a cut off for our our low coverage samples and greater than 3.5% for our exome samples.
* [FLOAT]     `VerifyBam_LC_Affy_Chip`
  - Value from UMich's VerifyBamID BAM QC program http://genome.sph.umich.edu/wiki/VerifyBamID.  The Free measures use a statistical model based on the haplotypes discovered by the chip. The Chip measure considers the genotypes available for that individual from that chip. We use greater than 3% as a cut off for our our low coverage samples and greater than 3.5% for our exome samples.
* [FLOAT]     `LC_Indel_Ratio`
  - Both Indel ratios are the ratio of insertions to deletions found in that sample using a quick test (based on samtools). If the ratio is higher than 5 the sample is withdrawn.
* [FLOAT]     `E_Indel_Ratio`
  - Both Indel ratios are the ratio of insertions to deletions found in that sample using a quick test (based on samtools). If the ratio is higher than 5 the sample is withdrawn.
* [BOOLEAN]   `LC_Passed_QC`
  - These are binary flags showing if the sample passed QC, All samples which have passed QC have bam files. Only samples which have both exome and low coverage data are found under ftp/data and listed in the standard alignment index. The small number of other samples are found in ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/phase3_EX_or_LC_only_alignment/
* [BOOLEAN]   `E_Passed_QC`
  - These are binary flags showing if the sample passed QC, All samples which have passed QC have bam files. Only samples which have both exome and low coverage data are found under ftp/data and listed in the standard alignment index. The small number of other samples are found in ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/phase3_EX_or_LC_only_alignment/
* [BOOLEAN]   `In_Final_Phase_Variant_Calling`
  - Any sample which has both LC and E QC passed bams is in the final analysis set
* [BOOLEAN]   `Has_Omni_Genotypes`
  - Omni Genotypes in ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/working/20120131_omni_genotypes_and_intensities/Omni25_genotypes_2141_samples.b37.vcf.gz   
* [BOOLEAN]   `Has_Axiom_Genotypes`
  - Axiom Genotypes in ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/working/20110210_Affymetrix_Axiom/Affymetrix_Axiom_DB_2010_v4_b37.vcf.gz         
* [BOOLEAN]   `Has_Affy_6_0_Genotypes`
  - Affy 6.0 Genotypes in  ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/working/20121128_corriel_p3_sample_genotypes/
* [BOOLEAN]   `Has_Exome_LOF_Genotypes`
  - ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/working/20121009_broad_exome_chip/ALL.wgs.broad_exome_lof_indel_v2.20121009.snps_and_indels.snpchip.genotypes.vcf.gz
* [FLOAT]     `EBV_Coverage`
  - This was calculated by looking at the alignment of the data to NC_007605 in the low coverage bam files and using that to calculate coverage   
* [STRING]    `DNA_Source_from_Coriell`
  - This was the annotated DNA Source from Coriell     
* [BOOLEAN]   `Has_Sequence_from_Blood_in_Index`
  - In the later stages of the project some populations has multiple study ids, one to indicate sequencing from blood. This data for each sample has not been treated independently in the alignment process but when there is both LCL and Blood sourced data they are both together in single bams
* [STRING]    `Super_Population`
  - From ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/20131219.superpopulations.tsv
* [STRING]    `Super_Population_Description`
  - From ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/20131219.superpopulations.tsv

-------------------------------------------------------------------------------
*Do not make edits above this line.*
