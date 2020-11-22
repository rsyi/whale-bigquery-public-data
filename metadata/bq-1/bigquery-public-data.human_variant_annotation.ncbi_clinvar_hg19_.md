# `human_variant_annotation.ncbi_clinvar_hg19_`
`bq-1` | `bigquery-public-data`
Source: http://ftp.ncbi.nih.gov/pub/clinvar/vcf_GRCh37/archive/2017/clinvar_20170705.vcf.gz

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
  - NC: Inconsistent Genotype Submission For At Least One Sample
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
* [BOOLEAN]   `ASP`
  - Is Assembly specific. This is set if the variant only maps to one assembly
* [BOOLEAN]   `ASS`
  - In acceptor splice site FxnCode = 73
* [STRING]    `CAF`
  - An ordered, comma delimited list of allele frequencies based on 1000Genomes, starting with the reference allele followed by alternate alleles as ordered in the ALT column. Where a 1000Genomes alternate allele is not in the dbSNPs alternate allele set, the allele is added to the ALT column. The minor allele is the second largest value in the list, and was previuosly reported in VCF as the GMAF. This is the GMAF reported on the RefSNP and EntrezSNP pages and VariationReporter
* [BOOLEAN]   `CFL`
  - Has Assembly conflict. This is for weight 1 and 2 variant that maps to different chromosomes on different assemblies.
* [STRING]    `CLNACC`
  - Variant Accession and Versions
* [INTEGER]   `CLNALLE`
  - Variant alleles from REF or ALT columns.  0 is REF, 1 is the first ALT allele, etc.  This is used to match alleles with other corresponding clinical (CLN) INFO tags.  A value of -1 indicates that no allele was found to match a corresponding HGVS allele name.
* [STRING]    `CLNDBN`
  - Variant disease name
* [STRING]    `CLNDSDB`
  - Variant disease database name
* [STRING]    `CLNDSDBID`
  - Variant disease database ID
* [STRING]    `CLNHGVS`
  - Variant names from HGVS.    The order of these variants corresponds to the order of the info in the other clinical  INFO tags.
* [INTEGER]   `CLNORIGIN`
  - Allele Origin. One or more of the following values may be added: 0 - unknown; 1 - germline; 2 - somatic; 4 - inherited; 8 - paternal; 16 - maternal; 32 - de-novo; 64 - biparental; 128 - uniparental; 256 - not-tested; 512 - tested-inconclusive; 1073741824 - other
* [STRING]    `CLNREVSTAT`
  - no_assertion - No assertion provided, no_criteria - No assertion criteria provided, single - Criteria provided single submitter, mult - Criteria provided multiple submitters no conflicts, conf - Criteria provided conflicting interpretations, exp - Reviewed by expert panel, guideline - Practice guideline
* [STRING]    `CLNSIG`
  - Variant Clinical Significance, 0 - Uncertain significance, 1 - not provided, 2 - Benign, 3 - Likely benign, 4 - Likely pathogenic, 5 - Pathogenic, 6 - drug response, 7 - histocompatibility, 255 - other
* [STRING]    `CLNSRC`
  - Variant Clinical Chanels
* [STRING]    `CLNSRCID`
  - Variant Clinical Channel IDs
* [INTEGER]   `COMMON`
  - RS is a common SNP.  A common SNP is one that has at least one 1000Genomes population with a minor allele of frequency >= 1% and for which 2 or more founders contribute to that minor allele frequency.
* [BOOLEAN]   `DSS`
  - In donor splice-site FxnCode = 75
* [BOOLEAN]   `G5`
  - >5% minor allele frequency in 1+ populations
* [BOOLEAN]   `G5A`
  - >5% minor allele frequency in each and all populations
* [STRING]    `GENEINFO`
  - Pairs each of gene symbol:gene id.  The gene symbol and id are delimited by a colon (:) and each pair is delimited by a vertical bar (|)
* [BOOLEAN]   `GNO`
  - Genotypes available. The variant has individual genotype (in SubInd table).
* [BOOLEAN]   `HD`
  - Marker is on high density genotyping kit (50K density or greater).  The variant may have phenotype associations present in dbGaP.
