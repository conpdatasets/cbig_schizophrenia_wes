# OVERVIEW

- Project name: Schizophrenia Whole Exome Sequencing
- Project location: The Montreal Neurological Institute and Hospital, Montreal, Quebec
- Last updated: November 2022
- Contact email address: neurobioinfo@mcgill.ca, https://neurobioinfo.github.io/

The Montreal Neurological Institute and Hospital (The Neuro) Bioinformatics Core is responsible for processing, consolidating, and storing the genomics data generated for the range of studies being performed by the institute’s researchers and clinicians. As such, the data are sorted into sets based on the sequencing methodology used and the phenotype of study. The Neuro's commitment to open science practices have resulted in all of the data being made publicly available through the C-BIG initiative, following appropriate ethical approvals and the principal investigator(s) consent.

Largely, these genomics datasets were generated for the purposes of novel gene-disease relationship discovery, although other analyses may have also been performed. We recommend contacting the recruiting principal investigator(s), outlined below, for full details regarding the previous use of these datasets.

### Dataset contents
- 2292.751 GB
- FASTQ files, BAM alignments, and gVCF/VCF files
- 439 Subjects

## METHODS

### -- Recruitment --
Patients diagnosed with Schizophrenia were recruited at The Montreal Neurological Institute and Hospital (The Neuro) in the clinic of Dr. Guy Rouleau. All indivduals provided informed consent.

### -- Data Acquisition --
Whole blood was obtained from all individuals and DNA was isolated. Whole exome sequencing was performed using either the Illumina NovaSeq 6000 or the Illumina HiSeq. Sequencing reads were processed using a Burrows-Wheeler Aligner (BWA) alignment, Genome Analysis Toolkit (GATK)/Picard post-alignment, and GATK HaplotypeCaller calling pipeline.

Sequencing details: 
 
                         Machine-pairing Sequencing_center Capture_type_kit       Date
                   Illumina_HiSeq_Paired                IC      Exome_SS_V4 2017_10_17
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2010_11_22
                       ABI_SOLID3_Single              IRIC   Exome_SS_38Mbp 2010_11_09
                       ABI_SOLID3_Single              IRIC   Exome_SS_38Mbp 2010_11_02
                       ABI_SOLID4_Single              SteJ   Exome_SS_38Mbp 2011_01_20
                   Illumina_HiSeq_paired                IC      Exome_SS_V5       2015
                   Illumina_GAIIx_Paired                HK   Exome_SS_38Mbp 2010_03_08
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2010_11_12
                   Illumina_GAIIx_Paired                HK   Exome_SS_38Mbp 2017_10_06
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2010_12_02
                   Illumina_GAIIx_Paired                IC   Exome_SS_38Mbp 2017_10_06
                       ABI_SOLID3_Single              IRIC   Exome_SS_38Mbp 2010_09_17
                   Illumina_HiSeq_Paired                IC         Exome_V5 2014_11_17
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2010_11_30
              Illumina_HiSeq_4000_Paired          Macrogen      Exome_SS_V5 2016_12_02
                       ABI_SOLID4_Single              SteJ   Exome_SS_38Mbp 2011_01_25
                       ABI_SOLID4_Single              SteJ   Exome_SS_38Mbp 2011_02_15
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_02_08
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_03_09
                   Illumina_HiSeq_Paired               PGX      Exome_SS_V4 2017_10_17
                       ABI_SOLID4_Paired              SteJ   Exome_SS_50Mbp 2011_03_25
                   Illumina_HiSeq_Paired               PGX               V4      merge
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_03_10
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2010_12_30
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_01_05
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_03_23
                       ABI_SOLID4_Single              SteJ   Exome_SS_38Mbp 2010_12_02
                       ABI_SOLID4_Paired              SteJ   Exome_SS_50Mbp 2011_06_19
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_03_22
                       ABI_SOLID4_Paired              SteJ   Exome_SS_50Mbp 2011_05_12
                       ABI_SOLID4_Single              SteJ   Exome_SS_38Mbp 2011_02_12
                       ABI_SOLID4_Single              SteJ   Exome_SS_38Mbp 2011_02_08
                   Illumina_HiSeq_Paired                IC         Exome_V5      merge
                       ABI_SOLID4_Single              SteJ   Exome_SS_38Mbp 2010_07_23
                       ABI_SOLID4_Single              SteJ   Exome_SS_38Mbp 2010_08_03
                       ABI_SOLID4_Single              SteJ   Exome_SS_38Mbp 2010_08_10
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_01_28
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_01_10
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_02_23
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_02_24
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_03_06
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_03_17
                       ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2010_12_20
                       ABI_SOLID4_Single              SteJ   Exome_SS_38Mbp 2011_01_05
                       ABI_SOLID4_Single              SteJ   Exome_SS_38Mbp 2010_11_30
                   Illumina_HiSeq_Paired                IC   Exome_SS_50Mbp 2011_10_11
                   Illumina_HiSeq_Paired          Macrogen      Exome_SS_V5 2017_03_09
