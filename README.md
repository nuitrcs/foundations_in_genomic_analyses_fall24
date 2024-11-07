# Foundations in Genomic Analyses Fall 2024
This repository is a landing page for the Foundations in Genomic Analyses workshop series held in fall quarter of 2024. This series aims to cover topics and skills foundational to conducting genomics-related research and is a collaboration between Northwestern IT's Research Computing and Data Services and the Galter Library, taught by Haley Carter and Pamela Shaw. 

## Workshop 1: Filetypes and Quality Control 

Sequencing files are a unique type of data that all computational biologists should be comfortable handling. This workshop will cover the structure and use of common sequencing filetypes, including the difference between fasta and fastq, and zipped and unzipped files. We will also work through calculating quality control statistics on these filetypes with fastqc.

Materials can be found here: https://github.com/nuitrcs/genomic_filetypes

## Workshop 2: Sequence Alignment and Mapping Reads

The first step in almost all bioinformatic pipelines is sequence alignment. There are many software tools available to accomplish this task and choosing the right one and then using it at scale can be intimidating. This workshop will suggest aligners for specific tasks and cover the basics of using each suggested tool including: bwa, bowtie2, hisat2, and minimap2. Participants will compose and run submission scripts for each of these and we will look at the output they create. 

Materials can be found here: https://github.com/nuitrcs/sequence_alignment

## Workshop 3: Genome Browsers

This workshop provides a brief overview on the most popular features of two genome browsers: the UCSC Genome Browser and the Ensembl Genome Browser. The UCSC Genome Browser was created by the Genome Bioinformatics Group of the University of California at Santa Cruz. Ensembl  is a joint project between EMBL-EBI and the Wellcome Trust Sanger Institute. Both browsers allow the user to retrieve comprehensive information on a gene or genomic sequence in context of the genome, with multiple customizable tracks to display curated data from numerous external sources for features such as polymorphisms, transcript variants and histone modifications. This workshop will cover how to locate these browsers, manage tracks and annotations, how to get sequence data from the browser view, and the avenues to download data from each site – we will compare and contrast how each browser displays data, so the user can decide which is best for their purposes.  

Materials can be found here: https://github.com/galterdatalab/foundations-genomebrowsers

## Workshop 4: Sequence Similarity Searching

Sequence similarity searches can be done in multiple ways on multiple platforms.  It is useful for comparing or discovering conserved regions across sometimes very dissimilar sequences. BLAST (Basic Local Alignment Search Tool) aligns a sequence (nucleotide or peptide) to a database of other sequences, or can align two sequences to each other.  This workshop will cover the basics of sequence similarity searching with NCBI’s BLAST, as well as introduce specialized BLAST tools that can help you find statistically significant matches to a nucleotide or protein query sequence, discover homology across species, target your search to specific taxonomic groups in the BLAST database, and retrieve data for further analysis.

Materials can be found here: https://github.com/galterdatalab/foundations-sequence-similarity

## Workshop 5: Setting up an R Environment for Analysis with the GCC

R is a popular language for data analysis and many R packages have been written for genomic analysis, especially analysis of single cell RNA-seq data. Installing and managing these packages is relatively straightforward on a local laptop but performing these analyses with large genomic or transcriptomic datasets often requires more computational power than an individual laptop provides. This workshop will cover R package installation on Quest and interfacing with a custom R environment via RStudio on Quest OnDemand. We will focus on installation of Bioconductor packages and packages used with scRNA-seq data. 

Materials can be found here: https://github.com/nuitrcs/R_environments_GCC

## Workshop 6: Getting Started with nf-core Nextflow Pipelines

Nextflow is a workflow management tool designed to enable the creation of reproducible workflows that function across computational resources though the use of software containers. Many curated bioinformatics Nextflow pipelines can be found through the nf-core. In this workshop, we will explore their collection and work through running an nf-core pipeline on Quest. The biggest consideration for using Nextflow on Quest is setting the configuration to use Quest’s resources appropriately. We will cover how this is done through the nu-genomics profile for nf-core pipelines as well as writing a custom configuration file when necessary.