* [BOOLEAN]   `INT`
  - In Intron FxnCode = 6
* [BOOLEAN]   `KGPhase1`
  - 1000 Genome phase 1 (incl. June Interim phase 1)
* [BOOLEAN]   `KGPhase3`
  - 1000 Genome phase 3
* [BOOLEAN]   `LSD`
  - Submitted from a locus-specific database
* [BOOLEAN]   `MTP`
  - Microattribution/third-party annotation(TPA:GWAS,PAGE)
* [BOOLEAN]   `NOC`
  - Contig allele not present in variant allele list. The reference sequence allele at the mapped position is not present in the variant allele list, adjusted for orientation.
* [BOOLEAN]   `NOV`
  - Rs cluster has non-overlapping allele sets. True when rs set has more than 2 alleles from different submissions and these sets share no alleles in common.
* [BOOLEAN]   `NSF`
  - Has non-synonymous frameshift A coding region variation where one allele in the set changes all downstream amino acids. FxnClass = 44
* [BOOLEAN]   `NSM`
  - Has non-synonymous missense A coding region variation where one allele in the set changes protein peptide. FxnClass = 42
* [BOOLEAN]   `NSN`
  - Has non-synonymous nonsense A coding region variation where one allele in the set changes to STOP codon (TER). FxnClass = 41
* [BOOLEAN]   `OM`
  - Has OMIM/OMIA
* [BOOLEAN]   `OTH`
  - Has other variant with exactly the same set of mapped positions on NCBI refernce assembly.
* [BOOLEAN]   `PM`
  - Variant is Precious(Clinical,Pubmed Cited)
* [BOOLEAN]   `PMC`
  - Links exist to PubMed Central article
* [BOOLEAN]   `R3`
  - In 3' gene region FxnCode = 13
* [BOOLEAN]   `R5`
  - In 5' gene region FxnCode = 15
* [BOOLEAN]   `REF`
  - Has reference A coding region variation where one allele in the set is identical to the reference sequence. FxnCode = 8
* [INTEGER]   `RS`
  - dbSNP ID (i.e. rs number)
* [INTEGER]   `RSPOS`
  - Chr position reported in dbSNP
* [BOOLEAN]   `RV`
  - RS orientation is reversed
* [BOOLEAN]   `S3D`
  - Has 3D structure - SNP3D table
* [INTEGER]   `SAO`
  - Variant Allele Origin: 0 - unspecified, 1 - Germline, 2 - Somatic, 3 - Both
* [BOOLEAN]   `SLO`
  - Has SubmitterLinkOut - From SNP->SubSNP->Batch.link_out
* [INTEGER]   `SSR`
  - Variant Suspect Reason Codes (may be more than one value added together) 0 - unspecified, 1 - Paralog, 2 - byEST, 4 - oldAlign, 8 - Para_EST, 16 - 1kg_failed, 1024 - other
* [BOOLEAN]   `SYN`
  - Has synonymous A coding region variation where one allele in the set does not change the encoded amino acid. FxnCode = 3
* [BOOLEAN]   `TPA`
  - Provisional Third Party Annotation(TPA) (currently rs from PHARMGKB who will give phenotype data)
* [BOOLEAN]   `U3`
  - In 3' UTR Location is in an untranslated region (UTR). FxnCode = 53
* [BOOLEAN]   `U5`
  - In 5' UTR Location is in an untranslated region (UTR). FxnCode = 55
* [STRING]    `VC`
  - Variation Class
* [BOOLEAN]   `VLD`
  - Is Validated.  This bit is set if the variant has 2+ minor allele count based on frequency or genotype data.
* [FLOAT]     `VP`
  - Variation Property.  Documentation is at ftp://ftp.ncbi.nlm.nih.gov/snp/specs/dbSNP_BitField_latest.pdf
* [INTEGER]   `WGT`
  - Weight, 00 - unmapped, 1 - weight 1, 2 - weight 2, 3 - weight 3 or more
* [INTEGER]   `dbSNPBuildID`
  - First dbSNP Build for RS

-------------------------------------------------------------------------------
*Do not make edits above this line.*
